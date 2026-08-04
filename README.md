# Reducto (reducto)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Reducto is an agentic document platform providing a REST API for parsing, extracting, splitting, classifying, and editing complex documents such as PDFs, Word files, spreadsheets, presentations, and scanned images. The platform uses layout-aware OCR and vision language models to preserve tables, figures, and complex layouts with high fidelity, delivering structured JSON output optimized for LLM consumption. Reducto has processed over 3 billion pages and serves enterprises across finance, healthcare, legal, and insurance sectors with SOC 2 and HIPAA compliance, support for 100+ languages and 30+ file formats, and an MCP server for AI agent integration.

APIs.json: https://raw.githubusercontent.com/api-evangelist/reducto/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=reducto-api-evangelist&utm_content=repo

## Tags

- Document Parsing
- PDF
- OCR
- Data Extraction
- AI
- Machine Learning
- Document Intelligence
- Structured Data

## APIs

### Reducto Document API

The Reducto Document API provides endpoints for parsing documents into structured JSON, extracting schema-defined fields, splitting multi-document files into labeled sections, classifying documents by type, editing fillable forms with natural language, and composing reusable processing pipelines. Both synchronous and asynchronous variants are available.

- Documentation: https://docs.reducto.ai/
- Base URL: https://api.reductoai.com
- OpenAPI: https://api.reductoai.com/openapi.json
- Python SDK: https://github.com/reductoai/reducto-python-sdk
- Node.js SDK: https://github.com/reductoai/reducto-node-sdk
- Go SDK: https://github.com/reductoai/reducto-go-sdk

## Plans / Rate Limits / FinOps

- Plans and Pricing: [plans/reducto-plans-pricing.yml](plans/reducto-plans-pricing.yml)
- Rate Limits: [rate-limits/reducto-rate-limits.yml](rate-limits/reducto-rate-limits.yml)
- FinOps: [finops/reducto-finops.yml](finops/reducto-finops.yml)

Reducto uses a credit-based billing model. The Standard plan includes 15,000 free credits then $0.015/credit (~$0.015/page). The Growth plan offers volume discounts with 10 req/s throughput. The Enterprise plan supports 100+ req/s with VPC/on-premises options.

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://reducto.ai/ |
| Documentation | https://docs.reducto.ai/ |
| GitHub Organization | https://github.com/reductoai |
| LinkedIn | https://www.linkedin.com/company/reducto-ai/ |
| X (Twitter) | https://x.com/reductoai |
| Blog | https://reducto.ai/blog |
| Pricing | https://reducto.ai/pricing |
| Status Page | https://status.reducto.ai/ |
| Changelog | https://docs.reducto.ai/onprem/changelog |
| Studio | https://studio.reducto.ai/ |
| MCP Server | https://github.com/reductoai/mcp-server-reducto |

## Maintainers

- Kin Lane / kin@apievangelist.com
