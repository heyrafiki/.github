<p align="center">
  <a href="https://heyrafiki.space">
    <img src="https://heyrafiki.space/opengraph-image.png" alt="Heyrafiki" width="420">
  </a>
</p>

# Building the Intelligence and Infrastructure for Continuous Mental Healthcare

**Built in Kenya, for the World.**

Mental Healthcare should get better informed over time. Heyrafiki brings early
Screening, finding care, ongoing Care, Benefits and Claims into one connected
system, so a Person does not have to start from zero whenever care changes hands.

People decide what they share. Practitioners decide what it means. Organizations
and Insurers act only within the permissions and responsibilities assigned to them.

[Website](https://heyrafiki.space) ·
[Docs](https://docs.heyrafiki.space) ·
[Lab](https://heyrafiki.space/resources/lab) ·
[Open Source](https://heyrafiki.space/open-source) ·
[Vision](https://heyrafiki.space/vision)

## The system

| Foundation | What it makes possible |
| --- | --- |
| **Continuity** | The context a Person agrees to share can move from one point of Care to the next. |
| **Intelligence** | Repeated check-ins help a Practitioner see what changed and decide what needs attention. |
| **Infrastructure** | Care, Benefits, Claims and Payments can work together while each keeps its own responsibilities. |

## Public work

| Repository | What it is |
| --- | --- |
| [contract](https://github.com/heyrafiki/contract) | The versioned public API contract. |
| [proving-ground](https://github.com/heyrafiki/proving-ground) | Open tests that show what the system supports and where it must stop. |
| [docs](https://github.com/heyrafiki/docs) | Guides for the API, SDKs, Webhooks and MCP access. |
| [rafiki-js](https://github.com/heyrafiki/rafiki-js) | JavaScript and TypeScript client for the Heyrafiki API. |
| [rafiki-py](https://github.com/heyrafiki/rafiki-py) | Python client for the Heyrafiki API. |
| [rafiki-go](https://github.com/heyrafiki/rafiki-go) | Go client for the Heyrafiki API. |
| [rafiki-net](https://github.com/heyrafiki/rafiki-net) | .NET client for the Heyrafiki API. |
| [rafiki-rs](https://github.com/heyrafiki/rafiki-rs) | Rust client for the Heyrafiki API. |
| [hey](https://github.com/heyrafiki/hey) | Command-line tools for safe Sandbox testing. |

## Trust should be testable

[Proving Ground](https://github.com/heyrafiki/proving-ground) publishes test
suites that anyone can run against our public contracts. They cover consent and
access, payment and Claim records, early-Screening provenance, and the cases in
which the system must decline to act.

[First Light](https://github.com/heyrafiki/proving-ground/tree/main/benchmarks/first-light)
keeps the questionnaire, version, language, timing, Consent and source with an
early-Screening result. That gives a Practitioner the context to understand a
result before relying on it.

[Iris Affective Dynamics](https://github.com/heyrafiki/proving-ground/tree/main/research/affective-dynamics)
investigates whether repeated observations can help Practitioners notice
deterioration, persistence and recovery sooner. Its comparators, failure
criteria and evidence boundaries are published before clinical use.

## People stay in control

- People decide what to share.
- Practitioners make clinical decisions.
- Consent determines access.
- Insurers make Claim decisions under their own rules.
- AI can help people make sense of information. It does not make clinical,
  Benefit or Claim decisions.

## Access and openness

Our public work includes the API definition, SDKs, command-line tools,
documentation and test suites. For agent integrations, MCP access starts in
approved Sandbox projects with clear scopes and an audit trail.

Open source has a clear boundary. Production data, credentials, safety systems,
and private regulatory or insurer integrations remain private. Read the
[open source boundary](https://heyrafiki.space/open-source).

## Contributing and security

Start with [CONTRIBUTING.md](https://github.com/heyrafiki/.github/blob/main/CONTRIBUTING.md).
Report vulnerabilities through [SECURITY.md](https://github.com/heyrafiki/.github/blob/main/SECURITY.md),
never a public issue.
