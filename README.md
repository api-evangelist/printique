# Printique (printique)

Printique (An Adorama Company, formerly **AdoramaPix**) is a professional online photo lab based in Brooklyn, NYC. It produces photo prints, fine-art giclee prints, photo books, albums, wall decor (metal, acrylic, canvas, glass, framed, and wood), cards, calendars, and photo gifts. AdoramaPix was established in 1998 and rebranded to Printique effective October 3, 2019.

## Access Model — No Public API

**Printique does not publish a documented public developer or fulfillment API.** There is no developer portal, no API reference, no API keys or authentication documentation, and no OpenAPI definition on the open web. The only Printique-hosted endpoint that exists is an undocumented internal web-application backend (e.g. `https://www.printique.com/app/api/user`) that serves the printique.com storefront — it is **not** a published, supported, or documented public API.

Programmatic and automated ordering is delivered entirely through **prebuilt partner-platform integrations**, not a Printique-owned API:

- **Squarespace** — syncs products and automates order fulfillment directly from a seller's own site.
- **PhotoShelter** — wholesale print-and-product integration for professional photographers; wholesale costs are billed on a monthly statement, with white-label blind shipping.
- **Fundy Designer** — album design integration.
- **Adobe Lightroom** and **Capture One** — desktop plugins that publish images directly to Printique.

Because no public API surface is documented, the API entries in `apis.yml` are honestly **modeled** (`endpointsModeled: true`) from Printique's public product, Pro-for-business, integration, and FAQ pages. They are labeled "(Modeled)", carry no base URL, and no endpoints or schemas have been fabricated.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/printique/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/printique/refs/heads/main/apis.yml)

## Tags

- Photo Printing
- Print Fulfillment
- Photo Lab
- Photography
- Prints
- Albums
- Wall Art
- Print on Demand

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## APIs (Modeled)

These are conceptual surfaces that describe how Printique ordering and fulfillment work through partner platforms. Printique publishes no public paths, parameters, or schemas for any of them.




## Plans and Pricing

Printique sells **no API access**. Its commercial model is per-product retail pricing plus an optional **Printique Pro** membership:

- **Pro membership:** $14.95/month or $159.95/year.
- **Tiered wholesale savings:** Silver 15% (up to $1,000/yr spend), Gold 20% ($1,000–$10,000/yr), Platinum 25% ($10,000+/yr).
- **Benefits:** wholesale savings, white-label blind shipping, dedicated Pro support, enhanced QC, and the Squarespace / PhotoShelter / Fundy integrations.
- **Shipping:** free U.S. economy shipping on orders over $100 (some exclusions).

See [`plans/printique-plans-pricing.yml`](plans/printique-plans-pricing.yml).

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/printique-by-adorama)
- [Website](https://www.printique.com)
- [Documentation](https://www.printique.com/company/printique-pro-photo-lab-for-businesses/)
- [Integrations](https://support.photoshelter.com/hc/en-us/articles/203373130-Printique-formerly-known-as-AdoramaPix)
- [Plans](plans/printique-plans-pricing.yml)
- [Blog](https://www.printique.com/blog/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
