ez430-original-firmware
=======================

ez430-original-firmware

Just a mspdebug dump of the ez430 original firmware (done with [this procedure](http://tthtlc.wordpress.com/2011/01/23/disassembling-the-ti-ez430-chronos-an-open-source-watch-software-development/) )

May not be suitable for old releases, as it seems to be a new hardware.

Flash it with 

```bash
mspdebug -q rf2500 "prog ez430.hex" 
```

Use it as your own risks.
