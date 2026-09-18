# AOA EP

**Naked Nuras Loves Rave**  
NLS Records · Friday drop · 18 September 2026  
Masters **010819** · MP3 160k / 44.1 kHz / stereo

Plate: [iama.cc/catalogue/aoa](https://iama.cc/catalogue/aoa/)  
Interpreter: [MAGMA](https://cobalt-tulip-royal-orchid.grok.me/)  
Git for [@nlsrecords](https://x.com/nlsrecords) — this repository is the distribution.

Cover: [`cover.png`](cover.png)

## Audio

| # | Title | Time | File |
|---|---|---|---|
| 01 | MORE'S LOW | 8:10 | [`audio/mores-low.mp3`](audio/mores-low.mp3) |
| 02 | TRACK FOR | 8:15 | [`audio/track-for.mp3`](audio/track-for.mp3) |
| 03 | GETAFIX | 5:37 | [`audio/getafix.mp3`](audio/getafix.mp3) |
| 04 | TRYTO | 11:37 | `audio/tryto.mp3` — drop in |

Same encode as GETAFIX:

```bash
ffmpeg -i "AOA - TRACK FOR_(Mastered_010819).wav" \
  -c:a libmp3lame -b:a 160k -ar 44100 -ac 2 \
  audio/track-for.mp3
```

## MAGMA buses

- **MORE'S LOW** — protocol / strata. Form follows function.
- **TRACK FOR** — improved noise / meshwork curl.
- **GETAFIX** — MixKey. The potion when the two machines agree.
- **TRYTO** — surplus circulation. The try.

## Play

```bash
git clone https://github.com/nonlineari/aoa-ep.git
cd aoa-ep
ffplay audio/mores-low.mp3
ffplay audio/track-for.mp3
ffplay audio/getafix.mp3
```

Site players: [iama.cc/catalogue/aoa](https://iama.cc/catalogue/aoa/)

© NLS Records / Naked Nuras Loves Rave
