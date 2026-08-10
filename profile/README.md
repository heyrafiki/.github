<p align="center">
  <a href="https://heyrafiki.space">
    <img src="https://heyrafiki.space/opengraph-image.png" alt="Heyrafiki" width="420">
  </a>
</p>

<h3 align="center">Mental Healthcare infrastructure.</h3>

<p align="center">
  One rail for Care, Cover and Payments. Built in Nairobi, for Africa and the next billion People.
</p>

<p align="center">
  <a href="https://heyrafiki.space"><b>Website</b></a> ·
  <a href="https://docs.heyrafiki.space"><b>Docs</b></a> ·
  <a href="https://heyrafiki.space/changelog"><b>Changelog</b></a> ·
  <a href="https://heyrafiki.space/vision"><b>Vision</b></a> ·
  <a href="https://heyrafiki.space/open-source"><b>Open source</b></a>
</p>

---

Heyrafiki connects People, Practitioners, Insurers and Organizations across Care, Benefits and Payments. Developers can build against versioned REST contracts, the JavaScript SDK and CLI, and public documentation.

## Public projects

| Repository | Purpose | Licence |
| --- | --- | --- |
| [`docs`](https://github.com/heyrafiki/docs) | Developer documentation for the API, SDKs, Webhooks and MCP. [Read the Docs](https://docs.heyrafiki.space). | [CC BY 4.0](https://github.com/heyrafiki/docs/blob/main/LICENSE) |
| [`openapi`](https://github.com/heyrafiki/openapi) | OpenAPI 3.1 contract for the REST API. | [Apache 2.0](https://github.com/heyrafiki/openapi/blob/main/LICENSE) |
| [`heyrafiki-js`](https://github.com/heyrafiki/heyrafiki-js) | JavaScript and TypeScript SDK, plus the Heyrafiki CLI. | [Apache 2.0](https://github.com/heyrafiki/heyrafiki-js/blob/main/LICENSE) |
| [`heyrafiki-python`](https://github.com/heyrafiki/heyrafiki-python) | Python SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/heyrafiki-python/blob/main/LICENSE) |
| [`heyrafiki-go`](https://github.com/heyrafiki/heyrafiki-go) | Go SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/heyrafiki-go/blob/main/LICENSE) |
| [`heyrafiki-dotnet`](https://github.com/heyrafiki/heyrafiki-dotnet) | .NET SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/heyrafiki-dotnet/blob/main/LICENSE) |
| [`heyrafiki-rust`](https://github.com/heyrafiki/heyrafiki-rust) | Rust SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/heyrafiki-rust/blob/main/LICENSE) |

## Access

The documentation, API contract, assurance benchmark and SDK source are public. Organizations with Sandbox access can create a key in the [Developer Platform](https://app.heyrafiki.space/dev/keys). [Request access](https://heyrafiki.space/waitlist).

## For insurers and institutions

Integration teams can review the contract and control model before requesting access:

| Review surface | What it proves |
| --- | --- |
| [Insurance integration guide](https://docs.heyrafiki.space/insurance/integration-guide) | Coverage, eligibility, pre-authorization, Claims and remittance workflow ownership |
| [Financial controls](https://docs.heyrafiki.space/insurance/financial-controls) | Integer money, Claim line identities, decision derivation and settlement separation |
| [Claim valuation timeline](https://docs.heyrafiki.space/insurance/claim-valuation-timeline) | Reproducible as-of Claim history across business time, knowledge time and valuation time |
| [Assurance Graph](https://docs.heyrafiki.space/institutions/assurance-graph) | Every public operation linked to an accountable capability, control owner, authority source and executable evidence |
| [Acceptance testing](https://docs.heyrafiki.space/insurance/acceptance-testing) | Synthetic pilot sequence, negative tests and production approval evidence |
| [OpenAPI contract](https://github.com/heyrafiki/openapi) | Versioned schemas, scopes, errors, idempotency and executable contract checks |
| [Security policy](https://github.com/heyrafiki/.github/blob/main/SECURITY.md) | Private vulnerability reporting and health-data handling rules |

The payer remains authoritative for membership, Benefit design, adjudication policy, premium, reserving and regulatory returns. Heyrafiki preserves the operational evidence connecting payer decisions to delivered Care, Claims and settlement.

## Open insurance assurance benchmark

The [Open Mental Health Insurance Assurance Benchmark](https://github.com/heyrafiki/openapi/blob/main/BENCHMARK.md) maps all 30 public API operations to 10 accountable capabilities and 9 controls. Its deterministic runner validates the contract, financial identities, a bitemporal Claim valuation timeline and graph integrity. Five adversarial mutations test duplicate events, reordered knowledge, future knowledge, unbalanced adjudication and settlement above payer liability.

```bash
git clone https://github.com/heyrafiki/openapi.git
cd openapi
npm ci
npm test
```

The fixture is synthetic. It establishes reproducible contract behavior, not regulatory approval, clinical efficacy, reserve adequacy or insurer solvency. [Read the research article](https://heyrafiki.space/resources/articles/what-did-the-claim-system-know) or [inspect the machine-readable Assurance Graph](https://github.com/heyrafiki/openapi/blob/main/assurance/assurance-graph.json).

## Open source

We publish contracts, SDKs and documentation where independent inspection improves interoperability and trust. Each public artifact has its own licence.

Safety thresholds, anti-fraud controls, private regulator and payer adapters, production credentials and production data stay private. Read the [open source thesis](https://heyrafiki.space/open-source).

## Contributing

Issues and pull requests are welcome in public repositories. Start with [`CONTRIBUTING.md`](https://github.com/heyrafiki/.github/blob/main/CONTRIBUTING.md).

Report security issues through [`SECURITY.md`](https://github.com/heyrafiki/.github/blob/main/SECURITY.md), never a public issue.

<p align="center">
  <sub><a href="https://heyrafiki.space">heyrafiki.space</a> · <a href="mailto:hello@heyrafiki.space">hello@heyrafiki.space</a></sub>
</p>
