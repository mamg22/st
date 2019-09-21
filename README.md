# mamg22's `st` build

This is my build/fork of the [suckless terminal](https://st.suckless.org/), with many patches to provide a wonderful experience.

It uses the Iceberg set of colors by default, but can read the ones in Xresources.

## Building

`st` requires `fontconfig` and the X11 and Xft headers, it's probable you have them already. `make` is also required. Build it doing:

```
git clone https://github.com/mamg22/st
cd st
sudo make install
```

## Patches applied

- st-alpha-0.8.2
- st-anysize-0.8.1
- st-bold-is-not-bright-20190127-3be4cf1
- st-boxdraw_v2-0.8.2
- st-externalpipe-0.8.2
- st-font2-20190416-ba72400
- st-hidecursor-0.8.1
- st-newterm-0.8.2
- st-scrollback-20190331-21367a0
- st-scrollback-mouse-0.8.2
- st-vertcenter-20180320-6ac8c8a
- st-xresources-20190105-3be4cf1
