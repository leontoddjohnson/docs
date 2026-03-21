---
title: tutti
bookCollapseSection: false
booktoc: false
---

# tutti

all together.

## set up

**requirements**

- norns
- mx.samples (see below)
- midi controller(s)

**in maiden ...**

```
;install https://github.com/leontoddjohnson/tutti
```

## there's not much to it

> This script is an extension to @infinitedigits's [mx.samples](https://llllllll.co/t/mx-samples/41400).

Right now, this script is completely relegated to the `PARAMS` page. Select instruments, MIDI sources, and channels. Then, adjust parameters for each instrument as you would normally for mx.samples.

**Note: parameters only update prior to note play.** So, adjusting the amp (velocity) or panning on a note that is already playing will not do anything.

By default, you can select up to **four** instruments, but you can change this by updating the `N_INSTRUMENTS` variable in the script.

> [!CAUTION]
> Right now, this script uses a noise parameter that was added to [my fork of the mx.samples repository](https://github.com/leontoddjohnson/mx.samples/tree/main). Until [the pull request](https://github.com/schollz/mx.samples/pull/13) is merged, you'll need to either (a) clone the fork, or (b) remove the noise parameter [here](https://github.com/leontoddjohnson/tutti/blob/6c3fa899667d4a76458568f9eab888756e34262e/tutti.lua#L143) and [here](https://github.com/leontoddjohnson/tutti/blob/6c3fa899667d4a76458568f9eab888756e34262e/tutti.lua#L201).
