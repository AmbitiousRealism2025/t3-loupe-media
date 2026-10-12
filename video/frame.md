---
name: T3 Loupe — Hackerman
canvas: 1920x1080
colors:
  ground: "#0B0C16"        # Hackerman background; the void every frame sits on
  ink: "#DDF7FF"           # primary text / lens rim
  ink-dim: "#8FA6B0"       # secondary text (ink at ~60% over ground)
  ink-faint: "#4A5762"     # hairlines, tertiary labels
  signal: "#82FB9C"        # the ONE accent: needs-you / working / the lens glint
  teal-deep: "#0E3B44"     # wallpaper horizon tint, used only as atmospheric glow
  ground-lift: "#111827"   # centre of the soft radial vignette on type-only frames
  surface: "#0F111D"       # terminal card fill
  line: "#26313C"          # terminal card hairline
typography:
  statement:
    family: "Instrument Serif"
    source: "assets/fonts/InstrumentSerif-Regular.woff2, InstrumentSerif-Italic.woff2 (@font-face, embedded)"
    weights: [400]
    use: "human statements — the claim the viewer reads; sentence case, tracking -0.03em, 96–140px"
  product:
    family: "JetBrains Mono"
    source: "bundled"
    weights: [400, 700]
    use: "the product's own voice — labels, captions, keys, the install command; uppercase tracked 0.14em for labels, 28–40px"
spacing:
  safe: 96px               # outer margin at 1920x1080
  caption-band: bottom 17% kept clear of essential content
components:
  lens:
    shape: circle, 360–520px diameter
    rim: "2px ink at 70% + 1px signal inner hairline"
    body: "same screenshot, scaled 1.8–2.2×, crisp; outside the lens the screenshot is blurred 10–14px and dimmed to ~45%"
    glint: "a soft signal-tinted bloom at the rim's upper-left, static"
  caption:
    shape: "mono label (signal, 0.14em caps) over one serif line (ink)"
  key-chip:
    shape: "1px ink-faint outline, 6px radius, mono 28px — mirrors the panel's own key hints"
---

## Overview

The film is the product's own world: Omarchy's **Hackerman** theme — near-black
ground, pale cyan ink, one phosphor-green signal. Every pixel of product UI is a
real screenshot of the demo feed; nothing is redrawn.

## The idea in the look

A **loupe**: most of the frame is out of focus and dimmed, and a single glass
circle makes one region sharp and large. The panel's dense telemetry stays
legible because the lens chooses what you read. This is literally the product's
promise — the detail you need surfaces where you look.

## Type as two voices

- **Instrument Serif** speaks for the person: short, calm statements.
- **JetBrains Mono** speaks for the machine: labels, keys, the command.

The tension is human attention vs. machine telemetry; the lens sits between them.

## Colour budget

Signal green is rationed exactly like the plugin rations it: it marks what needs
you, what is working, and the lens glint. Never a second accent, never a gradient
"AI" glow, never green body text.

## Do / Don't

- Do blur and dim the world, sharpen the subject.
- Do let the screenshot's own grid/wallpaper be the texture.
- Don't invent UI, thread titles, or numbers that aren't in the demo screenshots.
- Don't use rounded "glassmorphism" cards, bokeh, particles, or neon outlines.
- Don't imply Loupe can approve or act — it is read-only; acting happens in T3.
