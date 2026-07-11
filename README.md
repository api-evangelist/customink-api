# Custom Ink (customink-api)

Custom Ink is a direct-to-consumer (DTC) custom apparel and promotional products company. Groups design and order custom t-shirts, hoodies, hats, drinkware, bags, and other branded merchandise through an online Design Lab, get instant price quotes, and place orders with full-service fulfillment at [customink.com](https://www.customink.com/).

> **Access model — honest, gated stub.** As of the review date (2026-07-11), Custom Ink does **not** publish a public or partner developer API. There is no developer portal, no published API reference, no OpenAPI description, no SDK, and no partner API documentation for products, designs, quotes, or orders. An internal API host, `api.customink.com`, backs Custom Ink's own web and mobile storefront and is secured behind AWS API Gateway and Amazon Cognito (documented on Custom Ink's own engineering blog), but it is **private, undocumented, and not offered to third-party developers**. Custom Ink's "partners" program is a commercial/business relationship (colleges, brands, licensing, artwork/fonts), not a technical developer integration.

Because there is no documented public API, this catalog entry is a **stub**. The single API listed in `apis.yml` is explicitly **modeled** (`endpointsModeled: true`) from Custom Ink's public product surface — it is a set of logical capability groupings for cataloging purposes only and contains **no fabricated endpoints**. No `openapi/`, `plans/`, `rate-limits/`, `finops/`, or `collections/` artifacts were created, because no sourced API surface, price plans, or metered rates exist to document.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/customink-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/customink-api/refs/heads/main/apis.yml)

## Tags

- Custom Apparel
- T-Shirts
- Print on Demand
- Promotional Products
- eCommerce
- Design
- No Public API

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## APIs

### Custom Ink Storefront API (Modeled)

A single, honestly **modeled** logical surface representing what a Custom Ink developer API could cover:

- **Products** — garment styles, colors, and sizes available in the catalog.
- **Design** — Design Lab artwork upload, placement, and preview rendering.
- **Quotes** — instant price by product, ink-color count, and order quantity.
- **Orders** — order submission, proof approval, and fulfillment/status tracking.

This is **not** a documented public API. `endpointsModeled` is `true`; no concrete endpoints are claimed. The internal `api.customink.com` host that powers Custom Ink's own apps is private, undocumented, and out of scope for third-party use.

- **Human URL:** [https://www.customink.com/](https://www.customink.com/)

## Pricing

Custom Ink pricing is an all-inclusive, **per-order** model determined by three factors — the product selected, the number of ink colors, and the total order quantity — with volume discounts and free setup, design review, and shipping (48 US states, APO, and Canada). Quotes are obtained interactively via the Design Lab "$" button, the quick-quote tool, or customer service. There is **no** programmatic (API) quote or pricing access and no published API price plans. See [Get a Price Quote](https://www.customink.com/help_center/get-a-price-quote).

## Common Properties

- [Website](https://www.customink.com/)
- [LinkedIn](https://www.linkedin.com/company/customink)
- [GitHub Organization](https://github.com/customink)
- [Documentation (Help Center)](https://www.customink.com/help_center)
- [Partners](https://www.customink.com/about/partners)
- [Pricing](https://www.customink.com/help_center/get-a-price-quote)
- [Blog (Engineering)](https://technology.customink.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
