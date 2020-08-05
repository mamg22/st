# mamg22's `st` build

This is my build/fork of the [suckless terminal](https://st.suckless.org/), with a few nice patches.

This `st` fork doesn't have scrollback, it uses tmux in all windows using the `tmux-launch` script.

It uses the Iceberg colorscheme.

## Building

`st` requires `fontconfig`, `make`, and the X11 and Xft headers. Then:

```
git clone https://github.com/mamg22/st.git
cd st
make
sudo make install
```

## Extras

Some features and keybinds added are:

- Font size increase and decrease with `ctrl+shift+l` and `ctrl+shift+h`.
* Clipboard copy/paste with `ctrl+shift+c` and `ctrl+shift+v`.
- Boxdraw patch for better line rendering.

## Patches applied

- alpha
- anysize
- boxdraw
