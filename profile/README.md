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
  <a href="https://heyrafiki.space/open-source"><b>Open source</b></a> ·
  <a href="https://heyrafiki.space/resources/lab"><b>Lab</b></a>
</p>

---

Heyrafiki connects People, Practitioners, Insurers and Organizations across Care, Benefits and Payments. Developers build against a versioned REST API definition, typed SDKs, the `hey` command line and public documentation.

## Public projects

| Repository | Purpose | Licence |
| --- | --- | --- |
| [`docs`](https://github.com/heyrafiki/docs) | Developer documentation for the API, SDKs, Webhooks and MCP. [Read the Docs](https://docs.heyrafiki.space). | [CC BY 4.0](https://github.com/heyrafiki/docs/blob/main/LICENSE) |
| [`contract`](https://github.com/heyrafiki/contract) | OpenAPI 3.1 definition and machine-readable Assurance Graph. | [Apache 2.0](https://github.com/heyrafiki/contract/blob/main/LICENSE) |
| [`proving-ground`](https://github.com/heyrafiki/proving-ground) | Executable conformance evidence, First Light fixtures and reviewed research protocols. | [Apache 2.0](https://github.com/heyrafiki/proving-ground/blob/main/LICENSE) |
| [`rafiki-js`](https://github.com/heyrafiki/rafiki-js) | JavaScript and TypeScript SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/rafiki-js/blob/main/LICENSE) |
| [`rafiki-py`](https://github.com/heyrafiki/rafiki-py) | Python SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/rafiki-py/blob/main/LICENSE) |
| [`rafiki-go`](https://github.com/heyrafiki/rafiki-go) | Go SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/rafiki-go/blob/main/LICENSE) |
| [`rafiki-net`](https://github.com/heyrafiki/rafiki-net) | .NET SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/rafiki-net/blob/main/LICENSE) |
| [`rafiki-rs`](https://github.com/heyrafiki/rafiki-rs) | Rust SDK for the Heyrafiki API. | [Apache 2.0](https://github.com/heyrafiki/rafiki-rs/blob/main/LICENSE) |
| [`hey`](https://github.com/heyrafiki/hey) | Command line for Sandbox diagnostics and governed API reads. | [Apache 2.0](https://github.com/heyrafiki/hey/blob/main/LICENSE) |

## Install a public beta

| Language | Install |
| --- | --- |
| JavaScript | `npm install @heyrafiki/rafiki-js@0.1.0-beta.1` |
| Python | `python -m pip install --pre heyrafiki==0.1.0b1` |
| Go | `go get github.com/heyrafiki/rafiki-go@v0.1.0-beta.1` |
| .NET | `dotnet add package heyrafiki --version 0.1.0-beta.1` |
| Rust | `cargo add heyrafiki@0.1.0-beta.1` |

See the [SDK guide](https://docs.heyrafiki.space/sdks) for registry links,
source builds and first-request examples.

## Access

The documentation, API definition, assurance benchmark and SDK source are public. Organizations with Sandbox access can create a key in the [Developer Platform](https://app.heyrafiki.space/dev/keys). [Request access](https://heyrafiki.space/waitlist).

## For insurers and institutions

Integration teams can review the API definition and control model before requesting access:

| Review surface | What it proves |
| --- | --- |
| [Insurance integration guide](https://docs.heyrafiki.space/insurance/integration-guide) | Coverage, eligibility, pre-authorization, Claims and remittance workflow ownership |
| [Financial controls](https://docs.heyrafiki.space/insurance/financial-controls) | Integer money, Claim line identities, decision derivation and settlement separation |
| [Claim valuation timeline](https://docs.heyrafiki.space/insurance/claim-valuation-timeline) | Reproducible as-of Claim history across business time, knowledge time and valuation time |
| [Assurance Graph](https://docs.heyrafiki.space/institutions/assurance-graph) | Every public operation linked to an accountable capability, control owner, authority source and executable evidence |
| [Acceptance testing](https://docs.heyrafiki.space/insurance/acceptance-testing) | Synthetic pilot sequence, negative tests and production approval evidence |
| [OpenAPI definition](https://github.com/heyrafiki/contract) | Versioned schemas, scopes, errors, idempotency and accountable capability ownership |
| [API overview](https://docs.heyrafiki.space/resources) | All 31 released operations grouped by Care, Benefits, Claims, remittance and Webhook resources |
| [Proving Ground](https://github.com/heyrafiki/proving-ground) | Reproducible conformance suites and pinned evidence artifacts |
| [First Light Evidence Pack](https://github.com/heyrafiki/proving-ground/blob/main/benchmarks/first-light/v2/pilot-evidence-pack.md) | Consent-authorized early-identification routing, tenant isolation, blind dual review, longitudinal knowledge time and adverse-boundary evidence |
| [Security policy](https://github.com/heyrafiki/.github/blob/main/SECURITY.md) | Private vulnerability reporting and health-data handling rules |

The payer remains authoritative for membership, Benefit design, adjudication policy, premium, reserving and regulatory returns. Heyrafiki preserves the operational evidence connecting payer decisions to delivered Care, Claims and settlement.

## Open insurance assurance benchmark

The [Open Mental Health Insurance Assurance Benchmark](https://github.com/heyrafiki/proving-ground) connects each public API operation to its accountable capability, control owner and executable evidence. Its runner validates the API definition, financial identities, a bitemporal Claim valuation timeline and committed cases that must fail.

```bash
git clone https://github.com/heyrafiki/proving-ground.git
cd proving-ground
npm ci
npm test
```

The open benchmark is the shared technical baseline for governed institutional pilots. Teams extend it with their operating assumptions, approved evidence and accountable reviewers while preserving the same reproducible method. [Call the Claim valuation operation](https://docs.heyrafiki.space/insurance/claim-valuation-timeline), [read the research article](https://heyrafiki.space/resources/articles/what-did-the-claim-system-know) or [inspect the machine-readable Assurance Graph](https://github.com/heyrafiki/contract/blob/main/assurance/assurance-graph.json).

## First Light conformance evidence

First Light carries Screening signals into an accountable Practitioner review boundary. Its [public evidence pack](https://github.com/heyrafiki/proving-ground/blob/main/benchmarks/first-light/v2/pilot-evidence-pack.md) reproduces versioned fixtures across self, caregiver and Practitioner responder paths. The suite verifies Consent before read or action, tenant isolation, minimum-necessary model context, blind dual review, effective and recorded time, complete audit evidence and adverse boundaries.

Every artifact is pinned in a [reviewed SHA-256 manifest](https://github.com/heyrafiki/proving-ground/blob/main/benchmarks/first-light/v2/manifest.json). The [Evidence Boundary](https://github.com/heyrafiki/proving-ground/blob/main/benchmarks/first-light/v2/evidence-boundary.md) keeps fixed-cohort conformance measurement precise while instrument- and population-specific clinical evaluation carries its own reviewed protocol.

## Research and public tools

The [Heyrafiki Lab](https://heyrafiki.space/resources/lab) collects browser-based
tools that use example data and state their limits beside the result.

The [Affective Dynamics protocol](https://github.com/heyrafiki/proving-ground/tree/main/research/affective-dynamics)
defines standard comparators, synthetic edge cases, failure criteria and an
independent reviewer checklist for person-relative longitudinal context.

The Assurance Graph research package includes its comparative
[protocol](https://github.com/heyrafiki/proving-ground/blob/main/research/consent-aware-bitemporal-assurance-graph/protocol.md),
[manuscript](https://github.com/heyrafiki/proving-ground/blob/main/research/consent-aware-bitemporal-assurance-graph/manuscript.md),
[prior-art search](https://github.com/heyrafiki/proving-ground/blob/main/research/consent-aware-bitemporal-assurance-graph/prior-art-search.md)
and [independent reviewer checklist](https://github.com/heyrafiki/proving-ground/blob/main/research/consent-aware-bitemporal-assurance-graph/reviewer-checklist.md).

## Open source

We publish API definitions, SDKs and documentation where independent inspection improves interoperability and trust. Each public artifact has its own licence.

Safety thresholds, anti-fraud controls, private regulator and payer adapters, production credentials and production data stay private. Read the [open source thesis](https://heyrafiki.space/open-source).

## Contributing

Issues and pull requests are welcome in public repositories. Start with [`CONTRIBUTING.md`](https://github.com/heyrafiki/.github/blob/main/CONTRIBUTING.md).

Heyrafiki follows a BDFL governance model under Founder Daniel Moenga. Read [`GOVERNANCE.md`](https://github.com/heyrafiki/.github/blob/main/GOVERNANCE.md) for how project decisions and maintainer responsibilities work.

Report security issues through [`SECURITY.md`](https://github.com/heyrafiki/.github/blob/main/SECURITY.md), never a public issue.

<p align="center">
  <sub><a href="https://heyrafiki.space">heyrafiki.space</a> · <a href="mailto:hello@heyrafiki.space">hello@heyrafiki.space</a></sub>
</p>
