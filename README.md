# WhatsApp (whatsapp)

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

APIs for the WhatsApp messaging platform, enabling businesses to communicate with customers through the world's most popular messaging app.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/whatsapp/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### WhatsApp Business Platform API

The Cloud API and On-Premises API that enables medium and large businesses to communicate with customers at scale.

- **Human URL:** [https://developers.facebook.com/docs/whatsapp](https://developers.facebook.com/docs/whatsapp)
- **Base URL:** `https://graph.facebook.com/v21.0`

#### Tags

- Business
- Chat
- Communications
- Messaging

#### Properties

- [Documentation](https://developers.facebook.com/docs/whatsapp/cloud-api)
- [OpenAPI](openapi/whatsapp-cloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whatsapp-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whatsapp-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.facebook.com/docs/whatsapp/business-management-api/get-started)
- [Documentation](https://developers.facebook.com/docs/whatsapp/cloud-api/webhooks)
- [AsyncAPI](asyncapi/whatsapp-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/whatsapp-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Reference](https://developers.facebook.com/docs/whatsapp/cloud-api/reference/messages)
- [Getting Started](https://developers.facebook.com/docs/whatsapp/cloud-api/get-started)
- [Pricing](https://developers.facebook.com/docs/whatsapp/pricing)
- [Rate Limits](https://developers.facebook.com/docs/whatsapp/cloud-api/overview#throughput)
- [Status Page](https://metastatus.com/)
- [Changelog](https://developers.facebook.com/docs/whatsapp/cloud-api/changelog)
- [Error Codes](https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes)
- [Postman Collection](https://www.postman.com/meta/whatsapp-business-platform/collection/wlk6lh4/whatsapp-cloud-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Node.js  S D K](https://github.com/WhatsApp/WhatsApp-Nodejs-SDK)
- [Sandbox](https://business.whatsapp.com/developers/developer-hub)
- [Migration  Guide](https://developers.facebook.com/docs/whatsapp/cloud-api/migrate-to-cloud-api)
- [Media  Reference](https://developers.facebook.com/docs/whatsapp/cloud-api/reference/media)
- [Phone  Numbers  Reference](https://developers.facebook.com/docs/whatsapp/cloud-api/reference/phone-numbers)
- [Business  Profiles  Reference](https://developers.facebook.com/docs/whatsapp/cloud-api/reference/business-profiles)
- [Two- Step  Verification](https://developers.facebook.com/docs/whatsapp/cloud-api/reference/two-step-verification)
- [Versioning](https://developers.facebook.com/docs/graph-api/guides/versioning)

### WhatsApp Business Account Management API

API for managing WhatsApp Business Accounts, phone numbers, and messaging templates.

- **Human URL:** [https://developers.facebook.com/docs/whatsapp/business-management-api](https://developers.facebook.com/docs/whatsapp/business-management-api)
- **Base URL:** `https://graph.facebook.com/v21.0`

#### Tags

- Accounts
- Business
- Management
- Templates

#### Properties

- [Documentation](https://developers.facebook.com/docs/whatsapp/business-management-api)
- [OpenAPI](openapi/whatsapp-business-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whatsapp-business-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whatsapp-business-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developers.facebook.com/docs/whatsapp/business-management-api/get-started)
- [JSON Schema](json-schema/whatsapp-message-template-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Getting Started](https://developers.facebook.com/docs/whatsapp/business-management-api/get-started)
- [Postman Collection](https://www.postman.com/meta/whatsapp-business-platform/collection/3kru5r6/whatsapp-business-management-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Reference](https://developers.facebook.com/docs/whatsapp/business-management-api/message-templates)
- [Changelog](https://developers.facebook.com/docs/whatsapp/business-management-api/changelog)
- [Error Codes](https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes)
- [Rate Limits](https://developers.facebook.com/docs/whatsapp/cloud-api/overview#throughput)

### WhatsApp Flows API

API for creating structured, interactive forms and multi-step flows within WhatsApp conversations, enabling appointment booking, surveys, lead capture, and other guided experiences using a JSON-based screen definition format.

- **Human URL:** [https://developers.facebook.com/docs/whatsapp/flows](https://developers.facebook.com/docs/whatsapp/flows)
- **Base URL:** `https://graph.facebook.com/v21.0`

#### Tags

- Flows
- Forms
- Interactive
- Messaging

#### Properties

- [Documentation](https://developers.facebook.com/docs/whatsapp/flows)
- [OpenAPI](openapi/whatsapp-flows-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/whatsapp-flows-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whatsapp-flows-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://developers.facebook.com/docs/whatsapp/flows/reference/components)
- [JSON Schema](json-schema/whatsapp-flow-json-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Changelog](https://developers.facebook.com/docs/whatsapp/flows/changelogs)
- [Error Codes](https://developers.facebook.com/docs/whatsapp/flows/reference/error-codes)
- [Postman Collection](https://www.postman.com/meta/whatsapp-business-platform/collection/y5swede/whatsapp-flows-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub Repository](https://github.com/WhatsApp/WhatsApp-Flows-Tools)
- [Getting Started](https://developers.facebook.com/docs/whatsapp/flows/gettingstarted)
- [Authentication](https://developers.facebook.com/docs/whatsapp/business-management-api/get-started)

### WhatsApp On-Premises API

The self-hosted version of the WhatsApp Business API that allowed businesses to run the API on their own infrastructure. This API was deprecated on October 23, 2025, and all users must migrate to the Cloud API.

- **Human URL:** [https://developers.facebook.com/docs/whatsapp/on-premises](https://developers.facebook.com/docs/whatsapp/on-premises)
- **Base URL:** `https://localhost:443`

#### Tags

- Deprecated
- Messaging
- On-Premises
- Self-Hosted

#### Properties

- [Documentation](https://developers.facebook.com/docs/whatsapp/on-premises)
- [Getting Started](https://developers.facebook.com/docs/whatsapp/on-premises/get-started/installation)
- [Deprecation  Notice](https://developers.facebook.com/docs/whatsapp/on-premises)
- [Postman Collection](https://www.postman.com/meta/whatsapp-business-platform/collection/vdi189b/whatsapp-on-premises-api-deprecated) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Migration  Guide](https://developers.facebook.com/docs/whatsapp/cloud-api/migrate-to-cloud-api)
- [Postman Collection](collections/whatsapp-business-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whatsapp-business-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/whatsapp-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whatsapp-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/whatsapp-flows-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whatsapp-flows-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Terms of Service](https://www.whatsapp.com/legal/business-terms)
- [Privacy Policy](https://www.whatsapp.com/legal/privacy-policy-eea)
- [Commerce  Policy](https://www.whatsapp.com/legal/commerce-policy)
- [Developer  Portal](https://developers.facebook.com/)
- [Getting Started](https://developers.facebook.com/docs/whatsapp/cloud-api/get-started)
- [Authentication](https://developers.facebook.com/docs/whatsapp/business-management-api/get-started)
- [Best  Practices](https://developers.facebook.com/docs/whatsapp/cloud-api/best-practices)
- [Use  Cases](https://business.whatsapp.com/products/business-platform)
- [Changelog](https://developers.facebook.com/docs/whatsapp/cloud-api/changelog)
- [Status Page](https://metastatus.com/)
- [Blog](https://business.whatsapp.com/blog)
- [Support](https://developers.facebook.com/support/)
- [Console](https://developers.facebook.com/apps/)
- [GitHub Organization](https://github.com/WhatsApp)
- [Community](https://business.whatsapp.com/developers/developer-hub)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/whatsapp-cloud-api)
- [Security](https://www.whatsapp.com/security/WhatsApp-Security-Whitepaper.pdf)
- [Postman Collection](https://www.postman.com/meta/whatsapp-business-platform/overview) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Pricing](https://business.whatsapp.com/products/platform-pricing)
- [JSON-LD](json-ld/whatsapp-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/whatsapp-webhook-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Node.js  S D K](https://github.com/WhatsApp/WhatsApp-Nodejs-SDK)
- [A P I  Examples](https://github.com/fbsamples/whatsapp-api-examples)
- [Business  Messaging  Policy](https://business.whatsapp.com/policy)
- [Meta  Terms](https://www.whatsapp.com/legal/meta-terms-whatsapp-business)
- [F A Q](https://business.whatsapp.com/resources/faq)
- [Sandbox](https://business.whatsapp.com/developers/developer-hub)
- [Versioning](https://developers.facebook.com/docs/graph-api/guides/versioning)
- [Migration  Guide](https://developers.facebook.com/docs/whatsapp/cloud-api/migrate-to-cloud-api)
- [Rate Limits](https://developers.facebook.com/docs/whatsapp/cloud-api/overview#throughput)
- [Error Codes](https://developers.facebook.com/docs/whatsapp/cloud-api/support/error-codes)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
