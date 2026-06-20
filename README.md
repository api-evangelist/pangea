# Pangea (pangea)

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
