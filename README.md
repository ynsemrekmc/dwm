# My build of dwm

## Information about this repository This is a direct fork of [Luke
Smith's build of dwm](https://github.com/LukeSmithxyz/dwm) and is
customized for my personal use case.

## FAQ

> What are the bindings?

This is suckless, mmmbud, the source code is the documentation! Check out [config.h](config.h).

## Patches and features

- [Clickable statusbar](https://dwm.suckless.org/patches/statuscmd/) with my build of [dwmblocks-async](https://github.com/ynsemrekmc/dwmblocks-async).
- Reads [xresources](https://dwm.suckless.org/patches/xresources/) colors/variables (i.e. works with `pywal`, etc.).
- scratchpad: Accessible with <kbd>mod+shift+enter</kbd>.
- New layouts: bstack, fibonacci, deck, centered master and more. All bound to keys <kbd>super+(shift+)t/y/u/i</kbd>.
- True fullscreen (<kbd>super+f</kbd>) and prevents focus shifting.
- Windows can be made sticky (<kbd>super+s</kbd>).
- [hide vacant tags](https://dwm.suckless.org/patches/hide_vacant_tags/) hides tags with no windows.
- [stacker](https://dwm.suckless.org/patches/stacker/): Move windows up the stack manually (<kbd>super-K/J</kbd>).
- [shiftview](https://dwm.suckless.org/patches/nextprev/): Cycle through tags (<kbd>super+g/;</kbd>).
- [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/): Gaps allowed across all layouts.
- [swallow patch](https://dwm.suckless.org/patches/swallow/): if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.
- [systray patch](https://dwm.suckless.org/patches/systray/): Add a system tray for application in the status bar.


## Installation for newbs

```bash
git clone https://github.com/ynsemrekmc/dwm.git
cd dwm
sudo make install
```
