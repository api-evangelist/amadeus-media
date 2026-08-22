# Amadeus Media (amadeus-media)

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

Amadeus Media provides APIs and data services for accessing travel-related media content, including hotel images, property descriptions, multimedia assets, and rich content for hospitality and travel applications. Amadeus partners with trusted content providers such as Leonardo to deliver high-quality hotel media through enterprise-grade APIs used by online travel agencies, metasearch platforms, and hospitality technology providers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Content, Hotels, Images, Media, Travel

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Hotel Content API
The Amadeus Hotel Content API provides detailed property information including descriptions, amenities, facilities, contact details, and media assets such as images and multimedia content for hotels in the Amadeus inventory. Available through Amadeus Enterprise APIs, this API enables travel platforms to display rich hotel profiles with photos, room images, and property descriptions.

**Human URL:** [https://developers.amadeus.com/enterprise/category/hotel/api/content](https://developers.amadeus.com/enterprise/category/hotel/api/content)

#### Tags:

 - Content, Hotels, Images, Media, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/enterprise/category/hotel/api/content)
- [OpenAPI](openapi/amadeus-media-hotel-content-openapi.yaml)
- [JSONSchema](json-schema/hotel-content-hotel-content-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-content-response-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-media-response-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-media-item-schema.json)
- [JSONSchema](json-schema/hotel-content-media-asset-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-basic-info-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-description-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-contact-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-address-schema.json)
- [JSONSchema](json-schema/hotel-content-geo-code-schema.json)
- [JSONSchema](json-schema/hotel-content-hotel-media-data-schema.json)
- [JSONStructure](json-structure/hotel-content-hotel-content-structure.json)
- [JSONStructure](json-structure/hotel-content-hotel-content-response-structure.json)
- [JSONStructure](json-structure/hotel-content-hotel-media-response-structure.json)
- [JSON-LD](json-ld/amadeus-hotel-content-context.jsonld)

### Hotel List API
The Amadeus Hotel List API returns hotel property data including name, address, geographic coordinates, and time zone for each hotel bookable through Amadeus. This API is the starting point for building hotel search experiences and retrieving the property identifiers needed to fetch hotel media and offers.

**Human URL:** [https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)

#### Tags:

 - Content, Hotels, Listings, Travel

#### Properties

- [Documentation](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list)
- [APIReference](https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-list/api-reference)
- [OpenAPI](openapi/amadeus-media-hotel-list-openapi.yaml)
- [JSONSchema](json-schema/hotel-list-hotel-schema.json)
- [JSONSchema](json-schema/hotel-list-hotel-search-response-schema.json)
- [JSONStructure](json-structure/hotel-list-hotel-structure.json)
- [JSONStructure](json-structure/hotel-list-hotel-search-response-structure.json)
- [JSON-LD](json-ld/amadeus-hotel-list-context.jsonld)

## Common Properties

