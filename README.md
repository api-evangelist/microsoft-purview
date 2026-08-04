# Microsoft Purview (microsoft-purview)

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

Microsoft Purview is a comprehensive data governance service that helps organizations discover, catalog, classify, and manage their data estate across on-premises, multi-cloud, and SaaS environments.

**APIs.json:** [https://www.microsoft.com/en-us/security/business/microsoft-purview](https://www.microsoft.com/en-us/security/business/microsoft-purview)

## Tags

- Compliance
- Data Catalog
- Data Classification
- Data Governance
- Data Loss Prevention
- Information Protection

## Timestamps

- **Created:** Sun Jan 14 2024 19:00:00 GMT-0500 (Eastern Standard Time)
- **Modified:** 2026-05-19

## APIs

### Microsoft Purview Catalog API

APIs for discovering, cataloging, and managing metadata for data assets across your data estate. The catalog is built on Apache Atlas and provides searchable inventory of data assets with classifications and glossary terms.

- **Human URL:** [https://learn.microsoft.com/en-us/purview/catalog-api](https://learn.microsoft.com/en-us/purview/catalog-api)
- **Base URL:** `https://{account-name}.purview.azure.com`

#### Tags

- Classifications
- Data Catalog
- Data Discovery
- Glossary
- Metadata

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/)
- [OpenAPI](openapi/microsoft-purview-catalog-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/purview/)
- [Getting Started](https://learn.microsoft.com/en-us/purview/data-gov-api-create-assets)

### Microsoft Purview Scanning API

APIs for configuring and managing scans of data sources to automatically discover and catalog data assets. Supports registering data sources and scheduling automated scans across your data estate.

- **Human URL:** [https://learn.microsoft.com/en-us/purview/scanning-api](https://learn.microsoft.com/en-us/purview/scanning-api)
- **Base URL:** `https://{account-name}.purview.azure.com`

#### Tags

- Automated Discovery
- Classification Rules
- Data Scanning
- Data Sources
- Scan Triggers

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/scanning)
- [OpenAPI](openapi/microsoft-purview-scanning-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-scanning.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-scanning.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Reference](https://learn.microsoft.com/en-us/purview/data-map-data-sources)

### Microsoft Purview Account API

APIs for managing Purview accounts, configurations, and administrative settings. Provides resource management operations for creating, updating, and deleting Purview accounts through Azure Resource Manager.

- **Human URL:** [https://learn.microsoft.com/en-us/purview/account-api](https://learn.microsoft.com/en-us/purview/account-api)
- **Base URL:** `https://management.azure.com`

#### Tags

- Account Management
- Administration
- Configuration
- Resource Manager

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/account)
- [OpenAPI](openapi/microsoft-purview-account-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow)

### Microsoft Purview Data Map API

APIs for accessing and managing the unified data map that provides a holistic view of your data estate. Supports entity management, lineage tracking, relationship mapping, and discovery queries across cataloged assets.

- **Human URL:** [https://learn.microsoft.com/en-us/purview/data-map-api](https://learn.microsoft.com/en-us/purview/data-map-api)
- **Base URL:** `https://{account-name}.purview.azure.com`

#### Tags

- Data Discovery
- Data Map
- Entity Management
- Lineage
- Relationships

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/datamap)
- [OpenAPI](openapi/microsoft-purview-data-map-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-data-map.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-data-map.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Getting Started](https://learn.microsoft.com/en-us/purview/legacy/how-to-purview-custom-lineage-api-user-guide)

### Microsoft Purview Metadata Policies API

APIs for creating and managing data access policies based on metadata attributes. Enables programmatic management of collection-level permissions and role assignments.

- **Human URL:** [https://learn.microsoft.com/en-us/purview/metadata-policies](https://learn.microsoft.com/en-us/purview/metadata-policies)
- **Base URL:** `https://{account-name}.purview.azure.com`

#### Tags

- Access Policies
- Collections
- Data Governance
- Metadata
- Role Assignments

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/metadatapolicies)
- [OpenAPI](openapi/microsoft-purview-metadata-policies-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-metadata-policies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-metadata-policies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Getting Started](https://learn.microsoft.com/en-us/purview/legacy/tutorial-metadata-policy-collections-apis)

### Microsoft Purview Workflow API

APIs for managing workflows and approval processes for data governance tasks. Supports defining custom approval workflows for glossary term management and other governance operations.

- **Human URL:** [https://learn.microsoft.com/en-us/purview/workflow-api](https://learn.microsoft.com/en-us/purview/workflow-api)
- **Base URL:** `https://{account-name}.purview.azure.com`

#### Tags

- Approvals
- Automation
- Governance Tasks
- Workflows

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/workflow)
- [OpenAPI](openapi/microsoft-purview-workflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-workflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-workflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)

### Microsoft Purview Unified Catalog API

APIs for programmatically integrating and managing the Microsoft Purview Unified Catalog. Supports operations on business domains, glossary terms, data products, OKRs, critical data elements, and data access policies.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-api-overview](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-api-overview)
- **Base URL:** `https://{account-name}.purview.azure.com`

#### Tags

- Business Domains
- Data Governance
- Data Products
- Glossary Terms
- Unified Catalog

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-api-overview)
- [OpenAPI](openapi/microsoft-purview-unified-catalog-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-unified-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-unified-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/purview/data-gov-api-rest-data-plane)

### Microsoft Purview Data Quality API

APIs for programmatically interacting with data quality rules, measuring data quality, and retrieving data quality scores for data assets. Supports data profiling, rule management, and quality assessment operations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-data-quality](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-data-quality)
- **Base URL:** `https://{account-name}.purview.azure.com`

#### Tags

- Data Assessment
- Data Profiling
- Data Quality
- Quality Rules

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-data-quality)
- [OpenAPI](openapi/microsoft-purview-data-quality-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-data-quality.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-data-quality.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://learn.microsoft.com/en-us/purview/unified-catalog-data-quality)
- [Authentication](https://learn.microsoft.com/en-us/purview/data-gov-api-rest-data-plane)

### Microsoft Purview eDiscovery API

APIs for automating eDiscovery operations through Microsoft Graph, including managing cases, custodians, review sets, searches, and exports for litigation, investigation, and regulatory requests.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/security-ediscovery-apioverview](https://learn.microsoft.com/en-us/graph/api/resources/security-ediscovery-apioverview)
- **Base URL:** `https://graph.microsoft.com`

#### Tags

- Compliance
- eDiscovery
- Investigations
- Legal Hold
- Litigation

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/security-ediscovery-apioverview?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-purview-ediscovery-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-ediscovery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-ediscovery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/graph/security-ediscovery-appauthsetup)
- [Getting Started](https://learn.microsoft.com/en-us/purview/edisc-ref-api-guide)

### Microsoft Purview Information Protection API

APIs for accessing and managing sensitivity labels through Microsoft Graph. Enables applications to apply, update, and delete sensitivity labels, evaluate label actions, and enforce information protection policies programmatically.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/security-information-protection-overview](https://learn.microsoft.com/en-us/graph/security-information-protection-overview)
- **Base URL:** `https://graph.microsoft.com`

#### Tags

- Data Classification
- Encryption
- Information Protection
- Rights Management
- Sensitivity Labels

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/security-information-protection-overview)
- [OpenAPI](openapi/microsoft-purview-information-protection-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-information-protection.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-information-protection.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://learn.microsoft.com/en-us/purview/sensitivity-labels)

### Microsoft Purview Data Security and Governance API

APIs for integrating data loss prevention and compliance policy enforcement into applications through Microsoft Graph. Provides compute protection scopes and process content operations to evaluate and enforce DLP policies at runtime.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/security-datasecurityandgovernance-overview](https://learn.microsoft.com/en-us/graph/security-datasecurityandgovernance-overview)
- **Base URL:** `https://graph.microsoft.com`

#### Tags

- AI Security
- Compliance
- Data Loss Prevention
- Data Security
- Policy Enforcement

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/security-datasecurityandgovernance-overview)
- [OpenAPI](openapi/microsoft-purview-data-security-governance-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-data-security-governance.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-data-security-governance.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://learn.microsoft.com/en-us/purview/developer/use-the-api)
- [Reference](https://learn.microsoft.com/en-us/purview/developer/)

### Microsoft Purview Records Management API

APIs for managing retention labels, retention policies, and disposition review through Microsoft Graph. Helps organizations manage data retention and deletion to meet legal obligations and compliance regulations.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/security-recordsmanagement-overview](https://learn.microsoft.com/en-us/graph/api/resources/security-recordsmanagement-overview)
- **Base URL:** `https://graph.microsoft.com`

#### Tags

- Compliance
- Data Lifecycle
- Records Management
- Retention Labels

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/security-recordsmanagement-overview?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-purview-records-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-purview-records-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-purview-records-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://learn.microsoft.com/en-us/graph/compliance-concept-overview)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://purview.microsoft.com)
- [Documentation](https://learn.microsoft.com/en-us/purview/)
- [Getting Started](https://learn.microsoft.com/en-us/purview/use-azure-purview-studio)
- [Authentication](https://learn.microsoft.com/en-us/purview/data-gov-api-rest-data-plane)
- [Reference](https://learn.microsoft.com/en-us/rest/api/purview/)
- [S D Ks](https://learn.microsoft.com/en-us/purview/data-gov-python-sdk)
- [Best  Practices](https://learn.microsoft.com/en-us/purview/concept-best-practices-accounts)
- [Changelog](https://learn.microsoft.com/en-us/purview/whats-new)
- [Blog](https://techcommunity.microsoft.com/t5/microsoft-purview-blog/bg-p/MicrosoftPurviewBlog)
- [Support](https://learn.microsoft.com/en-us/answers/topics/azure-purview.html)
- [Status Page](https://status.azure.com/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/purview)
- [Community](https://techcommunity.microsoft.com/t5/microsoft-purview/ct-p/MicrosoftPurview)
- [Website](https://www.microsoft.com/en-us/security/business/microsoft-purview)
- [Login](https://purview.microsoft.com)
- [Sign Up](https://azure.microsoft.com/en-us/products/purview/)
- [JSON-LD](json-ld/microsoft-purview-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://www.microsoft.com/en-us/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
