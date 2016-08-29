# i3-config
A personal custom i3wm config. 

ATTENTION, this config file is not intend to be a universal one. There might be some differences between different distributions. There might be some errors while using it. PLEASE read the offical document for the first time using i3.

**This document is still under development.**

## Requirement

### Software
* [i3-gaps](https://github.com/Airblader/i3)
* [compton](https://github.com/chjj/compton)
* conky (Optional)

### Fonts
* Noto Sans
* Font Awesome

## Document

### i3-gaps installing
i3-gaps is a forked i3wm version by a core developer, it adds many useful features that the orginal i3 doesn't contain. Unfortunatly, for the most Linux distributions, there are no packaged i3-gaps. So, it is required to compile from source.

The [wiki](https://github.com/Airblader/i3/wiki/Compiling-&-Installing) gives a detailed instruction to compile the i3-gaps.

ATTENTION, for the latest version of i3-gaps, it requires the [xcb-util-xrm](https://github.com/Airblader/xcb-util-xrm) which also can't be installed easily through many Linux distribution's official repository. Please compile by yourself.

### compton installing

compton is a compositor designed for X11. If it is not provided by your distribution's offical repository, please compile it from [the source](https://github.com/chjj/compton). 

### Key Binding

Super Key(Windows Key) is used as the main key.

Fit the vim opreating habitat.

#### Move

`Super + M` is the toggle of the Move Mode.

`↑` or `j` Move up.

`↓` or `k` Move down.

`←` or `h` Move left.

`→` or `l` Move right.

`Escape` or `Enter` Exit Move mode/Return to normal mode.

#### Resize

`Super + R` is the toggle of the Resize Mode.

`j` Increase height.

`k` Decrease height.

`h` Decrease width.

`l` Increase width.

`Escape` or `Enter` Exit Move mode/Return to normal mode.

### i3 status bar

This config use i3status as status bar program.

## Reference
[boring2 by dkeg](http://dotshare.it/dots/588/)

[i3-wm-config by benkaiser](https://github.com/benkaiser/i3-wm-config)

## License
This config file is licensed under GNU/GPL version 3.