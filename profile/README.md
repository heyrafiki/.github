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
  <a href="https://heyrafiki.space/open-source"><b>Open source thesis</b></a>
</p>

---

Heyrafiki connects People, licensed Practitioners, Insurers and Organizations on one rail. A Person finds a right-fit Practitioner and uses the cover they already have. The Practitioner gets practice tools and is paid the moment a Session ends. The Insurer receives a clean, coded Claim from a verified network.

## Architecture

| Decision | Why |
| --- | --- |
| **One authority per domain** | Realtime state and records of authority are separate stores with one owner each. Copies between them are event-driven projections, never uncontrolled dual writes. |
| **The ledger is the source of truth** | Payment providers move money; a double-entry ledger records it. Booking captures into escrow, delivery releases, a covered Session posts a receivable instead. Every movement has a matching pair. |
| **Identity stored apart from clinical data** | A breach of one is not a breach of the other. Access is decided by role, purpose and consent together; any one failing denies the request. |
| **Standards at the boundary** | FHIR resource shapes and ICD-10 coding, so Claims, referrals and records exchange with systems that already exist. |
| **Portable by construction** | No host-locked primitives, so the Platform is not captive to one provider. |

## What is open

The rails, so anyone can inspect them, extend them and hold us to them: client SDKs, adapters for the healthcare standards health systems already run, the API contract, the developer documentation, and the scoring for published screening instruments with a citation for every one.

## What is closed

Safety and triage thresholds, anti-fraud logic, the Practitioner verification pipeline, and integrations bound by a payer contract. Publishing those would arm the people we protect others from. The [full reasoning](https://heyrafiki.space/open-source) is public even though the code is not.

## Status

Pre-launch. The API contract, authentication and error envelope are final and respond today; endpoints open with the Platform. Sandbox keys go to [the waitlist](https://heyrafiki.space/waitlist) first.

## Contributing

Issues and pull requests are welcome on every public repository. Start with `CONTRIBUTING.md`.

Report anything security-related through [`SECURITY.md`](https://github.com/heyrafiki/.github/blob/main/SECURITY.md) rather than a public issue. This code sits near health data.

<p align="center">
  <sub><a href="https://heyrafiki.space">heyrafiki.space</a> · <a href="mailto:hello@heyrafiki.space">hello@heyrafiki.space</a></sub>
</p>
