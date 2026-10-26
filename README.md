# Printique (printique)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
