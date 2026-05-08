# DocRaptor (docraptor)

DocRaptor is an HTML-to-PDF / HTML-to-Excel document generation API powered by Prince XML. Strong CSS-paged-media support including headers/footers, page breaks, watermarks and accessibility tags. Synchronous and asynchronous renders; document hosting available.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **DocRaptor REST** — `https://api.docraptor.com` — `POST /docs` (sync), `POST /async_docs` + status polling (async). HTTP Basic auth (API key as username). [Docs](https://docraptor.com/documentation).

## OpenAPI
DocRaptor does not currently publish a downloadable OpenAPI/Swagger document at a stable public URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`. SDKs are available for PHP, Python, Node, Ruby, Java and .NET.

## Tags
Document Generation, PDF, HTML, Excel, API, Prince

## Common Properties
- [Website](https://docraptor.com/) · [Docs](https://docraptor.com/documentation) · [Pricing](https://docraptor.com/plans) · [GitHub](https://github.com/DocRaptor)
- [Plans](plans/docraptor-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/docraptor-rate-limits.yml) — partially reconciled (per-second numeric ceiling not public)
- [FinOps](finops/docraptor-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Free** — 5 docs/mo (+ unlimited free watermarked test docs).
- **Basic** — $15/mo, 125 docs, $0.12/doc overage.
- **Professional** — $29/mo, 325 docs.
- **Premium** — $75/mo, 1,250 docs.
- **Max** — $149/mo, 5,000 docs.
- **Bronze** — $399/mo, 15,000 docs.
- **Silver** — $1,000/mo, 40,000 docs.
- **Gold** — $2,250/mo, 100,000 docs.
- **Enterprise** — custom.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
