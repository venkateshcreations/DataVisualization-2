# GlobalTech Industries — Digital Transformation Intelligence Hub

An interactive enterprise portfolio dashboard built with **D3.js v7** featuring 9 interconnected data visualizations that map GlobalTech Industries' digital transformation journey from 2023 to 2027.

## Features

- **9 D3.js charts** — Sankey, Sunburst, Circle Packing, Force Network, Treemap, Tangled Tree, Capability Heatmap, Revenue Line Chart, Maturity Rings
- **Multi-phase timeline** — 5-year journey (2023–2027) with phase switching via navigation bar, timeline, or keyboard arrows (<kbd>←</kbd> <kbd>→</kbd>)
- **Dark theme** — Custom CSS variables, animated grid background, ambient glow orbs
- **Fullscreen mode** — Floating control bar with Esc to exit
- **Search** — <kbd>⌘K</kbd> to search 120+ initiatives across all pillars
- **Settings panel** — Accent color, animation speed, card visibility, grid toggle
- **Card controls** — Collapse/expand, cycle height, export SVG, reset zoom
- **Layout modes** — Grid, List, Focus
- **Pillar filtering** — Strategy, Technology, Data, Operations, Customer, Innovation
- **Responsive** — CSS Grid layout adapts to viewport width
- **Right-click context menu** on charts
- **Export** individual SVGs or all charts at once
- **Minimap** quick navigation

## Charts

| Chart | Type | Description |
|-------|------|-------------|
| Sankey | `#card-sankey` | Digital value flow across 3 streams (Tech, Data, Ops) |
| Sunburst | `#card-sunburst` | Programme taxonomy with click-to-zoom and rotation |
| Circle Packing | `#card-circlepack` | Scope map with drill-down by clicking bubbles |
| Force Network | `#card-force` | Capability dependency graph with drag, pin, charge control |
| Treemap | `#card-treemap` | Investment map with drill-down and tile algorithm switching |
| Tangled Tree | `#card-tangled` | Tech evolution 2023→2027 with filter by track |
| Capability Map | `#card-orgmap` | Maturity heatmap with heat/number/bar display modes |
| Revenue Chart | `#card-revenue` | Revenue & digital growth line chart with annotations |
| Maturity Rings | `#card-rings` | Pillar maturity ring gauges animated on phase change |

## Datasets

- `Enterprise Digital Transformation Journey Dataset.json`
- `Force Network Relationships Dataset.json`
- `Additional Dataset for Sankey Diagram.json`

## Usage

Open `index.html` in any modern browser. No build step required — D3.js is loaded from CDN.
