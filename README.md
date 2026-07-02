# Transparency (transparency)
An index and topic collection covering public-facing transparency surfaces across the API and platform ecosystem. Transparency in this context refers to the mechanisms platforms use to publicly disclose operational state, government and legal requests, content moderation decisions, security incidents, certificate issuance, and software supply-chain artifacts. This collection brings together transparency reports from major platforms (Google, Cloudflare, Microsoft, Meta, Apple, Reddit, GitHub, Twitter/X, LinkedIn), public status page platforms (Statuspage, Better Stack, Atlassian Statuspage), public audit log surfaces (Cloudflare Audit, AWS CloudTrail-adjacent services, Datadog Audit, Microsoft Purview), cryptographic transparency logs and ledgers (Sigstore Rekor, Certificate Transparency, Let's Encrypt CT, Trillian), and data-broker / FOIA disclosure portals (FOIA, Free Law Project, Disclosure Requirements). It is distinct from the Privacy topic, which focuses on consent and data-subject access requests.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - Transparency, Status Page, Audit Log, Certificate Transparency, Public Disclosure, Transparency Report, Incident Communication, Transparency Log

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Transparency Report Schema](https://raw.githubusercontent.com/api-evangelist/transparency/refs/heads/main/json-schema/transparency-transparency-report-schema.json)
- [JSONSchema - Audit Log Entry Schema](https://raw.githubusercontent.com/api-evangelist/transparency/refs/heads/main/json-schema/transparency-audit-log-entry-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/transparency/refs/heads/main/json-ld/transparency-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/transparency/refs/heads/main/vocabulary/transparency-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Public Transparency Reports | Periodic public reports from platforms like Google, Cloudflare, Microsoft, Meta, Apple, Reddit, GitHub, and Twitter/X disclosing government and legal requests, takedowns, and content moderation actions. |
| Public Status Pages | Hosted status page surfaces (Statuspage, Better Stack, Atlassian Statuspage, Incident.io) communicating real-time service health, incidents, and scheduled maintenance to customers and the public. |
| Public Audit Logs | Audit log APIs and services (Cloudflare Audit Logs, Datadog Audit Trail, Microsoft Purview, Google Cloud Logging) that record administrative and security-relevant events in tamper-evident form. |
| Cryptographic Transparency Logs | Append-only, cryptographically verifiable logs such as Certificate Transparency, Sigstore Rekor, and Trillian that make issuance and signing events publicly auditable. |
| Incident Communication | Structured public disclosure of incidents, post-mortems, RCA, and ongoing impact via status pages, RSS, webhooks, and subscriber notifications. |
| Government and Legal Request Disclosure | Standardized reporting of government data requests, court orders, copyright takedowns, and national security requests across major platforms. |
| Data-Broker and FOIA Disclosure | Public disclosure portals for data brokers and government records, including Freedom of Information Act request handling and judicial disclosure. |

## Use Cases

| Name | Description |
|------|-------------|
| Subscribe to Status Page Incidents | Programmatically subscribe to status page updates from providers like Statuspage, Better Stack, and Atlassian Statuspage and pipe them into incident response systems. |
| Stream Public Audit Logs into a SIEM | Pull tamper-evident audit logs from Cloudflare, Datadog, Microsoft Purview, and Google Cloud Logging into a centralized security information and event management platform. |
| Verify Software Artifacts in a Transparency Log | Query Sigstore Rekor or Certificate Transparency logs to verify that a signed artifact, certificate, or release was publicly recorded and is auditable. |
| Monitor Certificate Issuance for a Domain | Watch Certificate Transparency feeds (including Let's Encrypt CT submissions) for unauthorized or unexpected certificate issuance against owned domains. |
| Aggregate Platform Transparency Reports | Normalize and compare government request disclosures from Google, Cloudflare, Microsoft, Meta, Apple, Reddit, and Twitter/X for research and journalism. |
| Publish Post-Incident Communication | Use status page APIs to publish incidents, ongoing updates, post-mortems, and historical reliability metrics to customers and regulators. |
| FOIA and Public Records Workflows | Submit, track, and publish responses to Freedom of Information Act and judicial disclosure requests via public records APIs. |

## Integrations

| Name | Description |
|------|-------------|
| Statuspage | Atlassian-owned hosted status page and incident communication platform with a REST API for pages, components, incidents, and subscribers. |
| Better Stack | Uptime monitoring and hosted status page platform with API access to monitors, heartbeats, incidents, and status pages. |
| Sigstore Rekor | Cryptographically secure, immutable transparency log for signed software releases, queryable via the Rekor API. |
| Cloudflare | Public Cloudflare Radar, transparency reports, and Audit Logs API providing visibility into traffic, requests, and tenant administrative activity. |
| Google Cloud Logging | Centralized audit and platform logging for Google Cloud, including Admin Activity and Data Access audit logs. |
| Microsoft Purview | Microsoft data governance and compliance platform that exposes audit logs across Microsoft 365 and Azure surfaces. |
| Datadog | Observability platform offering an Audit Trail and Audit Logs API for monitoring administrative activity across Datadog tenants. |
| PagerDuty | Incident response platform with public-facing status pages, post-mortems, and an API for incident disclosure and timelines. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Transparency Report Schema](json-schema/transparency-transparency-report-schema.json)
- [Audit Log Entry Schema](json-schema/transparency-audit-log-entry-schema.json)

### JSON Structure

- [Transparency Report Structure](json-structure/transparency-transparency-report-structure.json)
- [Audit Log Entry Structure](json-structure/transparency-audit-log-entry-structure.json)

### JSON-LD

- [Transparency Context](json-ld/transparency-context.jsonld)

## Vocabulary

- [Transparency Vocabulary](vocabulary/transparency-vocabulary.yaml) — Unified taxonomy covering transparency reports, status pages, audit logs, and cryptographic transparency logs across 5 resources, 7 actions, 4 workflows, and 4 personas

## Network

This index references the following transparency, status page, audit log, and disclosure repositories:

- [Apple Pay](https://github.com/api-evangelist/apple-pay)
- [Atlassian](https://github.com/api-evangelist/atlassian)
- [Better Stack](https://github.com/api-evangelist/better-stack)
- [Cloudflare](https://github.com/api-evangelist/cloudflare)
- [Datadog](https://github.com/api-evangelist/datadog)
- [Disclosure Requirements](https://github.com/api-evangelist/disclosure-requirements)
- [FireHydrant](https://github.com/api-evangelist/firehydrant)
- [Free Law Project](https://github.com/api-evangelist/free-law-project)
- [Freedom of Information Act](https://github.com/api-evangelist/freedom-of-information-act)
- [GitHub Enterprise](https://github.com/api-evangelist/github-enterprise)
- [Google Cloud](https://github.com/api-evangelist/google-cloud)
- [Google Cloud Logging](https://github.com/api-evangelist/google-cloud-logging)
- [Google Cloud Security Command Center](https://github.com/api-evangelist/google-cloud-security-command-center)
- [Honeybadger](https://github.com/api-evangelist/honeybadger)
- [Incident.io](https://github.com/api-evangelist/incident-io)
- [Let's Encrypt](https://github.com/api-evangelist/lets-encrypt)
- [LinkedIn](https://github.com/api-evangelist/linkedin)
- [Meta Platforms](https://github.com/api-evangelist/meta-platforms)
- [Microsoft Azure](https://github.com/api-evangelist/microsoft-azure)
- [Microsoft Purview](https://github.com/api-evangelist/microsoft-purview)
- [PagerDuty](https://github.com/api-evangelist/pagerduty)
- [Reddit](https://github.com/api-evangelist/reddit)
- [Sigstore](https://github.com/api-evangelist/sigstore)
- [Squadcast](https://github.com/api-evangelist/squadcast)
- [Statuspage](https://github.com/api-evangelist/statuspage)
- [Twitter](https://github.com/api-evangelist/twitter)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
