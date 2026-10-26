# TechRepublic (techrepublic)

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

TechRepublic is a leading IT and enterprise technology media site that provides IT professionals with news, analysis, tips, tutorials, best practices, and research on business technology. Covering topics including cloud computing, cybersecurity, artificial intelligence, enterprise software, hardware, and data management, TechRepublic serves technology decision-makers and practitioners across industries. The platform exposes its content programmatically via WordPress REST API endpoints and standard RSS/Atom feeds.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/techrepublic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/techrepublic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Enterprise IT
- Media
- Technology News
- Content
- Publishing

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### TechRepublic RSS Feed

TechRepublic provides RSS/Atom feeds covering its full range of technology news and analysis. Feeds are available for the main news stream and for over 150 individual topic categories including AI, security, cloud, software, hardware, developer, data centers, mobility, and more. Standard RSS 2.0 and Atom feeds allow readers and developers to consume TechRepublic content programmatically using any standard feed reader or parsing library. Topics span technology sectors, company coverage, geographic regions, and emerging technology areas.

- **Human URL:** [https://www.techrepublic.com/rssfeeds/](https://www.techrepublic.com/rssfeeds/)
- **Base URL:** `https://www.techrepublic.com`

#### Tags

- Content
- Feed
- News
- RSS
- Syndication

#### Properties

- [Documentation](https://www.techrepublic.com/rssfeeds/)
- [R S S Feed](https://www.techrepublic.com/rssfeeds/)
- [Postman Collection](collections/techrepublic-wordpress-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/techrepublic-wordpress-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TechRepublic WordPress REST API

TechRepublic is built on WordPress and exposes the standard WordPress REST API, providing JSON endpoints for accessing posts, pages, categories, tags, authors, media, and other content types. The API is available at the /wp-json/wp/v2/ base path and supports filtering, pagination, and searching across all TechRepublic content. Endpoints include posts, pages, categories, tags, media, users, comments, and taxonomies. Enables developers to integrate TechRepublic articles and metadata into their own applications and workflows.

- **Human URL:** [https://developer.wordpress.org/rest-api/](https://developer.wordpress.org/rest-api/)
- **Base URL:** `https://www.techrepublic.com/wp-json/wp/v2`

#### Tags

- Content
- JSON
- REST
- WordPress
- Posts
- Categories
- Media

#### Properties

- [Documentation](https://developer.wordpress.org/rest-api/)
- [OpenAPI](openapi/techrepublic-wordpress-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/techrepublic-wordpress-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/techrepublic-wordpress-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/techrepublic-post-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/techrepublic-category-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [Website](https://www.techrepublic.com/)
- [About](https://www.techrepublic.com/about/)
- [Newsletter](https://www.techrepublic.com/newsletters/)
- [R S S Feeds](https://www.techrepublic.com/rssfeeds/)
- [Blog](https://www.techrepublic.com/topic/)
- [Advertising](https://www.techrepublic.com/advertise/)
- [Forum](https://www.techrepublic.com/forums/)
- [Resources](https://www.techrepublic.com/resource-library/)
- [LinkedIn](https://www.linkedin.com/company/techrepublic)
- [X (Twitter)](https://x.com/TechRepublic)
- [Facebook](https://www.facebook.com/TechRepublic/)
- [Instagram](https://www.instagram.com/techrepublic/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
