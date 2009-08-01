Google Voice Growler
====================

Google Voice Growler is a userscript for [Google Voice](http://google.com/voice) running in
[Fluid](http://fluidapp.com).

The script:
* Automatically checks for new items (SMS, voicemail, and missed calls)
* Triggers Growl notifications (great for prowl)
* Updates the [Dock badge](http://www.flickr.com/photos/malabooboo/3724142785/) count

Installation
------------

Browse to this page in your Google Voice Fluid app, and [click here](http://github.com/cjmartin/gVoiceGrowler/blob/820af1591f4f8af4876954d931d0864205464a3e/gVoiceGrowler.user.js)

or

Download the file gVoiceGrowler.user.js and drag it into your running app


Known issues
------------

Google voice doesn't auto-refresh like gmail. This script retrieves the same XML document
that is called by manually clicking the "refresh" link above the inbox but I can't decipher
the actual function that is called to update the page, therefore Growl and the dock badge
will update but the page content itself will not. If someone with more JS mojo than I have
wants to figure out what function is being called please do and let me know.

Clicking around in the app, marking things read etc. won't be reflected in the dock badge
until the next 30 sec update takes place.