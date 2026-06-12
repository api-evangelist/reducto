# Reducto (reducto)

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
