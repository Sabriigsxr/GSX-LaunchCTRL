# GSX-LAUNCHCTRL

**Launch Smarter. Execute Harder.**

A complete pre-launch brand identity, marketing kit, and landing site for GSX-LAUNCHCTRL — a local-first AI coding-agent CLI built for developers who push limits.

---

## Brand at a Glance

| Element | Detail |
|---------|--------|
| **Name** | GSX-LAUNCHCTRL |
| **Tagline** | LAUNCH SMARTER. EXECUTE HARDER. |
| **Secondary** | Power Under Control. |
| **Campaign** | Same Passion. New Frontier. |
| **Personality** | Aggressive, Controlled, Mechanical, Technical, Premium, Independent |
| **Colors** | Obsidian Black, Carbon Black, Racing Blue, Electric Cyan, Redline Red |
| **Fonts** | Space Grotesk (display), Inter (body), IBM Plex Mono (terminal) |

---

## What Is GSX-LAUNCHCTRL?

GSX-LAUNCHCTRL is a performance-focused AI coding-agent CLI. It gives developers a deliberate, coordinated, and controllable workflow:


---

## Repository Structure

```
GSX-LAUNCHCTRL/
├── README.md                         # This file — brand & marketing overview
├── brand/                            # Complete brand identity system
│   ├── guidelines/
│   │   ├── 01-brand-overview.md      # Personality, positioning, audience
│   │   ├── 02-logo-system.md         # Logo variations, clear space, misuse
│   │   ├── 03-color-system.md        # Color palette, gradients, accessibility
│   │   └── 04-motion-photography.md  # Typography, motion, photo aesthetic
│   ├── design-tokens/
│   │   ├── colors.json               # Color system in JSON
│   │   ├── typography.json           # Type scale and font families
│   │   ├── spacing.json              # 8px base unit spacing + breakpoints
│   │   └── tokens.css                # CSS custom properties
│   └── logo/
│       ├── gsx-launchctrl-wordmark.svg       # Horizontal wordmark
│       ├── gsx-launchctrl-monogram.svg       # App icon / favicon
│       ├── gsx-launchctrl-monochrome.svg     # Single-color print
│       ├── gsx-launchctrl-blue-black.svg     # Dark background version
│       └── gsx-launchctrl-favicon.svg        # Browser favicon
├── campaign/                         # Pre-launch campaign assets
│   ├── photos/
│   │   └── prompts.md                # 10 AI image generation prompts
│   ├── video/
│   │   └── storyboards.md            # 3 video storyboards with shot lists
│   └── coming-soon/
│       └── poster-design.md          # Poster layout brief
├── social/                           # Social media strategy
│   ├── style-guide.md                # Voice, tone, visual guidelines
│   ├── content-calendar.md           # 4-week publishing plan
│   └── asset-inventory.md            # Complete asset catalog
└── website/                          # Responsive landing page
    ├── index.html                    # Single-page landing site
    ├── scripts/
    │   └── main.js                   # Terminal typing + navigation
    └── styles/
        ├── base.css                  # Design tokens + resets
        ├── components.css            # Typography, buttons, cards
        ├── layout.css                # Terminal, nav, hero, grid
        ├── responsive.css            # Mobile breakpoints
        └── terminal.css              # Active nav state, output colors
```

---

## Quick Start — Preview the Landing Page

```bash
# Clone the repository
git clone https://github.com/Sabriigsxr/GSX-LaunchCTRL.git
cd GSX-LaunchCTRL

# Serve the website locally
python3 -m http.server 8000

# Open http://localhost:8000/website/index.html
```


---

## Motion Principles

- **Precise cuts** over fades
- **Controlled light sweeps** for reveals
- **Short glitch accents** (1-2 frames) for digital precision
- **Speed ramps** for dramatic emphasis
- **Subtle motion blur** only on high-speed transitions
- All animations disableable via `prefers-reduced-motion`

---

## Campaign Assets

### Photo Generation (10 prompts)

Hero images, social assets, and merchandise designs ready for Midjourney/DALL·E/Stable Diffusion. See `campaign/photos/prompts.md`.

### Video Storyboards (3 videos)

1. **Brand Reveal** (15s) — "Same Passion. New Frontier."
2. **Product Vision** (30s) — "Power Under Control"
3. **Coming Soon** (10s) — Vertical stories/reels format

See `campaign/video/storyboards.md`.

### Coming Soon Poster

24" × 36" print poster layout with full color and typography specifications. See `campaign/coming-soon/poster-design.md`.

---

## Social Media Strategy

**Voice:** Aggressive, controlled, mechanical, technical, premium, independent

**4-Week Content Calendar:**
- Week 1: Brand Awareness
- Week 2: Feature Education
- Week 3: Behind the Scenes
- Week 4: Launch Readiness

**Hashtags:** #GSXLaunchCtrl #LaunchCtrl #GSX #AI #DevTools #LocalFirst #CLI #Terminal #MCP #Ollama #BuildInPublic

See `social/style-guide.md`, `social/content-calendar.md`, `social/asset-inventory.md`.

---

## Usage Rules

- Black and blue are the primary palette
- Red is a restrained accent — like a tachometer entering the redline
- White/silver for text hierarchy on dark backgrounds
- Never place Racing Blue (#087BFF) on Carbon Black (#111722) — insufficient contrast
- All animations disableable via `prefers-reduced-motion`
- Logo minimum readable size: 24px height for horizontal wordmark
- Do NOT imply the software controls real vehicles or performs ECU tuning. The automotive identity is purely creative direction for a developer tool.

---

## License

This is a brand identity and marketing kit for GSX-LAUNCHCTRL. Use only on systems you own or have explicit written authorization to test.

---

**Built with:** Space Grotesk, Inter, IBM Plex Mono, CSS, HTML, JavaScript

**Status:** IN DEVELOPMENT — Pre-launch deliverables

**Follow the build:** https://github.com/Sabriigsxr/gsxr
---

## Design System

### Color Palette

| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| Obsidian Black | `#080B10` | 8, 11, 16 | Primary background |
| Carbon Black | `#111722` | 17, 23, 34 | Secondary background |
| Racing Blue | `#087BFF` | 8, 123, 255 | Links, primary buttons |
| Electric Cyan | `#21C8FF` | 33, 200, 255 | Highlights, accents |
| Clean White | `#F5F7FA` | 245, 247, 250 | Primary text |
| Metallic Silver | `#C7D0DC` | 199, 208, 220 | Secondary text |
| Redline Red | `#FF3048` | 255, 48, 72 | Accent, warnings |

### Typography

| Element | Font | Weight | Use |
|---------|------|--------|-----|
| Display / Headlines | Space Grotesk | 400–900 | Hero, section headings |
| Body | Inter | 300–700 | Paragraphs, captions |
| Terminal / Code | IBM Plex Mono | 400–700 | Commands, status, code |

### Gradients

**Primary (hero, buttons):**
```
linear-gradient(135deg, #087BFF 0%, #21C8FF 100%)
```

**Accent (status, highlights):**
```
linear-gradient(90deg, #087BFF 0%, #21C8FF 50%, #FF3048 100%)
```
1. **PLAN** — Define the mission with clear objectives and scope
2. **SELECT** — Choose the right model and tools for each task
3. **COORDINATE** — Organize workflow with deterministic agent handoffs
4. **EXECUTE** — Work with full visibility and controlled execution

**Local-first by design.** Ollama, HexStrike MCP, and RAG knowledge base — all running on your machine, not in the cloud.