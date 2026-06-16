# SCALA Score API — OpenAPI Specification

OpenAPI 3.1 specification for the SCALA Score API — search and enrich company data from 250M+ business records.

## Quick start

```bash
# Search companies
curl "https://score.get-scala.com/api/search?q=Ferrero&country=IT"

# Look up by VAT
curl "https://score.get-scala.com/api/lookup?id=IT02727330014"
```

No API key needed. Free tier: 50 lookups/month.

## Import

- **Postman**: Import `openapi.yaml` → ready-to-use collection
- **Swagger UI**: Load `openapi.yaml` in any Swagger UI instance
- **Code generation**: Use `openapi-generator` to create client SDKs in any language

## Available SDKs & tools

| Tool | Install | Link |
|------|---------|------|
| Python SDK | `pip install scala-score` | [PyPI](https://pypi.org/project/scala-score/) |
| CSV enrichment (Node) | `npx enrich-companies input.csv` | [npm](https://www.npmjs.com/package/enrich-companies) |
| CSV enrichment (Python) | `pip install enrich-companies` | [PyPI](https://pypi.org/project/enrich-companies/) |
| Terminal lookup | `npx company-lookup Ferrero` | [npm](https://www.npmjs.com/package/company-lookup) |
| MCP Server | `npx scala-mcp-server` | [npm](https://www.npmjs.com/package/scala-mcp-server) |
| Chrome Extension | Install from store | [Chrome Web Store](https://chromewebstore.google.com/detail/score-company-lookup/) |
| GitHub Action | See action.yml | [GitHub](https://github.com/Alessandro114/enrich-companies-action) |
| Bulk dataset | Download CSV | [Kaggle](https://www.kaggle.com/datasets/yorkiealfbroth/global-company-data-994k) |

## Data coverage

250M+ companies across 50+ countries. Sources: official government business registries.

## License

MIT
