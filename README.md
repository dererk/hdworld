hdworld, a Slip based screensaver that mimics the behaviour of a digital painting
======================================================================================

Even though this screen saver works with both xlockmore-gl and xscreensaver, the last one is prefered.


Installation
------------

1. Fetch and install xscreensaver or xlockmore (opengl version) from your prefered location/Operative System's packaging method
2. Download your OS's building chain under xscreensaver/xlockmore-gl. On Debian systems this means:
    apt-get source xscreensaver (or xlockmore-gl)
3. Install slip.c into xscreensaver/xlockmore-gl "hacks/" directory
4. Recompile
5. Enjoy!


Configuration
-------------

This is handled by your screensaver daemon, but the following should work on both cases:
    slip -root -delay 100000 -count 17


License
-------

Permission to use, copy, modify, and distribute this software and its
documentation for any purpose and without fee is hereby granted,
provided that the above copyright notice appear in all copies and that
both that copyright notice and this permission notice appear in
supporting documentation.

This file is provided AS IS with no warranties of any kind.  The author
shall have no liability with respect to the infringement of copyrights,
trade secrets or any patents by this file or any part thereof.  In no
event will the author be liable for any lost revenue or profits or
other special, indirect and consequential damages.
