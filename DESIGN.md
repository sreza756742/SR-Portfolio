# Sanjid R Portfolio — Design System

## Direction

An editorial, image-led portfolio influenced by the spatial confidence of Grid Agency without reproducing its page. The site uses oversized type, generous black space, precise rules, tactile red/cobalt imagery and a deliberately restrained interface.

## Foundations

- Canvas: `#050505`
- Primary text: `#f4f4f1`
- Secondary text: `#9b9b97`
- Rules: `rgba(244, 244, 241, 0.28)`
- Accent red: `#ff2318`
- Accent cobalt: `#123cff`
- Typeface: Manrope Variable, self-hosted through Fontsource
- Horizontal gutter: `clamp(1rem, 3.2vw, 3.75rem)`
- Major section rhythm: `clamp(7rem, 12vw, 12rem)`

## Layout

- Desktop navigation is a three-part fixed header: mark, centred navigation, contact.
- Hero fills the viewport and balances service labels against the main statement.
- Work uses two equal columns on desktop and one column on compact screens.
- Section introductions use an oversized title paired with concise supporting copy.
- Services and process are structured as full-width ruled rows, not floating cards.
- Mobile retains the same hierarchy while converting asymmetric grids into a clear vertical sequence.

## Motion

- GSAP ScrollSmoother supplies native-scroll-based interpolation on wheel, touch, and anchor navigation across the site.
- GSAP ScrollTrigger controls section reveals, process wipes, and image parallax inside the shared ScrollSmoother coordinate system.
- Motion is progressive enhancement: all core content remains semantic and usable without it.
- Touch devices retain native scrolling.
- `prefers-reduced-motion` disables interpolation and animation.

## Image Treatment

- Project imagery uses cover crops inside consistent landscape frames.
- Hero and contact share a red/cobalt translucent material study.
- Studio imagery is monochrome with a single cobalt accent.
- Process imagery is a continuous four-stage material sequence cropped into individual frames.
