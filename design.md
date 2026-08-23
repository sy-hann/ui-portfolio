# Design — SY H. Portfolio

A locked visual system for the portfolio. All four pages share this system.

## Genre
Modern-minimal with a technical editorial rhythm.

## Macrostructure family
- Main page: asymmetric profile introduction, project-led long document, compact experience index, closing contact panel.
- Project detail pages: editorial case study with a broad hero, scan-first metadata, narrow narrative text and alternating evidence blocks.

## Theme
Warm Sage: a warm cream paper paired with deep forest ink and a restrained sage accent.

- `--color-paper`: `oklch(96.5% 0.014 95)`
- `--color-paper-2`: `oklch(93% 0.016 95)`
- `--color-surface`: `oklch(98.5% 0.008 95)`
- `--color-ink`: `oklch(22% 0.025 155)`
- `--color-ink-2`: `oklch(45% 0.025 155)`
- `--color-rule`: `oklch(83% 0.018 115)`
- `--color-accent`: `oklch(82% 0.075 145)`
- `--color-accent-strong`: `oklch(48% 0.105 155)`
- `--color-focus`: `oklch(50% 0.12 155)`
- Dark mode: deep forest paper, mineral-green surfaces, pale neutral ink and a brighter sage accent.

## Typography
- Display: system sans-serif, 650–700, roman
- Body: Open Sans, 400–600
- Mono/metadata: system monospace, 500
- Headings use a compact scale and balanced wrapping; body copy remains between 62–72 characters per line.

## Spacing
4-point named scale. Layout uses tokens from `tokens.css`; section rhythm is generous without making every block identical.

## Motion
- Transform and opacity only.
- Short, quiet hover transitions.
- Reduced-motion disables spatial movement.

## CTA voice
- Primary: dark rectangular fill with a small radius and direct verb-led copy.
- Secondary: quiet text link with an arrow and visible focus ring.

## Shared rules
- The SY H. wordmark, accent colour, typography and CTA treatment stay consistent.
- Project screenshots are evidence, not decoration; no fake browser or device chrome.
- Featured work receives substantially more space than the project archive.
- Detail pages preserve Overview, Project Info, My Role and Key Experience content.
