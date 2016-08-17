Graph 89
===
Graph 89 is a Ti graphing calculator emulator targeting the Android platform,
supporting both the Z80 family(83, 83+, 83+SE, 84+, 84+SE) via [TilEm](http://lpg.ticalc.org/prj_tilem/)
and the 68000 family(89, 89Ti, 92+, Voyage 200) via [TiEmu](http://lpg.ticalc.org/prj_tiemu/)

this amazing piece of software was written by
[Dritan Hashorva](https://bitbucket.org/dhashoandroid/)

He open sourced Graph 89 in Nov 2013, and no updates since that.

anybody want to show gratitude to the developer should buy
[the original in Play store](https://play.google.com/store/apps/details?id=com.Bisha.TI89EmuDonation)
and/or donate to
[TILP](http://lpg.ticalc.org/prj_tilp/),
[TiEmu](http://lpg.ticalc.org/prj_tiemu/),
[TilEm](http://lpg.ticalc.org/prj_tilem/).

what does this fork do
---
1. compiled using newer tool chain.
2. compiled with APP_ABI := all so it should work on arm64-v8a and x86_64 devices now, not tested though.
3. immersive fullscreen, works but kinda buggy, see #2

I'm very new to Android development, and my time on this project is limited, but any suggestion and help will be appreciated.

License
---
just like the original Graph 89: GPL V3