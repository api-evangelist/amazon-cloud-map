# Amazon Cloud Map (amazon-cloud-map)
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
