## Trekkie — Pebble Watchface

![In action](http://i.imgur.com/gh8vOxD.png)

![Design](http://i.imgur.com/X5LgINj.png)

An LCARS-inspired Pebble watchface. Swanky. [Download!](http://www.mypebblefaces.com/view?fID=458&aName=zachbruggeman&pageTitle=Trekkie&auID=472)

*I hold no responsibility if this breaks your Pebble! This is built using the early Proof of Concept SDK, and may be unstable.* I use it on my Pebble without issues though. :smile:

### Building

Because remembering paths is a pain, I've set up a Makefile to do that for you. Make sure to clone this watch into the proper directory:

```
git clone https://github.com/remixz/trekkie.git /path/to/pebble-sdk/watches/trekkie
cd trekkie
make setup
```

Then, to build, just run:
```
make build
```

Installing it on your Pebble is a bit more of an adventure. I install it using [`libpebble`](https://github.com/pebble/libpebble). If you are on Android, you can also serve the .pbw on a web-server and download it.
