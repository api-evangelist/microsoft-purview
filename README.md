# Microsoft Purview (microsoft-purview)
Microsoft Purview is a comprehensive data governance service that helps organizations discover, catalog, classify, and manage their data estate across on-premises, multi-cloud, and SaaS environments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-purview/refs/heads/main/apis.yml)

## Tags:

 - Compliance, Data Catalog, Data Classification, Data Governance, Data Loss Prevention, Information Protection

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### Microsoft Purview Catalog API
APIs for discovering, cataloging, and managing metadata for data assets across your data estate. The catalog is built on Apache Atlas and provides searchable inventory of data assets with classifications and glossary terms.

**Human URL:** [https://learn.microsoft.com/en-us/purview/catalog-api](https://learn.microsoft.com/en-us/purview/catalog-api)

**Base URL:** https://{account-name}.purview.azure.com

#### Tags:

 - Classifications, Data Catalog, Data Discovery, Glossary, Metadata

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/)
- [OpenAPI](openapi/microsoft-purview-catalog-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/purview/)
- [Getting Started](https://learn.microsoft.com/en-us/purview/data-gov-api-create-assets)

### Microsoft Purview Scanning API
APIs for configuring and managing scans of data sources to automatically discover and catalog data assets. Supports registering data sources and scheduling automated scans across your data estate.

**Human URL:** [https://learn.microsoft.com/en-us/purview/scanning-api](https://learn.microsoft.com/en-us/purview/scanning-api)

**Base URL:** https://{account-name}.purview.azure.com

#### Tags:

 - Automated Discovery, Classification Rules, Data Scanning, Data Sources, Scan Triggers

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/scanning)
- [OpenAPI](openapi/microsoft-purview-scanning-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Reference](https://learn.microsoft.com/en-us/purview/data-map-data-sources)

### Microsoft Purview Account API
APIs for managing Purview accounts, configurations, and administrative settings. Provides resource management operations for creating, updating, and deleting Purview accounts through Azure Resource Manager.

**Human URL:** [https://learn.microsoft.com/en-us/purview/account-api](https://learn.microsoft.com/en-us/purview/account-api)

**Base URL:** https://management.azure.com

#### Tags:

 - Account Management, Administration, Configuration, Resource Manager

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/account)
- [OpenAPI](openapi/microsoft-purview-account-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow)

### Microsoft Purview Data Map API
APIs for accessing and managing the unified data map that provides a holistic view of your data estate. Supports entity management, lineage tracking, relationship mapping, and discovery queries across cataloged assets.

**Human URL:** [https://learn.microsoft.com/en-us/purview/data-map-api](https://learn.microsoft.com/en-us/purview/data-map-api)

**Base URL:** https://{account-name}.purview.azure.com

#### Tags:

 - Data Discovery, Data Map, Entity Management, Lineage, Relationships

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/datamap)
- [OpenAPI](openapi/microsoft-purview-data-map-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Getting Started](https://learn.microsoft.com/en-us/purview/legacy/how-to-purview-custom-lineage-api-user-guide)

### Microsoft Purview Metadata Policies API
APIs for creating and managing data access policies based on metadata attributes. Enables programmatic management of collection-level permissions and role assignments.

**Human URL:** [https://learn.microsoft.com/en-us/purview/metadata-policies](https://learn.microsoft.com/en-us/purview/metadata-policies)

**Base URL:** https://{account-name}.purview.azure.com

#### Tags:

 - Access Policies, Collections, Data Governance, Metadata, Role Assignments

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/metadatapolicies)
- [OpenAPI](openapi/microsoft-purview-metadata-policies-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)
- [Getting Started](https://learn.microsoft.com/en-us/purview/legacy/tutorial-metadata-policy-collections-apis)

### Microsoft Purview Workflow API
APIs for managing workflows and approval processes for data governance tasks. Supports defining custom approval workflows for glossary term management and other governance operations.

**Human URL:** [https://learn.microsoft.com/en-us/purview/workflow-api](https://learn.microsoft.com/en-us/purview/workflow-api)

**Base URL:** https://{account-name}.purview.azure.com

#### Tags:

 - Approvals, Automation, Governance Tasks, Workflows

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/workflow)
- [OpenAPI](openapi/microsoft-purview-workflow-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/purview/tutorial-using-rest-apis)

### Microsoft Purview Unified Catalog API
APIs for programmatically integrating and managing the Microsoft Purview Unified Catalog. Supports operations on business domains, glossary terms, data products, OKRs, critical data elements, and data access policies.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-api-overview](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-api-overview)

**Base URL:** https://{account-name}.purview.azure.com

#### Tags:

 - Business Domains, Data Governance, Data Products, Glossary Terms, Unified Catalog

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-api-overview)
- [OpenAPI](openapi/microsoft-purview-unified-catalog-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/purview/data-gov-api-rest-data-plane)

### Microsoft Purview Data Quality API
APIs for programmatically interacting with data quality rules, measuring data quality, and retrieving data quality scores for data assets. Supports data profiling, rule management, and quality assessment operations.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-data-quality](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-data-quality)

**Base URL:** https://{account-name}.purview.azure.com

#### Tags:

 - Data Assessment, Data Profiling, Data Quality, Quality Rules

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/purview/unified-catalog-data-quality)
- [OpenAPI](openapi/microsoft-purview-data-quality-openapi.yml)
- [Reference](https://learn.microsoft.com/en-us/purview/unified-catalog-data-quality)
- [Authentication](https://learn.microsoft.com/en-us/purview/data-gov-api-rest-data-plane)

### Microsoft Purview eDiscovery API
APIs for automating eDiscovery operations through Microsoft Graph, including managing cases, custodians, review sets, searches, and exports for litigation, investigation, and regulatory requests.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/security-ediscovery-apioverview](https://learn.microsoft.com/en-us/graph/api/resources/security-ediscovery-apioverview)

**Base URL:** https://graph.microsoft.com

#### Tags:

 - Compliance, eDiscovery, Investigations, Legal Hold, Litigation

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/security-ediscovery-apioverview?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-purview-ediscovery-openapi.yml)
- [Authentication](https://learn.microsoft.com/en-us/graph/security-ediscovery-appauthsetup)
- [Getting Started](https://learn.microsoft.com/en-us/purview/edisc-ref-api-guide)

### Microsoft Purview Information Protection API
APIs for accessing and managing sensitivity labels through Microsoft Graph. Enables applications to apply, update, and delete sensitivity labels, evaluate label actions, and enforce information protection policies programmatically.

**Human URL:** [https://learn.microsoft.com/en-us/graph/security-information-protection-overview](https://learn.microsoft.com/en-us/graph/security-information-protection-overview)

**Base URL:** https://graph.microsoft.com

#### Tags:

 - Data Classification, Encryption, Information Protection, Rights Management, Sensitivity Labels

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/security-information-protection-overview)
- [OpenAPI](openapi/microsoft-purview-information-protection-openapi.yml)
- [Reference](https://learn.microsoft.com/en-us/purview/sensitivity-labels)

### Microsoft Purview Data Security and Governance API
APIs for integrating data loss prevention and compliance policy enforcement into applications through Microsoft Graph. Provides compute protection scopes and process content operations to evaluate and enforce DLP policies at runtime.

**Human URL:** [https://learn.microsoft.com/en-us/graph/security-datasecurityandgovernance-overview](https://learn.microsoft.com/en-us/graph/security-datasecurityandgovernance-overview)

**Base URL:** https://graph.microsoft.com

#### Tags:

 - AI Security, Compliance, Data Loss Prevention, Data Security, Policy Enforcement

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/security-datasecurityandgovernance-overview)
- [OpenAPI](openapi/microsoft-purview-data-security-governance-openapi.yml)
- [Getting Started](https://learn.microsoft.com/en-us/purview/developer/use-the-api)
- [Reference](https://learn.microsoft.com/en-us/purview/developer/)

### Microsoft Purview Records Management API
APIs for managing retention labels, retention policies, and disposition review through Microsoft Graph. Helps organizations manage data retention and deletion to meet legal obligations and compliance regulations.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/security-recordsmanagement-overview](https://learn.microsoft.com/en-us/graph/api/resources/security-recordsmanagement-overview)

**Base URL:** https://graph.microsoft.com

#### Tags:

 - Compliance, Data Lifecycle, Records Management, Retention Labels

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/security-recordsmanagement-overview?view=graph-rest-1.0)
- [OpenAPI](openapi/microsoft-purview-records-management-openapi.yml)
- [Reference](https://learn.microsoft.com/en-us/graph/compliance-concept-overview)

## Common Properties

- [Portal](https://purview.microsoft.com)
- [Documentation](https://learn.microsoft.com/en-us/purview/)
- [Getting Started](https://learn.microsoft.com/en-us/purview/use-azure-purview-studio)
- [Authentication](https://learn.microsoft.com/en-us/purview/data-gov-api-rest-data-plane)
- [Reference](https://learn.microsoft.com/en-us/rest/api/purview/)
- [SDKs](https://learn.microsoft.com/en-us/purview/data-gov-python-sdk)
- [Best Practices](https://learn.microsoft.com/en-us/purview/concept-best-practices-accounts)
- [Change Log](https://learn.microsoft.com/en-us/purview/whats-new)
- [Blog](https://techcommunity.microsoft.com/t5/microsoft-purview-blog/bg-p/MicrosoftPurviewBlog)
- [Support](https://learn.microsoft.com/en-us/answers/topics/azure-purview.html)
- [Status](https://status.azure.com/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure/azure-sdk-for-python/tree/main/sdk/purview)
- [Community](https://techcommunity.microsoft.com/t5/microsoft-purview/ct-p/MicrosoftPurview)
- [Website](https://www.microsoft.com/en-us/security/business/microsoft-purview)
- [Login](https://purview.microsoft.com)
- [Sign Up](https://azure.microsoft.com/en-us/products/purview/)
- [JSON-LD](json-ld/microsoft-purview-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
