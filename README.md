# mamg22's `st` build

This is my build/fork of the [suckless terminal](https://st.suckless.org/), with a few nice patches.

It uses the Iceberg set of colors.

## Building

`st` requires `fontconfig` and the X11 and Xft headers, it's probable you have them already. `make` is also required. Build it doing:

```
git clone https://github.com/mamg22/st.git
cd st
sudo make install
```

## Extras

Some features and keybinds added are:

- Scrollback line by line with `alt+shift+j` and `alt+shift+k`, and scroll screens with `alt+shift+f` and `alt+shift+b`.
- Font resize also with `alt+shift+h` and `alt+shift+l`.
+ Copy and paste from clipboard with `alt+shift+c` and `alt+shift+v`.
- Boxdraw patch for better line rendering.

## Patches applied

- st-alpha-0.8.2
- st-anysize-0.8.1
- st-boxdraw_v2-0.8.2
- st-scrollback-20190331-21367a0
