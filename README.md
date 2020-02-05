Graph 89

===
Graph 89 is a
[Ti graphing calculators](https://education.ti.com/en/us/products#!product=graphing-calculators)
emulator targeting the Android platform,
supporting both 68000 family(89, 89Ti, 92, 92+, Voyage 200) via [TiEmu](http://lpg.ticalc.org/prj_tiemu/)
and Z80 family(83, 83+, 83+SE, 84+, 84+SE) via [TilEm](http://lpg.ticalc.org/prj_tilem/).

this amazing piece of software was written by
[Dritan Hashorva](https://bitbucket.org/dhashoandroid/),
He open sourced Graph 89 in Nov 2013, and (seems) ceased developing since then.

anybody want to show gratitude to the developers should buy
[the original in Play store](https://play.google.com/store/apps/details?id=com.Bisha.TI89EmuDonation)
and/or donate to
[TILP](http://lpg.ticalc.org/prj_tilp/),
[TiEmu](http://lpg.ticalc.org/prj_tiemu/),
[TilEm](http://lpg.ticalc.org/prj_tilem/).

download and usage
---
APK is available at the [release](https://github.com/Twilight/Graph89/releases) page,
for how to use, take a look at [the introduction page of the original](https://play.google.com/store/apps/details?id=com.Bisha.TI89EmuDonation).

what have this fork done
---
1. compiled using newer tool chain.
2. compiled with `APP_ABI := all` so it should work on newer devices now, not tested though. the resulting APK is bigger as a side effect.
3. immersive fullscreen, works but kinda buggy, see issue #2.

I'm very new to Android development, and my time on this project is limited, but any suggestion and help will be appreciated.

License
---
GPL V3, just like the original.
