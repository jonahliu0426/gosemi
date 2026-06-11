# GoSemi — Semiconductor Supply-Chain Explorer

A single-page interactive explorer for semiconductor investors and analysts, served at **[gosemi.app](https://gosemi.app)**.

Two views, fully bilingual (English / 简体中文):

1. **EUV Machine Explorer** — interactive cutaway of an ASML TWINSCAN-class EUV scanner. Hover any component for vendors, materials, manufacturing toolchain, and estimated share of system value (Low-NA vs High-NA basis toggle).
2. **Chip-Making Process Flow** — all 15 stages from chip design to final test. Each stage has an interactive schematic, equipment/materials with estimated per-wafer $ contribution, hover panels with makers and tickers, and per-stage company market-share pie charts.

## Tech

Zero dependencies — one self-contained `index.html` (vanilla HTML/CSS/JS + inline SVG). Open it in any browser, or serve statically.

## Disclaimer

Cost shares, per-wafer dollar figures and market shares are directional analyst estimates synthesized from public sources; vendors do not disclose these numbers precisely. Nothing here is investment advice.
