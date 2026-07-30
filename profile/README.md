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

Heyrafiki connects People, licensed Practitioners, Insurers and Organizations on one rail. A Person finds a right-fit Practitioner and uses the Cover they already have. The Practitioner gets practice tools and a clear path to payment. The Insurer receives a clean, coded Claim from a verified network.

## Start here

| For | Start |
| --- | --- |
| **Developers and agents** | [Build with the Heyrafiki API](https://docs.heyrafiki.space) |
| **Practitioners** | [Run your Practice](https://heyrafiki.space/solutions/practitioners) |
| **Insurers** | [Connect Cover to Care](https://heyrafiki.space/solutions/insurers) |
| **Organizations** | [Offer private Mental Health Benefits](https://heyrafiki.space/solutions/organizations) |
| **NGOs and public health** | [Run accountable Care Programs](https://heyrafiki.space/solutions/ngos) |
| **Researchers** | [Read our research approach](https://heyrafiki.space/resources/research) |

## Architecture

| Decision | Why |
| --- | --- |
| **One authority per domain** | Realtime state and durable records have one owner each. Copies are event-driven projections, never uncontrolled dual writes. |
| **The Ledger is the source of truth** | Payment providers move money; a double-entry Ledger records it. Every movement has a matching pair. |
| **Identity stored apart from clinical data** | Access requires role, purpose and Consent together. Any one failing denies the request. |
| **Versioned contracts at the boundary** | OpenAPI, JSON Schema and signed Events keep released interfaces explicit and testable. |
| **Portable by construction** | Standard interfaces keep the Platform independent of one cloud or vendor. |

## Open source

We publish code where independent inspection improves interoperability and trust: contracts, SDKs, standards adapters, documentation and public-safe evaluation tools. Each repository opens with a useful artifact, an explicit licence and maintained release controls.

Safety thresholds, anti-fraud controls, private regulator and payer adapters, production credentials and production data stay private. Read the [open source thesis](https://heyrafiki.space/open-source).

## Build with Heyrafiki

Start with the [Docs](https://docs.heyrafiki.space), follow released behavior in the [Changelog](https://heyrafiki.space/changelog), or [request sandbox access](https://heyrafiki.space/waitlist).

Issues and pull requests are welcome in public repositories. Start with [`CONTRIBUTING.md`](https://github.com/heyrafiki/.github/blob/main/CONTRIBUTING.md).

Report security issues through [`SECURITY.md`](https://github.com/heyrafiki/.github/blob/main/SECURITY.md), never a public issue.

<p align="center">
  <sub><a href="https://heyrafiki.space">heyrafiki.space</a> · <a href="mailto:hello@heyrafiki.space">hello@heyrafiki.space</a></sub>
</p>
