# Home Weather Station Comparison — 2026

A structured comparison of 14 current home weather station models and model families, maintained by [WX Observation](https://wxobservation.com/).

The dataset is intended for homeowners, weather hobbyists, educators, and developers who need a compact way to compare sensor layout, measurements, update cadence, radio range, displays, connectivity, expandability, and important ownership tradeoffs.

## Dataset

[`home-weather-station-comparison-2026.csv`](./home-weather-station-comparison-2026.csv) contains one row per model or model family and 20 fields:

- Identity: brand, model, current status, and broad price tier.
- Fit: best-for summary, sensor layout, and measurements.
- Hardware: wind method, rain method, update cadence, and radio range.
- Ownership: display, connectivity, expandability, lightning, and UV/solar support.
- Editorial context: key strength, key limitation, canonical review URL, and evidence-review date.

The current dataset covers Ambient Weather, WeatherFlow Tempest, Davis Instruments, AcuRite, La Crosse Technology, and Sainlogic.

## Why the comparison avoids exact prices

Retail prices, bundles, stock, and hardware revisions change too quickly for a static public dataset. The `Price tier` field therefore uses broad categories such as Entry, Value, Midrange, Premium, and High premium. Check current manufacturer documentation and the linked review before making a purchase decision.

## Methodology

WX Observation reconciled the fields against refreshed review research and public product records in August 2026.

- Published line-of-sight range is not a promise of real-world performance. Walls, terrain, radio interference, and placement can reduce it substantially.
- Update cadence can vary by measurement, console, firmware, and product revision. Qualifying language is retained where a single interval would be misleading.
- `Best for`, `Key strength`, and `Key limitation` are WX Observation editorial summaries, not manufacturer claims.
- A model-family row can cover several bundles. Verify the precise model number and included components before relying on a field.

For the expanded testing and review methodology, see the [home weather station review hub](https://wxobservation.com/weather-station-reviews/).

## Example: two closely related Ambient Weather models

The dataset is useful for filtering broad differences, but some decisions require more context than a row can carry. The [Ambient Weather WS-2000 vs. WS-2902 comparison](https://wxobservation.com/ambient-weather-ws-2000-vs-ws-2902/) explains how console quality, indoor sensor placement, expansion options, and price affect that specific choice.

## Suggested uses

- Filter models by measurement set or sensor layout.
- Compare integrated arrays with systems that allow independent wind or rain placement.
- Build a shortlist before checking current prices and bundles.
- Create classroom exercises about measurement tradeoffs and observational error.
- Prototype a personal weather station selector or visualization.

## Corrections and updates

Product documentation changes. If a field appears outdated, open an issue with:

1. The brand and model.
2. The field that needs correction.
3. A current manufacturer manual or support-page URL.
4. The relevant page, section, or quoted specification.

Corrections are reviewed before the CSV is changed. See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for the evidence standard.

## Disclosure and reuse

The dataset contains no retailer affiliate links. Some linked WX Observation review pages may contain affiliate links and display their own disclosures.

No open-data license has been applied to this first release. The repository may be viewed and cited, but reuse rights remain reserved until the owner selects a license. Suggested citation:

> WX Observation. “Home Weather Station Comparison — 2026.” Reviewed August 8, 2026. https://wxobservation.com/

