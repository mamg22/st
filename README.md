# mamg22's `st` build

This is my build/fork of the [suckless terminal](https://st.suckless.org/), with some patches to provide a wonderful experience.

It uses the Iceberg set of colors.

## Building

`st` requires `fontconfig` and the X11 and Xft headers, it's probable you have them already. `make` is also required. Build it doing:

```
git clone https://github.com/mamg22/st
cd st
sudo make install
```

## Extras

Some features and keybinds added are:

- Scrollback line by line with `alt+j` and `alt+k`, and scroll screens with `alt+f` and `alt+b`.
- Font resize also with `alt+shift+j` and `alt+shift+k`.
- New terminal in the current directory with `alt+shift+return`.
- Copy and paste from clipboard with `alt-c` and `alt-v`.
- Boxdraw patch for better line rendering.

## Patches applied

- st-alpha-0.8.2
- st-anysize-0.8.1
- st-bold-is-not-bright-20190127-3be4cf1
- st-boxdraw_v2-0.8.2
- st-externalpipe-0.8.2
- st-newterm-0.8.2
- st-scrollback-20190331-21367a0
- st-scrollback-mouse-0.8.2
