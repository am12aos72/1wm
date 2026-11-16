# 1wm

**VERY golf wm. NOT TO BE CONFUSED WITH lslvr/1wm.**

written from 0, not based on other!!! this is my main wm and if u use dwm or other mini wm u can try this. i can say ts is a dwm but very small.

## functions

- 5 layouts (master/stack, spiral, dwm-style, monocle, grid)
- 12 tags + move windows between them
- mouse drag/resize
- fullscreen
- ring cycle
- focus follows mouse
- `_NET_SUPPORTED`, `_NET_CLIENT_LIST`, `_NET_ACTIVE_WINDOW`
- wall clamp
- spawn `st`

## usable?

yes. i live in it. 44 lines, 11 blocks, one file `1wm.c`. no config, no deps beyond libX11.

```sh
cc 1wm.c -lX11 -o 1wm




