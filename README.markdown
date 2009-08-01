Google Voice Growler
====================

Google Voice Growler is a userscript for [Google Voice](http://google.com/voice) running in
[Fluid](http://fluidapp.com). The script:

* Automatically checks for new items (SMS, voicemail, and missed calls)
* Triggers Growl notifications (great for prowl)
* Updates the [Dock badge](http://www.flickr.com/photos/malabooboo/3724142785/) count

Installation
------------

Browse to this page in your Google Voice Fluid app, and [click here](http://github.com/cjmartin/gVoiceGrowler/raw/master/gVoiceGrowler.user.js)

or Download the file gVoiceGrowler.user.js and drag it into your running app


Known issues
------------

Google voice doesn't auto-refresh like gmail. This script retrieves the same XML document
that is called by manually clicking the "refresh" link above the inbox but I can't decipher
the actual function that is called to update the page, therefore Growl and the dock badge
will update but the page content itself will not. If someone with more javascript mojo than I have
wants to figure out what function is being called please do and let me know.

Clicking around in the app, marking things read etc. won't be reflected in the dock badge
until the next 30 sec update takes place.

License
-------

(The MIT License)

Copyright (c) [Chris Martin](http://cjmart.in)

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.