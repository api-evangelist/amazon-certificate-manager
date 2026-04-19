# Amazon Certificate Manager (amazon-certificate-manager)
AWS Certificate Manager (ACM) handles the complexity of creating, storing, and renewing public and private SSL/TLS X.509 certificates and keys that protect your AWS websites and applications, enabling you to manage certificate lifecycles centrally.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Certificates, Encryption, Security, SSL, TLS

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Certificate Manager API
API for provisioning, managing, and deploying public and private SSL/TLS certificates for use with AWS services and your internal connected resources.

**Human URL:** [https://aws.amazon.com/certificate-manager/](https://aws.amazon.com/certificate-manager/)

#### Tags:

 - AWS, Certificates, Encryption, Security, SSL, TLS

#### Properties

- [Documentation](https://docs.aws.amazon.com/acm/latest/APIReference/)
- [OpenAPI](openapi/amazon-certificate-manager-openapi.yml)
- [OpenAPI](https://api.apis.guru/v2/specs/amazonaws.com/acm/2015-12-08/openapi.yaml)
- [JSONSchema](json-schema/amazon-certificate-manager-certificate-schema.json)
- [JSONLD](json-ld/amazon-certificate-manager-context.jsonld)
- [Pricing](https://aws.amazon.com/certificate-manager/pricing/)
- [GettingStarted](https://aws.amazon.com/certificate-manager/getting-started/)
- [FAQ](https://aws.amazon.com/certificate-manager/faqs/)
- [APIReference](https://docs.aws.amazon.com/acm/latest/APIReference/)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/acm/)
- [Security](https://docs.aws.amazon.com/acm/latest/userguide/security.html)
- [JSONSchema](json-schema/certificate-manager-request-certificate-request-schema.json)
- [JSONSchema](json-schema/certificate-manager-request-certificate-response-schema.json)
- [JSONSchema](json-schema/certificate-manager-list-certificates-response-schema.json)
- [JSONSchema](json-schema/certificate-manager-describe-certificate-response-schema.json)
- [Example](examples/certificate-manager-request-certificate-request-example.json)
- [Example](examples/certificate-manager-request-certificate-response-example.json)
- [Example](examples/certificate-manager-list-certificates-response-example.json)
- [Example](examples/certificate-manager-describe-certificate-response-example.json)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/certificate-manager/)
- [Documentation](https://docs.aws.amazon.com/acm/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/security/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/acm/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-certificate-manager)
- [Contact](https://aws.amazon.com/contact-us/)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-certificate-manager-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-certificate-manager-vocabulary.yaml)
- [NaftikoCapability](capabilities/certificate-lifecycle-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Automated Certificate Renewal | Managed renewal for Amazon-issued SSL/TLS certificates, reducing manual maintenance overhead. |
| Public and Private Certificates | Provision both public certificates validated via DNS or email, and private certificates issued by a private CA. |
| FIPS-Compliant Key Storage | Strong encryption and key management best practices for protecting and storing private keys. |
| Integrated AWS Service Deployment | Deploy certificates to CloudFront, Elastic Load Balancing, API Gateway, and other integrated AWS services at no cost. |
| Hybrid and Multicloud Support | Provision and manage certificates for EC2, containers, on-premises hosts, and multicloud workloads. |

## Use Cases

| Name | Description |
|------|-------------|
| Website Protection | Securely terminate HTTPS traffic to public websites and web applications using ACM certificates. |
| Internal Service Security | Protect private network communication between servers, mobile devices, IoT devices, and internal applications. |
| Uptime Maintenance | Automated certificate lifecycle management prevents certificate expiration-related service downtime. |
| Compliance and Audit | Centralize certificate management to meet compliance requirements and simplify security audits. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon CloudFront | Deploy ACM certificates to CloudFront distributions for HTTPS content delivery. |
| Elastic Load Balancing | Attach ACM certificates to Application, Network, and Classic Load Balancers. |
| Amazon API Gateway | Use ACM certificates for custom domain names in API Gateway. |
| AWS IAM | Control access to ACM operations via IAM policies and roles. |
| AWS CloudTrail | Audit all ACM API calls via CloudTrail for compliance and security monitoring. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Certificate Manager API](openapi/amazon-certificate-manager-openapi.yml)

### JSON Schema

- [Certificate Schema](json-schema/amazon-certificate-manager-certificate-schema.json)
- [Request Certificate Request](json-schema/certificate-manager-request-certificate-request-schema.json)
- [Request Certificate Response](json-schema/certificate-manager-request-certificate-response-schema.json)
- [List Certificates Response](json-schema/certificate-manager-list-certificates-response-schema.json)
- [Describe Certificate Response](json-schema/certificate-manager-describe-certificate-response-schema.json)

### JSON Structure

- [Request Certificate Request](json-structure/certificate-manager-request-certificate-request-structure.json)
- [Request Certificate Response](json-structure/certificate-manager-request-certificate-response-structure.json)
- [List Certificates Response](json-structure/certificate-manager-list-certificates-response-structure.json)
- [Describe Certificate Response](json-structure/certificate-manager-describe-certificate-response-structure.json)

### JSON-LD

- [Amazon Certificate Manager Context](json-ld/amazon-certificate-manager-context.jsonld)

### Examples

- [Request Certificate Request](examples/certificate-manager-request-certificate-request-example.json)
- [Request Certificate Response](examples/certificate-manager-request-certificate-response-example.json)
- [List Certificates Response](examples/certificate-manager-list-certificates-response-example.json)
- [Describe Certificate Response](examples/certificate-manager-describe-certificate-response-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Certificate Manager](capabilities/shared/certificate-manager.yaml) — 4 operations for SSL/TLS certificate provisioning and management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Certificate Lifecycle Management](capabilities/certificate-lifecycle-management.yaml) | ACM | 4 | DevOps Engineer, Security Engineer |

## Vocabulary

- [Amazon Certificate Manager Vocabulary](vocabulary/amazon-certificate-manager-vocabulary.yaml) — Unified taxonomy mapping 1 resource, 4 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Certificate Manager Spectral Rules](rules/amazon-certificate-manager-spectral-rules.yml) — 27 rules across 10 categories enforcing Amazon Certificate Manager API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
