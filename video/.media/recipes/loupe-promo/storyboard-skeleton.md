---
format: 1920x1080
duration: 45s
arc: Demo Loop — hook → in the bar → lens on what needs you → lens on what it's doing → every machine, your theme → install
music: none
---

## Video direction

- **Palette** (from `frame.md`): ground `#0B0C16`, ink `#DDF7FF`, signal `#82FB9C` only for needs-you / working / the lens glint. Screenshots carry the teal wallpaper; we add no other colour.
- **Type**: Instrument Serif for the human statement (one line per beat, ≤ 7 words); JetBrains Mono for labels, keys and the command.
- **Signature device — the loupe.** Outside the lens: screenshot blurred and dimmed. Inside: the same screenshot magnified and sharp. The lens glides between targets on long-tail eases (`viewport-change`, `coordinate-target-zoom`, `depth-of-field-blur`); it never wanders aimlessly — every move lands on something the caption names.
- **Motion grammar**: smooth `power3` settles, no bounce. Captions reveal on their beat, never front-loaded. Holds are still (subtle jitter at most). Only the final frame exits.
- **Rhythm**: F1 quick type beats → F2 one decisive zoom → F3/F4 lens tour (the body) → F5 the breather (wide, still, beautiful) → F6 calm end card that holds.
- **Silent-safe**: README autoplays muted; every idea is carried by on-screen text. Music skipped for now (user, 2026-10-12); silent cut.
- **Negative list**: no invented UI or numbers; no claim that Loupe approves/acts (it is read-only — "answer in T3"); no bokeh, particles, neon outlines, purple gradients; no slideshow front-loading; no floating/breathing elements.

## Frame 1 — Hook: busy agents

- on_screen: "Six agents working." → "Two machines." → "One is waiting on you." (last line, "waiting on you" in signal)
- duration: 6s
- transition_in: cut
- status: outline
- src: compositions/frames/01-hook.html
- type: hook
- persuasion: Pain validation
- beat: tension
- blueprint: kinetic-type-beats (Adapt — three calm beats instead of slams; serif, not display caps)

<fill in: this video's content for the "Hook: busy agents" beat — keep the layout role, replace the words.>

## Frame 2 — It lives in your bar

- on_screen: mono label "T3 LOUPE" · serif "Every agent. One ring."
- duration: 6s
- transition_in: blur-crossfade
- status: outline
- src: compositions/frames/02-bar.html
- type: product_intro
- persuasion: Show-don't-tell proof
- beat: curiosity → clarity
- blueprint: compose (`coordinate-target-zoom` + the lens)

<fill in: this video's content for the "It lives in your bar" beat — keep the layout role, replace the words.>

## Frame 3 — The lens finds what needs you

- on_screen: "NEEDS YOU" label · serif "What's blocked comes first." → "The exact command it's waiting on."
- duration: 9s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/03-needs-you.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: relief + control
- blueprint: device-surface-showcase (Adapt — keep the real-surface, stepwise, cursorless loop; the lens replaces cropping as the focus device)

<fill in: this video's content for the "The lens finds what needs you" beat — keep the layout role, replace the words.>

## Frame 4 — The lens reads what it's doing

- on_screen: serif "Every tool call, live." → "Context, cost, PRs, subagents." → "Plan and runs, at a glance."
- duration: 10s
- transition_in: crossfade
- status: outline
- src: compositions/frames/04-detail.html
- type: feature_showcase
- persuasion: Feature-to-benefit translation
- beat: confidence
- blueprint: compose (`viewport-change` lens path + `depth-of-field-blur`)

<fill in: this video's content for the "The lens reads what it's doing" beat — keep the layout role, replace the words.>

## Frame 5 — Every machine, your theme

- on_screen: mono "laptop · build-box" (from the screenshot) · serif "Every machine. Your theme." · key chip "f  toggle view"
- duration: 7s
- transition_in: blur-crossfade
- status: outline
- src: compositions/frames/05-wide.html
- type: benefit_highlight
- persuasion: Friction reduction
- beat: ease
- blueprint: zoom-out-workspace-reveal (Adapt — the pull-back from a tight crop of the dropdown to the whole desktop is the signature move; no workspace grid)

<fill in: this video's content for the "Every machine, your theme" beat — keep the layout role, replace the words.>

## Frame 6 — Install

- on_screen: "T3 Loupe" · serif "See every agent at a glance." · `$ git clone github.com/AmbitiousRealism2025/t3-loupe && tools/install.sh` · "For Omarchy · T3 Code"
- duration: 7s
- transition_in: zoom-through
- status: outline
- src: compositions/frames/06-install.html
- type: cta
- persuasion: Friction reduction
- beat: motivation
- blueprint: prompt-type-submit-generate (Reproduce — CTA install end-card variant; the demoting headline + terminal pill typing is the signature)

<fill in: this video's content for the "Install" beat — keep the layout role, replace the words.>
