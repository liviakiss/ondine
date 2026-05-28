# Ondine — Ocean Conservation Landing Page

A cinematic, scroll-driven landing page for **Ondine**, a fictional European ocean conservation nonprofit. Built as a portfolio piece exploring calm-design principles applied to environmental work.

🌊 **Live demo:** [liviakiss.github.io/ondine](https://liviakiss.github.io/ondine/)

## The idea

Most environmental nonprofit sites lead with statistics and urgency — "8 million tons of plastic," anxious red call-to-actions. That triggers fatigue, not action. Ondine does the opposite: it makes you *fall in love with the ocean first*, then shows what's at stake, then what's being done, then invites you in.

The emotional sequence — **awe → reality → hope → action** — is the cognitive psychology working invisibly.

## The signature interaction

A fixed full-bleed video background sits behind the content the entire scroll. As you descend, the foreground text scrolls over it while the background scene slowly crossfades from one depth to the next. The visitor stays "underwater" the whole journey — only the scene changes.

## Features

- Sticky video background with slow crossfade transitions between sections
- Gentle count-up numbers that animate as the impact section enters view
- A calm donation section with selectable tiers (no urgency, no pressure)
- Drifting bioluminescent particles and ambient depth dimming
- Scroll-progress navigation dots
- Mobile-first responsive layout

## Built with

- Vanilla HTML, CSS, and JavaScript — no frameworks
- `IntersectionObserver` for scroll-triggered reveals, background crossfades, and count-ups
- [Newsreader](https://fonts.google.com/specimen/Newsreader) (serif headlines) + [Inter](https://fonts.google.com/specimen/Inter) (body)
- Background video hosted on Cloudinary

## Design notes

| Element | Choice |
|---|---|
| Palette | Midnight blue `#050B1A`, abyssal navy `#0B1B33`, off-white text `#E8E6E1` |
| Accent | A single bioluminescent cyan-teal `#7FE3D4`, used only on interactive moments |
| Motion | Slow, 400–800ms ease-out — no bouncing, no parallax tricks |
| Whitespace | Generous, to reduce cognitive load |

## Status

Demo build — hero plus mission, what we do, the reality, impact, and donation sections. A full build would add the team & transparency section, the three-path "how to help" block, and the footer.

---

Designed and built by [Lívia Kiss](https://alivedesignstudio.net) · ALIVE Design Studio