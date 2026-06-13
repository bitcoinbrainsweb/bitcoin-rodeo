# Design brief: Bitcoin Rodeo

Inherits: brainframe-design-registry default-brief.md (v0.3.0+)
Precedence: this file then default-brief then registry hard default.
Forbidden overrides (ignored if set here): a11y-motion guards, content-parity rule, breakpoint scale.

## Deltas over default

lane: maximalist
marginalia: off
grid-min-cell: 240px
grid-max-cols: 5
motion-strategy: GSAP ScrollTrigger heavy; pinned sections and stagger encouraged
gsap-plugins: ScrollTrigger, SplitText, Flip
one-unforgettable-moment: a pinned, oversized lineup wall that reshuffles on scroll

## Inherited unchanged from default-brief
type scale, font sourcing, motion-tokens timing, layout-system (auto-fit grid, density tiers, max-width ban), footer/mark/og-meta/trust-strip, GSAP baseline lifecycle.