- [Portal](https://developers.amadeus.com/)
- [GettingStarted](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/)
- [Authentication](https://developers.amadeus.com/self-service/apis-docs/guides/authorization-262)
- [SignUp](https://developers.amadeus.com/register)
- [Pricing](https://developers.amadeus.com/pricing)
- [Blog](https://developers.amadeus.com/blog)
- [FAQ](https://developers.amadeus.com/self-service/apis-docs/guides/developer-guides/faq/)
- [Support](https://developers.amadeus.com/support)
- [TermsOfService](https://developers.amadeus.com/legal/terms-and-conditions)
- [PrivacyPolicy](https://developers.amadeus.com/legal/privacy-policy)
- [GitHubOrganization](https://github.com/amadeus4dev)
- [Python SDK](https://github.com/amadeus4dev/amadeus-python)
- [Node.js SDK](https://github.com/amadeus4dev/amadeus-node)
- [Java SDK](https://github.com/amadeus4dev/amadeus-java)
- [StatusPage](https://developers.amadeus.com/status)

## Features

| Name | Description |
|------|-------------|
| Hotel Property Images | Access high-quality images and multimedia assets for hotel properties through the Enterprise Hotel Content API and trusted content partners like Leonardo. |
| Rich Property Descriptions | Retrieve detailed hotel descriptions, amenity lists, facility information, and property attributes for comprehensive hotel profiles. |
| Geolocation Data | Access geographic coordinates, addresses, and time zones for over 770,000 hotels in the Amadeus global inventory. |
| Enterprise Content Access | Enterprise API tier provides access to detailed hotel content including media that is not available in self-service APIs due to licensing constraints. |
| Multi-Language Support | Hotel content and descriptions available in multiple languages to support international travel applications and global markets. |

## Use Cases

| Name | Description |
|------|-------------|
| Online Travel Agency Hotel Listings | Power hotel search pages with rich property photos, descriptions, and amenity information sourced directly from Amadeus content services. |
| Metasearch Platform Integration | Integrate Amadeus hotel content into metasearch engines to display property images and descriptions alongside rate comparisons. |
| Hotel Booking Engine Content | Enhance hotel booking flows with compelling property imagery and detailed descriptions to improve conversion rates. |
| Travel App Media Display | Display hotel photos and media in mobile travel apps to give users visual context when browsing and booking accommodation. |
| Corporate Travel Platform | Provide hotel content and imagery in corporate travel management systems to help business travelers make informed accommodation decisions. |

## Integrations

| Name | Description |
|------|-------------|
| Leonardo (Hotel Images) | Amadeus recommends Leonardo as the trusted data provider for hotel images and property media, offering a comprehensive library of hotel photography. |
| Google Places API | Developers can supplement Amadeus hotel data with Google Places API to retrieve hotel images and business information for properties in the Amadeus inventory. |
| Amadeus Hotel Search API | Combine with Amadeus Hotel Search to display media alongside hotel offers and pricing for a complete shopping experience. |
| Amadeus Hotel Booking API | Integrate hotel content with the booking flow to present property images and descriptions before and during the reservation process. |
| Amadeus Hotel Ratings API | Pair hotel media with sentiment-based ratings to create compelling hotel profile pages that combine visual content with review insights. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amadeus Hotel Content OpenAPI](openapi/amadeus-media-hotel-content-openapi.yaml)
- [Amadeus Hotel List OpenAPI](openapi/amadeus-media-hotel-list-openapi.yaml)

### JSON Schema

- [hotel-content-hotel-content-schema.json](json-schema/hotel-content-hotel-content-schema.json)
- [hotel-content-hotel-content-response-schema.json](json-schema/hotel-content-hotel-content-response-schema.json)
- [hotel-content-hotel-media-response-schema.json](json-schema/hotel-content-hotel-media-response-schema.json)
- [hotel-content-hotel-media-item-schema.json](json-schema/hotel-content-hotel-media-item-schema.json)
- [hotel-content-media-asset-schema.json](json-schema/hotel-content-media-asset-schema.json)
- [hotel-content-hotel-basic-info-schema.json](json-schema/hotel-content-hotel-basic-info-schema.json)
- [hotel-content-hotel-description-schema.json](json-schema/hotel-content-hotel-description-schema.json)
- [hotel-content-hotel-contact-schema.json](json-schema/hotel-content-hotel-contact-schema.json)
- [hotel-content-hotel-address-schema.json](json-schema/hotel-content-hotel-address-schema.json)
- [hotel-content-geo-code-schema.json](json-schema/hotel-content-geo-code-schema.json)
- [hotel-content-hotel-media-data-schema.json](json-schema/hotel-content-hotel-media-data-schema.json)
- [hotel-list-hotel-schema.json](json-schema/hotel-list-hotel-schema.json)
- [hotel-list-hotel-search-response-schema.json](json-schema/hotel-list-hotel-search-response-schema.json)

### JSON Structure

- [hotel-content-hotel-content-structure.json](json-structure/hotel-content-hotel-content-structure.json)
- [hotel-content-hotel-content-response-structure.json](json-structure/hotel-content-hotel-content-response-structure.json)
- [hotel-content-hotel-media-response-structure.json](json-structure/hotel-content-hotel-media-response-structure.json)
- [hotel-list-hotel-structure.json](json-structure/hotel-list-hotel-structure.json)
- [hotel-list-hotel-search-response-structure.json](json-structure/hotel-list-hotel-search-response-structure.json)

### JSON-LD

- [amadeus-hotel-content-context.jsonld](json-ld/amadeus-hotel-content-context.jsonld)
- [amadeus-hotel-list-context.jsonld](json-ld/amadeus-hotel-list-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Hotel Content API](capabilities/shared/hotel-content.yaml) — 2 operations for hotel content and media retrieval
- [Hotel List API](capabilities/shared/hotel-list.yaml) — 3 operations for hotel discovery by city, geocode, and IDs

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Hotel Media Discovery](capabilities/hotel-media-discovery.yaml) | Hotel List API, Hotel Content API | 4 | Travel Platform Developer, OTA Content Team |

## Vocabulary

- [Amadeus Media Vocabulary](vocabulary/amadeus-media-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amadeus Media Spectral Rules](rules/amadeus-media-spectral-rules.yml) — 30 rules across 8 categories enforcing Amadeus API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
