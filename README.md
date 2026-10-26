# Pangea (pangea)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Pangea delivers security as a set of composable, API-first services - authentication (AuthN/AuthZ), tamper-proof Secure Audit Log, Redact, Vault, File Scan, URL/Domain/IP Intel, Embargo, Sanitize, and AI Guard / Prompt Guard - that developers call over REST with a Bearer service token to add security guardrails to applications and AI workloads.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pangea/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pangea/refs/heads/main/apis.yml)

## Tags

- Security
- AI Security
- Authentication
- Audit Log
- Data Protection

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Pangea AuthN API

Hosted user authentication and identity - sign-up/sign-in flows, user lifecycle, session and client-token management, and JWKS - exposed as REST and secured with a Bearer service token.

- **Human URL:** [https://pangea.cloud/docs/api/authn](https://pangea.cloud/docs/api/authn)
- **Base URL:** `https://authn.aws.us.pangea.cloud`

#### Tags

- Authentication
- Identity
- Sessions

#### Properties

- [Documentation](https://pangea.cloud/docs/authn)
- [API Reference](https://pangea.cloud/docs/api/authn)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pangea Secure Audit Log API

Tamper-proof, cryptographically verifiable audit logging with Merkle-tree membership and consistency proofs, log entry creation, search, results paging, and export.

- **Human URL:** [https://pangea.cloud/docs/api/audit](https://pangea.cloud/docs/api/audit)
- **Base URL:** `https://audit.aws.us.pangea.cloud`

#### Tags

- Audit Log
- Tamper Proof
- Compliance

#### Properties

- [Documentation](https://pangea.cloud/docs/audit)
- [API Reference](https://pangea.cloud/docs/api/audit)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pangea Redact API

Detect and remove sensitive information (PII, secrets) from text and structured data using configurable rulesets, with format-preserving encryption and unredact support.

- **Human URL:** [https://pangea.cloud/docs/api/redact](https://pangea.cloud/docs/api/redact)
- **Base URL:** `https://redact.aws.us.pangea.cloud`

#### Tags

- Redaction
- PII
- Data Protection

#### Properties

- [Documentation](https://pangea.cloud/docs/redact)
- [API Reference](https://pangea.cloud/docs/api/redact)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pangea Vault API

Secure storage and lifecycle management for secrets and cryptographic keys with encrypt/decrypt, sign/verify, rotation, and JWT/JWK operations.

- **Human URL:** [https://pangea.cloud/docs/api/vault](https://pangea.cloud/docs/api/vault)
- **Base URL:** `https://vault.aws.us.pangea.cloud`

#### Tags

- Secrets
- Key Management
- Encryption

#### Properties

- [Documentation](https://pangea.cloud/docs/vault)
- [API Reference](https://pangea.cloud/docs/api/vault)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pangea File Scan API

Scan uploaded files (PE, Mach-O, ELF, Office, PDF, ZIP) for malicious content using configured threat-detection providers, returning a verdict, score, and category.

- **Human URL:** [https://pangea.cloud/docs/api/file-scan](https://pangea.cloud/docs/api/file-scan)
- **Base URL:** `https://file-scan.aws.us.pangea.cloud`

#### Tags

- File Scan
- Malware
- Threat Detection

#### Properties

- [Documentation](https://pangea.cloud/docs/file-scan)
- [API Reference](https://pangea.cloud/docs/api/file-scan)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pangea IP Intel API

IP address threat intelligence - reputation scoring, geolocation, and VPN/proxy/domain enrichment - drawn from multiple providers and normalized to a Pangea verdict and score.

- **Human URL:** [https://pangea.cloud/docs/api/ip-intel](https://pangea.cloud/docs/api/ip-intel)
- **Base URL:** `https://ip-intel.aws.us.pangea.cloud`

#### Tags

- Threat Intel
- IP Reputation
- Geolocation

#### Properties

- [Documentation](https://pangea.cloud/docs/ip-intel)
- [API Reference](https://pangea.cloud/docs/api/ip-intel)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pangea Domain & URL Intel API

Reputation lookups for domains and URLs against threat-intelligence providers, returning normalized verdicts, scores, and categories to flag malicious indicators.

- **Human URL:** [https://pangea.cloud/docs/api/domain-intel](https://pangea.cloud/docs/api/domain-intel)
- **Base URL:** `https://domain-intel.aws.us.pangea.cloud`

#### Tags

- Threat Intel
- Domain Reputation
- URL Reputation

#### Properties

- [Documentation](https://pangea.cloud/docs/domain-intel)
- [API Reference](https://pangea.cloud/docs/api/domain-intel)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pangea AI Guard & Prompt Guard API

Detect, redact, or block malicious content and intent in LLM inputs and outputs - prompt injection, PII, secrets, and malicious entities - via configurable recipes to guard AI applications.

- **Human URL:** [https://pangea.cloud/docs/api/ai-guard](https://pangea.cloud/docs/api/ai-guard)
- **Base URL:** `https://ai-guard.aws.us.pangea.cloud`

#### Tags

- AI Security
- Prompt Injection
- LLM Guardrails

#### Properties

- [Documentation](https://pangea.cloud/docs/ai-guard)
- [API Reference](https://pangea.cloud/docs/api/ai-guard)
- [OpenAPI](openapi/pangea-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pangea.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pangea.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/pangeacyber)
- [LinkedIn](https://www.linkedin.com/company/pangeacyber)
- [Website](https://pangea.cloud/)
- [Documentation](https://pangea.cloud/docs/)
- [Plans](plans/pangea-plans-pricing.yml)
- [Rate Limits](rate-limits/pangea-rate-limits.yml)
- [Fin Ops](finops/pangea-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
