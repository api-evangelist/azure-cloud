# Microsoft Azure Cloud (azure-cloud)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A comprehensive collection of Microsoft Azure cloud service APIs covering compute, storage, databases, AI, networking, security, and developer tools. Azure provides IaaS, PaaS, and SaaS delivery models through a global network of datacenters, with REST APIs secured by Microsoft Entra ID authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/azure-cloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/azure-cloud/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- Cloud Computing
- Databases
- IaaS
- Infrastructure
- Machine Learning
- Microsoft
- Networking
- PaaS
- Platform as a Service
- SaaS
- Storage

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Azure Compute API

Manage virtual machines, containers, serverless functions, and Kubernetes clusters. Includes Azure Virtual Machines, Azure Kubernetes Service (AKS), Azure Container Apps, Azure Functions, and App Service APIs.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/compute/](https://learn.microsoft.com/en-us/rest/api/compute/)
- **Base URL:** `https://management.azure.com`

#### Tags

- App Service
- Compute
- Containers
- Functions
- Kubernetes
- Serverless
- Virtual Machines

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/compute/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/virtual-machines/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/compute/resource-manager/Microsoft.Compute/stable/2023-03-01/compute.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Storage API

Scalable cloud storage REST APIs for blobs, files, queues, and tables. Includes Blob Storage, Azure Files, Queue Storage, Table Storage, and Azure Data Lake Storage.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/storageservices/](https://learn.microsoft.com/en-us/rest/api/storageservices/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Blob Storage
- Cloud Storage
- File Storage
- Object Storage
- Queue Storage
- Storage
- Table Storage

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/storageservices/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/resource-manager/Microsoft.Storage/stable/2023-01-01/storage.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Networking API

REST APIs for Azure networking resources including Virtual Networks, Load Balancers, Application Gateways, VPN Gateways, Azure Firewall, Front Door, and ExpressRoute.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/virtualnetwork/](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/)
- **Base URL:** `https://management.azure.com`

#### Tags

- ExpressRoute
- Firewall
- Load Balancer
- Networking
- Virtual Network
- VPN

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/virtualnetwork/)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Databases API

Managed database REST APIs for Azure SQL Database, Azure Cosmos DB, Azure Database for PostgreSQL, Azure Database for MySQL, and Azure Cache for Redis.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/sql/](https://learn.microsoft.com/en-us/rest/api/sql/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Cosmos DB
- Databases
- MySQL
- NoSQL
- PostgreSQL
- Redis
- SQL

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/sql/)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure AI Services API

REST APIs for Azure AI and Machine Learning services including Azure OpenAI Service, Azure Machine Learning, Azure AI Search, Computer Vision, Speech, and Document Intelligence.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/ai-services/](https://learn.microsoft.com/en-us/azure/ai-services/)
- **Base URL:** `https://management.azure.com`

#### Tags

- AI
- Artificial Intelligence
- Computer Vision
- Language
- Machine Learning
- OpenAI
- Speech

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/ai-services/)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/cognitiveservices/)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Security API

REST APIs for Azure security services including Microsoft Defender for Cloud, Key Vault, Microsoft Sentinel, and Web Application Firewall.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/defenderforcloud/](https://learn.microsoft.com/en-us/rest/api/defenderforcloud/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Defender
- Identity
- Key Vault
- Security
- Sentinel

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/defenderforcloud/)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Integration API

REST APIs for Azure integration services including Service Bus, Event Grid, Logic Apps, and API Management for building event-driven and workflow-based applications.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/servicebus/](https://learn.microsoft.com/en-us/rest/api/servicebus/)
- **Base URL:** `https://management.azure.com`

#### Tags

- API Management
- Event Grid
- Integration
- Logic Apps
- Messaging
- Service Bus
- Workflows

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/servicebus/)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Analytics API

REST APIs for Azure analytics services including Synapse Analytics, Data Factory, Stream Analytics, Data Explorer, and Microsoft Fabric for big data and real-time analytics workloads.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/synapse/](https://learn.microsoft.com/en-us/rest/api/synapse/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Analytics
- Big Data
- Data Factory
- ETL
- Stream Analytics
- Synapse

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/synapse/)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Management API

REST APIs for Azure management and governance including Azure Resource Manager, Azure Monitor, Azure Policy, Cost Management, and Azure Advisor.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/](https://learn.microsoft.com/en-us/rest/api/azure/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Cost Management
- Governance
- Management
- Monitor
- Policy
- Resource Manager

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/resources/)
- [Authentication](https://learn.microsoft.com/en-us/rest/api/azure/#register-your-client-application-with-microsoft-entra-id)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure IoT API

REST APIs for Azure IoT services including IoT Hub, IoT Central, IoT Edge, and Azure Digital Twins for connecting, monitoring, and managing IoT devices at scale.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/iothub/](https://learn.microsoft.com/en-us/rest/api/iothub/)
- **Base URL:** `https://management.azure.com`

#### Tags

- Digital Twins
- IoT
- IoT Central
- IoT Edge
- IoT Hub

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/iothub/)
- [Postman Collection](collections/azure-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/microsoft-azure-cloud)
- [Portal](https://portal.azure.com)
- [Documentation](https://learn.microsoft.com/en-us/azure/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/developer/intro/azure-developer-overview)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/)
- [Authentication](https://learn.microsoft.com/en-us/entra/identity-platform/v2-oauth2-client-creds-grant-flow)
- [Status Page](https://status.azure.com)
- [Blog](https://azure.microsoft.com/en-us/blog/)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure)
- [Pricing](https://azure.microsoft.com/en-us/pricing/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)
- [C L I](https://learn.microsoft.com/en-us/cli/azure/)
- [SDK](https://azure.github.io/azure-sdk/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
