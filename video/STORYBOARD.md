---
format: 1920x1080
duration: 45s
message: "Every T3 Code agent, on every machine, in one glance — the detail you need surfaces the moment you look."
arc: Demo Loop — hook → in the bar → lens on what needs you → lens on what it's doing → every machine, your theme → install
audience: developers running T3 Code agents on Omarchy, landing on the GitHub README
mode: collaborative
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

- scene: dark Hackerman ground; three serif lines land one at a time
- voiceover: ""
- on_screen: "Six agents working." → "Two machines." → "One is waiting on you." (last line, "waiting on you" in signal)
- duration: 6s
- transition_in: cut
- status: animated
- src: compositions/frames/01-hook.html
- type: hook
- persuasion: Pain validation
- beat: tension
- blueprint: kinetic-type-beats (Adapt — three calm beats instead of slams; serif, not display caps)
- asset_candidates: none (typography only)

Scene 1 (0–1.6s): "Six agents working." reveals word-by-word centred (`dynamic-content-sequencing`).
Scene 2 (1.6–3.2s): hard swap (zoom-through seam, `cut-catalog.md`) to "Two machines."
Scene 3 (3.2–6s): inverse zoom-through arrival on "One is waiting on you."; "waiting on you" warms to signal; hold.

narrativeRole: name the pain — you can't see which agent is blocked without switching windows.
keyMessage: something needs you, and you don't know which.

## Frame 2 — It lives in your bar

- scene: the Hackerman desktop, dimmed; the loupe drops from the top-right bar as a callout over "T3 Loupe ⓯ ④"
- on_screen: mono label "T3 LOUPE" · serif "Every agent. One ring."
- duration: 6s
- transition_in: blur-crossfade
- status: animated
- src: compositions/frames/02-bar.html
- type: product_intro
- persuasion: Show-don't-tell proof
- beat: curiosity → clarity
- blueprint: compose (`coordinate-target-zoom` + the lens)
- asset_candidates: assets/screens/bar.png — full desktop with the bar; assets/screens/desktop.png — empty wallpaper fallback

Scene 1 (0–1.5s): full desktop, wallpaper sun + wireframe mountains, dimmed; still.
Scene 2 (1.5–3.5s): a small signal marker pings the bar item; a leader line drops and the loupe opens beneath the bar as a callout (`coordinate-target-zoom` on the lens content) — "T3 Loupe", the ring and the "4" badge read big and crisp.
Scene 3 (3.5–6s): caption reveals below the lens: "T3 LOUPE" then "Every agent. One ring."; hold.

narrativeRole: name the product and where it lives.
keyMessage: a glanceable ring in the Omarchy bar.

## Frame 3 — The lens finds what needs you

- scene: the two-pane window, blurred; the lens glides to the Needs-you rows, then onto the exact pending command
- on_screen: "NEEDS YOU" label · serif "What's blocked comes first." → "The exact command it's waiting on."
- duration: 9s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/03-needs-you.html
- type: feature_showcase
- persuasion: Show-don't-tell proof
- beat: relief + control
- blueprint: device-surface-showcase (Adapt — keep the real-surface, stepwise, cursorless loop; the lens replaces cropping as the focus device)
- asset_candidates: assets/screens/approval.png — two-pane, Inbox, pending "Run command?" approval

Scene 1 (0–2.5s): the window settles in, world blurred; lens arrives on the Needs-you list (4 rows: run command, question, plan, failed). Caption 1 reveals.
Scene 2 (2.5–6.5s): the lens glides right onto the approval card — `git push --force-with-lease …` and the Allow once / Allow for session / Decline options read sharp. Caption 2 swaps in (waterfall cut).
Scene 3 (6.5–9s): small mono footnote fades in: "Read-only · answer in T3 with o"; hold.

narrativeRole: the core value — the blocked thing is first, with its full context.
keyMessage: you see what needs you before you switch windows.

## Frame 4 — The lens reads what it's doing

- scene: the hero two-pane (Active, "Design a robust T3 Loupe plugin" selected); the lens tours activity → facts → plan/runs
- on_screen: serif "Every tool call, live." → "Context, cost, PRs, subagents." → "Plan and runs, at a glance."
- duration: 10s
- transition_in: crossfade
- status: animated
- src: compositions/frames/04-detail.html
- type: feature_showcase
- persuasion: Feature-to-benefit translation
- beat: confidence
- blueprint: compose (`viewport-change` lens path + `depth-of-field-blur`)
- asset_candidates: assets/screens/hero.png — two-pane, working thread with activity, facts strip, plan, runs, subagents

Scene 1 (0–3.2s): lens on the ACTIVITY list (T3's own icons: read, terminal, bot, thought, edit). Caption 1.
Scene 2 (3.2–6.6s): lens glides up to the facts strip — 2 subagents running · PR #412 · 731k / 1M context · $13. Caption 2.
Scene 3 (6.6–10s): lens drops to PLAN 6 of 9 and the RUNS chart. Caption 3; hold.

narrativeRole: depth — everything about a thread without opening it.
keyMessage: the detail surfaces when you look at it.

## Frame 5 — Every machine, your theme

- scene: the lens pulls back and dissolves; the full desktop with the compact dropdown under the bar, sun and wireframe mountains — the breather
- on_screen: mono "laptop · build-box" (from the screenshot) · serif "Every machine. Your theme." · key chip "f  toggle view"
- duration: 7s
- transition_in: blur-crossfade
- status: animated
- src: compositions/frames/05-wide.html
- type: benefit_highlight
- persuasion: Friction reduction
- beat: ease
- blueprint: zoom-out-workspace-reveal (Adapt — the pull-back from a tight crop of the dropdown to the whole desktop is the signature move; no workspace grid)
- asset_candidates: assets/screens/dropdown.png — compact dropdown over the full Hackerman wallpaper

Scene 1 (0–2.5s): tight on the dropdown's header (machines row), pull back to the whole desktop.
Scene 2 (2.5–5s): serif line reveals left over the sky: "Every machine. Your theme."
Scene 3 (5–7s): key chip "f  toggle view" fades in beneath; hold still — the breather.

narrativeRole: breadth — multi-machine, theme-native, dropdown or window.
keyMessage: it belongs on your desktop.

## Frame 6 — Install

- scene: ground; the ring mark draws itself, "T3 Loupe" lockup, the headline demotes and a terminal pill types the clone command; repo URL; hold
- on_screen: "T3 Loupe" · serif "See every agent at a glance." · `$ git clone github.com/AmbitiousRealism2025/t3-loupe && tools/install.sh` · "For Omarchy · T3 Code"
- duration: 7s
- transition_in: zoom-through
- status: animated
- src: compositions/frames/06-install.html
- type: cta
- persuasion: Friction reduction
- beat: motivation
- blueprint: prompt-type-submit-generate (Reproduce — CTA install end-card variant; the demoting headline + terminal pill typing is the signature)
- asset_candidates: none (typography + SVG ring)

Scene 1 (0–2s): ring arc draws (`svg-path-draw`) with segments in ink and one in signal; "T3 Loupe" wordmark beside it; tagline reveals.
Scene 2 (2–5.2s): lockup demotes upward; `$` chip stretches into a terminal pill; command types behind a caret.
Scene 3 (5.2–7s): "For Omarchy · T3 Code" fades in; hold; final fade to ground.

narrativeRole: the ask.
keyMessage: one clone and one script.
