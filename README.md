# mamg22's `st` build

This is my build/fork of the [suckless terminal](https://st.suckless.org/), with a few nice patches.

It uses the Iceberg colorscheme.

## Building

`st` requires `fontconfig` and the X11 and Xft headers, it's probable you have them already. `make` is also required. Build it doing:

```
git clone https://github.com/mamg22/st.git
cd st
sudo make install
```

## Extras

Some features and keybinds added are:

- Scrollback line by line with `ctrl+shift+j` and `ctrl+shift+k`, and scroll screens with `ctrl+shift+f` and `ctrl+shift+b`.
- Font size increase and decrease with `ctrl+shift+l` and `ctrl+shift+h`.
* Clipboard copy/paste with `ctrl+shift+c` and `ctrl+shift+v`.
- Boxdraw patch for better line rendering.

## Patches applied

- alpha
- anysize
- boxdraw
- scrollback
