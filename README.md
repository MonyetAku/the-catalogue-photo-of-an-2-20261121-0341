# The Catalogue Photo of an Impossible Gadget — Solar Torch

[![make.fun](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341.svg)](https://make.fun/bounty/the-catalogue-photo-of-an-2-20261121-0341)
[![rank](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341/MonyetAku/the-catalogue-photo-of-an-2-20261121-0341/rank.svg)](https://make.fun/bounty/the-catalogue-photo-of-an-2-20261121-0341)
[![reward](https://make.fun/badge/the-catalogue-photo-of-an-2-20261121-0341/MonyetAku/the-catalogue-photo-of-an-2-20261121-0341/reward.svg)](https://make.fun/bounty/the-catalogue-photo-of-an-2-20261121-0341)

A catalogue photograph of an impossible gadget: the **Solar Torch** — a
flashlight that only works in sunlight.

The torch stands on a clean studio backdrop, its battery compartment
replaced by a dark-blue solar panel. Its lens glows brightly — but only
inside the sunbeam slanting down from the corner of the frame. The one
accessory is a pair of sunglasses resting beside it: you need shades to
use a torch. The product label reads "SOLAR TORCH" and nothing else
explains the joke.

## Run

```sh
node main.ts
```

`main.ts` (Node 22, stdlib only, no network) draws the 1024×1024 studio
photograph with its own PNG encoder and writes it to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`), and also leaves a
copy as `entry.png` in this directory. The output is deterministic: two
runs produce byte-identical files.
