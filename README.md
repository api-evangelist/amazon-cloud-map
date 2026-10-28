# Amazon Cloud Map

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

Amazon Cloud Map is a cloud resource discovery service that maintains an updated registry of application resources and their locations. Define custom names for application resources and use Cloud Map to dynamically discover service dependencies with integrated health checking and automatic updates.

**Areas:** AWS · Cloud Map · Service Discovery · Microservices · DNS

## Amazon Cloud Map on APIs.io

Everything profiled for Amazon Cloud Map is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/amazon-cloud-map/](https://apis.io/providers/amazon-cloud-map/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Amazon Cloud Map Instances API](https://apis.io/apis/amazon-cloud-map/amazon-cloud-map-instances-api/) — Operations for registering and discovering service instances
- [Amazon Cloud Map Namespaces API](https://apis.io/apis/amazon-cloud-map/amazon-cloud-map-namespaces-api/) — Operations for managing service discovery namespaces
- [Amazon Cloud Map Services API](https://apis.io/apis/amazon-cloud-map/amazon-cloud-map-services-api/) — Operations for managing services within namespaces
- [Amazon Cloud Map Cloud Map Operations API](https://apis.io/apis/amazon-cloud-map/amazon-cloud-map-operations-api/) — The Cloud Map Operations API from Amazon Cloud Map — 14 operation(s) for cloud map operations.
- [Amazon Cloud Map Cloud Map Service Attribute API](https://apis.io/apis/amazon-cloud-map/amazon-cloud-map-service-attribute-api/) — The Cloud Map Service Attribute API from Amazon Cloud Map — 3 operation(s) for cloud map service attribute.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [amazon-cloud-map](https://apis.io/servers/amazon-cloud-map/amazon-cloud-map/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Amazon Cloud Map Agentic Access](https://apis.io/agentic-access/amazon-cloud-map/amazon-cloud-map-agentic-access/)

#### JSON Schema (13)

The data models the API reads and writes.

- [CreateServiceRequest](https://apis.io/schemas/amazon-cloud-map/cloud-map-create-service-request/)
- [CreateServiceResponse](https://apis.io/schemas/amazon-cloud-map/cloud-map-create-service-response/)
- [DiscoverInstancesRequest](https://apis.io/schemas/amazon-cloud-map/cloud-map-discover-instances-request/)
- [DiscoverInstancesResponse](https://apis.io/schemas/amazon-cloud-map/cloud-map-discover-instances-response/)
- [HttpInstanceSummary](https://apis.io/schemas/amazon-cloud-map/cloud-map-http-instance-summary/)
- [Instance](https://apis.io/schemas/amazon-cloud-map/cloud-map-instance/)
- [ListInstancesResponse](https://apis.io/schemas/amazon-cloud-map/cloud-map-list-instances-response/)
- [ListNamespacesResponse](https://apis.io/schemas/amazon-cloud-map/cloud-map-list-namespaces-response/)
- [ListServicesResponse](https://apis.io/schemas/amazon-cloud-map/cloud-map-list-services-response/)
- [Namespace](https://apis.io/schemas/amazon-cloud-map/cloud-map-namespace/)
- [RegisterInstanceRequest](https://apis.io/schemas/amazon-cloud-map/cloud-map-register-instance-request/)
- [RegisterInstanceResponse](https://apis.io/schemas/amazon-cloud-map/cloud-map-register-instance-response/)
- [Service](https://apis.io/schemas/amazon-cloud-map/cloud-map-service/)

#### JSON Structure (13)

Data models expressed in JSON Structure.

- [Cloud Map Create Service Request Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-create-service-request-structure/)
- [Cloud Map Create Service Response Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-create-service-response-structure/)
- [Cloud Map Discover Instances Request Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-discover-instances-request-structure/)
- [Cloud Map Discover Instances Response Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-discover-instances-response-structure/)
- [Cloud Map Http Instance Summary Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-http-instance-summary-structure/)
- [Cloud Map Instance Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-instance-structure/)
- [Cloud Map List Instances Response Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-list-instances-response-structure/)
- [Cloud Map List Namespaces Response Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-list-namespaces-response-structure/)
- [Cloud Map List Services Response Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-list-services-response-structure/)
- [Cloud Map Namespace Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-namespace-structure/)
- [Cloud Map Register Instance Request Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-register-instance-request-structure/)
- [Cloud Map Register Instance Response Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-register-instance-response-structure/)
- [Cloud Map Service Structure](https://apis.io/json-structure/amazon-cloud-map/cloud-map-service-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Amazon Cloud Map Context](https://apis.io/jsonld/amazon-cloud-map/amazon-cloud-map-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Amazon Cloud Map Vocabulary](https://apis.io/vocabularies/amazon-cloud-map/amazon-cloud-map-vocabulary/)

#### Examples (13)

Example requests and responses.

- [Cloud Map Create Service Request Example](https://apis.io/examples/amazon-cloud-map/cloud-map-create-service-request-example/)
- [Cloud Map Create Service Response Example](https://apis.io/examples/amazon-cloud-map/cloud-map-create-service-response-example/)
- [Cloud Map Discover Instances Request Example](https://apis.io/examples/amazon-cloud-map/cloud-map-discover-instances-request-example/)
- [Cloud Map Discover Instances Response Example](https://apis.io/examples/amazon-cloud-map/cloud-map-discover-instances-response-example/)
- [Cloud Map Http Instance Summary Example](https://apis.io/examples/amazon-cloud-map/cloud-map-http-instance-summary-example/)
- [Cloud Map Instance Example](https://apis.io/examples/amazon-cloud-map/cloud-map-instance-example/)
- [Cloud Map List Instances Response Example](https://apis.io/examples/amazon-cloud-map/cloud-map-list-instances-response-example/)
- [Cloud Map List Namespaces Response Example](https://apis.io/examples/amazon-cloud-map/cloud-map-list-namespaces-response-example/)
- [Cloud Map List Services Response Example](https://apis.io/examples/amazon-cloud-map/cloud-map-list-services-response-example/)
- [Cloud Map Namespace Example](https://apis.io/examples/amazon-cloud-map/cloud-map-namespace-example/)
- [Cloud Map Register Instance Request Example](https://apis.io/examples/amazon-cloud-map/cloud-map-register-instance-request-example/)
- [Cloud Map Register Instance Response Example](https://apis.io/examples/amazon-cloud-map/cloud-map-register-instance-response-example/)
- [Cloud Map Service Example](https://apis.io/examples/amazon-cloud-map/cloud-map-service-example/)

#### Collections (3)

Postman and Open Collection request collections.

- [Amazon Cloud Map Instances API](https://apis.io/collections/amazon-cloud-map/open-amazon-cloud-map-instances-api/)
- [Amazon Cloud Map Instances Namespaces API](https://apis.io/collections/amazon-cloud-map/open-amazon-cloud-map-namespaces-api/)
- [Amazon Cloud Map Instances Services API](https://apis.io/collections/amazon-cloud-map/open-amazon-cloud-map-services-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Amazon Cloud Map Openapi Overlay](https://apis.io/overlays/amazon-cloud-map/amazon-cloud-map-openapi-overlay/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Amazon Cloud Map — jsonschema rules](https://apis.io/rules/amazon-cloud-map/amazon-cloud-map-jsonschema-spectral-rules/)
- [Amazon Cloud Map API Rules](https://apis.io/rules/amazon-cloud-map/amazon-cloud-map-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Amazon Cloud Map Authentication](https://apis.io/security/amazon-cloud-map/amazon-cloud-map-authentication/)
- [Amazon Cloud Map Domain Security](https://apis.io/security/amazon-cloud-map/amazon-cloud-map-domain-security/)
- [Amazon Cloud Map Trust Center](https://apis.io/security/amazon-cloud-map/amazon-cloud-map-trust-center/)
- [Amazon Cloud Map Vulnerability Disclosure](https://apis.io/security/amazon-cloud-map/amazon-cloud-map-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://aws.amazon.com/cloud-map/)
- [Documentation](https://docs.aws.amazon.com/cloud-map/)
- [Sign up](https://signin.aws.amazon.com/signup?request_type=register)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/compute/)
- [Terms of service](https://aws.amazon.com/service-terms/)
- [Privacy policy](https://aws.amazon.com/privacy/)
- [GitHub](https://github.com/aws)
- [Status](https://health.aws.amazon.com/health/status)

## API Evangelist rating

**Kin Score 45.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 28.9 |
| Contract governance | 31.8 |
| Operational transparency | 28.9 |
| Developer ergonomics | 53.6 |
| Access clarity | 52.6 |

**Agent readiness 29.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/amazon-cloud-map/](https://apis.io/providers/amazon-cloud-map/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Amazon Cloud Map: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/amazon-cloud-map/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
