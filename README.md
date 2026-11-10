# T3 Loupe — media

Promo video, screenshots and design-review images for [T3 Loupe](https://github.com/AmbitiousRealism2025/t3-loupe), the live T3 Code thread monitor for the Omarchy bar.

They live here so the plugin repository stays small: `omarchy plugin add` clones the whole plugin repository, history included, onto every user's machine.

| Path | What it is |
|---|---|
| [`t3-loupe-promo.mp4`](t3-loupe-promo.mp4) | 45-second promo, 1920×1080, silent |
| [`t3-loupe-teaser.gif`](t3-loupe-teaser.gif) | 9-second loop of the lens tour, used as the plugin README header |
| [`screens/2.6.0/`](screens/2.6.0) | README screenshots from 2.6.0 on: built-in demo feed, Omarchy's Matte Black theme |
| [`screens/2.5.10/`](screens/2.5.10) | The 2.5.10 screenshots, kept so older links still work |
| [`screens/`](screens) | Screenshots of the UI before the 2.5.7 redesign, Hackerman theme. Kept so older links still work |
| [`design-review/`](design-review) | The visual design review and its before/after mocks |
| [`video/`](video) | [HyperFrames](https://github.com/heygen-com/hyperframes) source for the promo: brief, storyboard, design spec, six frame compositions |

## Rebuilding the promo

```sh
cd video
npx hyperframes@0.8.150 preview                               # Studio
npx hyperframes@0.8.150 render -o renders/t3-loupe-promo-master.mp4 --fps 30 -q looks
```

All screenshots show T3 Loupe's built-in demo feed; no real threads, machines or tokens.

MIT © 2026 ambitiousrealism. Fonts in `video/assets/fonts/` (Instrument Serif, JetBrains Mono) are under the SIL Open Font License.
