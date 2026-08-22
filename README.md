# Amazon Cloud Map (amazon-cloud-map)

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

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-cloud-map/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Cloud Map, Service Discovery, Microservices, DNS

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon Cloud Map API
API for managing service discovery namespaces, services, and instances with health checking. Enables microservices to dynamically discover dependencies.

**Human URL:** [https://aws.amazon.com/cloud-map/](https://aws.amazon.com/cloud-map/)

#### Tags:

 - AWS, Cloud Map, Service Discovery, Microservices

#### Properties

- [Documentation](https://docs.aws.amazon.com/cloud-map/latest/api/)
- [OpenAPI](openapi/amazon-cloud-map-openapi.yml)
- [GettingStarted](https://aws.amazon.com/cloud-map/getting-started/)
- [Pricing](https://aws.amazon.com/cloud-map/pricing/)
- [FAQ](https://aws.amazon.com/cloud-map/faqs/)
- [APIReference](https://docs.aws.amazon.com/cloud-map/latest/api/)
- [JSONSchema](json-schema/cloud-map-namespace-schema.json)
- [JSONSchema](json-schema/cloud-map-service-schema.json)
- [JSONLD](json-ld/amazon-cloud-map-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/cloud-map/)
- [SpectralRules](rules/amazon-cloud-map-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-cloud-map-vocabulary.yaml)
- [NaftikoCapability](capabilities/service-discovery.yaml)

## Features

| Name | Description |
|------|-------------|
| Service Registry | Maintain an up-to-date registry of application resources with custom naming. |
| Health Monitoring | Continuously monitor health of every IP-based component and route only to healthy endpoints. |
| Dynamic Discovery | Automatically update service registries as services scale up or down. |
| Custom Names | Define custom names for application resources rather than hardcoding IP addresses. |
| Multi-Environment Support | Maintain service registries across different deployment environments, regions, and application versions. |

## Use Cases

| Name | Description |
|------|-------------|
| Microservice Discovery | Enable services to locate dependencies in dynamic container environments with ECS and EKS. |
| Health-Based Routing | Ensure traffic routes only to verified healthy service endpoints. |
| CI/CD Integration | Automatically register and deregister services during CI/CD pipeline deployments. |
| Multi-Region Service Mesh | Discover services across multiple AWS regions with a unified namespace. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon ECS | Automatically register ECS task IPs in Cloud Map as containers launch. |
| Amazon EKS | Integrate Kubernetes service discovery with Cloud Map for hybrid environments. |
| Amazon Route 53 | DNS-based service discovery backed by Route 53 private hosted zones. |
| AWS App Mesh | Use Cloud Map as the service registry for App Mesh virtual services. |
| AWS IAM | Control access to Cloud Map namespaces with IAM policies. |

## Artifacts

### OpenAPI

- [Amazon Cloud Map API](openapi/amazon-cloud-map-openapi.yml)

### JSON Schema

- [Namespace](json-schema/cloud-map-namespace-schema.json)
- [Service](json-schema/cloud-map-service-schema.json)
- [Instance](json-schema/cloud-map-instance-schema.json)
- [Http Instance Summary](json-schema/cloud-map-http-instance-summary-schema.json)

### JSON-LD

- [Amazon Cloud Map Context](json-ld/amazon-cloud-map-context.jsonld)

## Capabilities

### Shared Per-API Definitions

- [Amazon Cloud Map](capabilities/shared/cloud-map.yaml) — 6 operations for service discovery management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Service Discovery](capabilities/service-discovery.yaml) | Cloud Map | 6 | Platform Engineer, DevOps Engineer |

## Vocabulary

- [Amazon Cloud Map Vocabulary](vocabulary/amazon-cloud-map-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 4 actions, 1 workflow, and 2 personas

## Rules

- [Amazon Cloud Map Spectral Rules](rules/amazon-cloud-map-spectral-rules.yml) — 20 rules enforcing Amazon Cloud Map API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
