# Design Direction

## Project Mood
High-octane, technical, and heavily graphic. The site should feel like a piece of high-performance machinery or a live telemetry feed—functional, unapologetic, and immediate. It should evoke the energy of underground car culture and professional motorsport, trading conventional web polish for raw, mechanical authenticity. 

## Visual Keywords
Telemetry, High-Contrast, Utilitarian, Engineered, Constraint-First, Asphalt, Kinetic, Raw.

## Color Direction
A heavy, dark-mode foundation punctuated by aggressive, high-visibility accents.
* **Primary Backgrounds (Abyssal Blacks/Tarmac Grays):** `#090907`, `#0C0C09`, `#1E1E1D`, `#262625`
* **High-Visibility Accents (Racing Reds & Oranges):** `#F88000` (Vibrant Orange), `#D76F00`, `#660F1F` (Deep Red), `#500C18`
* **Technical Information/Muted Accents (Cool Blues):** `#9096D3`, `#686C99`, `#515477`
* *Note: Text should utilize the lighter grays and blues to reduce eye strain against the deep black backgrounds, reserving pure white only for critical focal points.*

## Typography Direction
A strict, two-tiered typographic hierarchy focused on data transmission and impact.
* **Display / Headings:** A heavy, extended, engineered sans-serif (e.g., Space Grotesk, Druk Wide, or Monument Extended). It should feel like it belongs on the side of an LMP1 endurance car.
* **Body / UI / Data:** A highly legible, technical monospace font (e.g., JetBrains Mono, Roboto Mono, or IBM Plex Mono). Used for all body copy, metadata, tags, and navigation to reinforce the "telemetry" dashboard feel.

## Layout Direction
A rigid, utilitarian grid system. Think technical manuals and data dashboards. Use visible borders, hard lines, and distinct modular panels to separate content. Do not use soft drop shadows or floating elements; everything should be anchored to the grid. Information density can be high, relying on typographic contrast rather than negative space to guide the eye.

## Image / Media Direction
Photography and media should maintain a high-contrast, dramatic visual style with crushed blacks and vibrant highlights. Imagery should feel cinematic and slightly gritty—embrace film grain, motion blur, and raw textures. Avoid highly sanitized, well-lit corporate stock photography or overly smooth, plastic-looking AI generations. 

## References
* Formula 1 promotional graphics and data readouts.
* MotoGP and FIA WEC event posters.
* McLaren x OKX branding campaigns.
* Industrial technical catalogs (e.g., BICC Cables).
* Gilles Villeneuve / classic motorsport typographic layouts.

## Avoid
* Soft, diffused gradients or "glassmorphism."
* Sterile, frictionless, or overly "friendly" tech-startup minimalism.
* Over-polished, glossy AI-generated aesthetics; preserve the human touch and the "half-formed" edges of the creative process.
* Rounded corners (border-radius should be 0px or extremely minimal, like 2px).

## Notes for the Coding Agent
* **CSS Grid:** Rely heavily on CSS Grid for the macro-layout. Use 1px solid borders (using one of the mid-grays like `#313130`) to visibly demarcate sections, creating a blueprint or dashboard aesthetic.
* **Constraint-First:** Build the component patterns strictly. The design system must prioritize structural integrity above all else. 
* **Interactions:** Hover states should be harsh and immediate (e.g., instantaneous background color swaps or hard underlines) rather than slow, easing transitions.
* **Authenticity over Polish:** Do not attempt to "clean up" the layout with excessive padding if it compromises the technical density. The interface should feel like a working tool, not just a presentation layer.
