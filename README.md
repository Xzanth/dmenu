# DMenu: Quiet, centering, padding, line-height ratio, Xft

### [dmenu's README](https://github.com/RyanMcG/dmenu/blob/master/README)

## What's different?

This fork of dmenu adds centering (`-c`), padding (`-d`), line-height ratio (`-lr`) and prompt only (`-po`) options. It is based on the following patches:

* [QXYW](http://github.com/baskerville/dmenu_qxyw)
* [Xft support](http://aur.archlinux.org/packages.php?ID=59497)
* [Height](http://aur.archlinux.org/packages.php?ID=59497)
* [Prompt Only](http://github.com/stilvoid/dmenu)

## Usage

```
dmenu_run -c -lr 2 -d 0.1 -fn 'Inconsolata for Powerline-10'
```
