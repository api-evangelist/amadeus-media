# Amadeus Media (amadeus-media)
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
