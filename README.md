# Figma 

# StudyNest Landing Page

A responsive product landing page for **StudyNest**, a fictional study-planner app for college students. It's a single self-contained HTML file with no external dependencies.

## Files

| File | Description |
|------|-------------|
| `StudyNest.html` | The landing page |
| `README.md` | This file |

## Running the Page

No build step or installation is needed.

1. Download `StudyNest.html`.
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari).
3. Resize the window or use the browser's device toolbar to check responsive behavior.

## Target Audience

Undergraduate students aged 18 to 24 who manage assignments, quizzes, lab submissions, and exam preparation across several subjects.

## Sections

- Header with logo, navigation, and a call-to-action button
- Hero with heading, description, primary and ghost buttons, and an animated app mockup
- Trusted-by logo strip
- Feature cards (adaptive planner, smart flashcards, focus sessions)
- Stats row
- Three-step "how it works" timeline
- Testimonials
- Pricing (three tiers, with the middle tier highlighted)
- FAQ with expandable items
- Gradient call-to-action banner
- Footer

## Features

- Dark theme with an animated aurora background and grid overlay
- Glass-style cards that lift on hover and follow the cursor with a glow
- Scroll-reveal animations
- Shimmering gradient headline text
- Fully responsive layout

## Design System

### Colors

| Token | Hex | Use |
|-------|-----|-----|
| Primary | `#6366F1` | Buttons, links, highlights |
| Pink | `#EC4899` | Gradients |
| Cyan | `#22D3EE` | Accents, icons, progress |
| Accent | `#F59E0B` | Badges, CTAs, warnings |
| Text | `#E2E8F0` | Headings and body text |
| Muted | `#94A3B8` | Secondary text |
| Background | `#070B1F` | Page background |

### Typography

- Font: Inter, with system-ui fallbacks
- Headings scale fluidly with `clamp()`
- Body text: 1rem with 1.6 line height

### Spacing

Spacing uses a consistent scale of 0.5rem, 1rem, 1.5rem, 3rem, and 5rem.

### Components

- **Button:** primary (gradient) and ghost (glass)
- **Header:** logo, nav links, action button
- **Feature card:** icon, heading, description, link
- **Stat card**
- **Step item**
- **Testimonial card**
- **Pricing card**
- **FAQ item**
- **Footer:** logo, link columns, copyright line

## Responsive Breakpoints

| Breakpoint | Layout changes |
|------------|----------------|
| Above 1024px | Three-column grids |
| 1024px and below | Two-column grids, stacked pricing |
| 860px and below | Single-column hero (centered), nav hidden, steps stacked |
| 600px and below | Single-column cards and footer, tighter padding |

## Accessibility

- Semantic HTML: `header`, `main`, `section`, `footer`, `nav`, `article`, `figure`
- Decorative elements are marked `aria-hidden`
- Animations are disabled for users who prefer reduced motion
- Text is designed to be readable on the dark background

## Known Limitations

- The mobile navigation is hidden. A full build would add a hamburger menu.
- All links use `#` placeholders.
- Logos, testimonials, names, pricing, and statistics are placeholder content and must be replaced before real use.
- The glass effect uses `backdrop-filter`, which older browsers may not support. The page still works without it.

## Figma Mapping

| Code element | Figma equivalent |
|--------------|------------------|
| CSS variables (`:root`) | Color and text styles |
| `.btn` variants | Button component with variants |
| `.feature-card` | Feature card component |
| `.site-header` | Header component (Auto Layout) |
| Breakpoints | Desktop (1440px) and mobile (375px) frames |

## Credits

Created as a student assignment for the "Create a responsive product landing page" exercise.
