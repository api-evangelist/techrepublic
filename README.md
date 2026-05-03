# TechRepublic (techrepublic)

TechRepublic is a leading IT and enterprise technology media site that provides IT professionals with news, analysis, tips, tutorials, best practices, and research on business technology. Covering topics including cloud computing, cybersecurity, artificial intelligence, enterprise software, hardware, and data management, TechRepublic serves technology decision-makers and practitioners across industries. The platform exposes content programmatically via WordPress REST API endpoints and standard RSS/Atom feeds across 150+ topic categories.

**URL:** [https://raw.githubusercontent.com/api-evangelist/techrepublic/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/techrepublic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Enterprise IT, Media, Technology News, Content, Publishing

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### TechRepublic RSS Feed

TechRepublic provides RSS/Atom feeds covering its full range of technology news and analysis across 150+ topic categories including AI, security, cloud, software, hardware, developer, data centers, mobility, and more. Standard RSS 2.0 and Atom feeds allow readers and developers to consume TechRepublic content programmatically using any standard feed reader or parsing library.

**Human URL:** [https://www.techrepublic.com/rssfeeds/](https://www.techrepublic.com/rssfeeds/)

#### Tags:

 - Content, Feed, News, RSS, Syndication

#### Properties

- [Documentation](https://www.techrepublic.com/rssfeeds/)
- [RSSFeed](https://www.techrepublic.com/rssfeeds/)

### TechRepublic WordPress REST API

TechRepublic exposes the standard WordPress REST API at `/wp-json/wp/v2`, providing JSON endpoints for accessing posts, pages, categories, tags, authors, media, and other content types. The API supports filtering, pagination, and full-text search across all TechRepublic technology news and analysis content.

**Human URL:** [https://developer.wordpress.org/rest-api/](https://developer.wordpress.org/rest-api/)

**Base URL:** https://www.techrepublic.com/wp-json/wp/v2

#### Tags:

 - Content, JSON, Media, Posts, Categories, REST, WordPress

#### Properties

- [Documentation](https://developer.wordpress.org/rest-api/)
- [OpenAPI](openapi/techrepublic-wordpress-rest-api-openapi.yml)
- [JSONSchema](json-schema/techrepublic-post-schema.json)
- [JSONSchema](json-schema/techrepublic-category-schema.json)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [techrepublic-wordpress-rest-api-openapi.yml](openapi/techrepublic-wordpress-rest-api-openapi.yml) | WordPress REST API v2 - posts, pages, categories, tags, authors, media |

### JSON Schemas

| File | Description |
|---|---|
| [techrepublic-post-schema.json](json-schema/techrepublic-post-schema.json) | Schema for TechRepublic post/article objects |
| [techrepublic-category-schema.json](json-schema/techrepublic-category-schema.json) | Schema for TechRepublic category/topic objects |

### JSON Structure

| File | Description |
|---|---|
| [techrepublic-post-structure.json](json-structure/techrepublic-post-structure.json) | Field-level documentation for post objects |

### JSON-LD Context

| File | Description |
|---|---|
| [techrepublic-context.jsonld](json-ld/techrepublic-context.jsonld) | Linked data context mapping WordPress terms to schema.org |

### Examples

| File | Description |
|---|---|
| [techrepublic-list-posts-example.json](examples/techrepublic-list-posts-example.json) | Example request/response for listing posts |
| [techrepublic-get-post-example.json](examples/techrepublic-get-post-example.json) | Example request/response for getting a post |
| [techrepublic-list-categories-example.json](examples/techrepublic-list-categories-example.json) | Example request/response for listing categories |

### Spectral Rules

| File | Description |
|---|---|
| [techrepublic-rules.yml](rules/techrepublic-rules.yml) | Spectral ruleset for TechRepublic API conventions |

### Naftiko Capabilities

| File | Description |
|---|---|
| [capabilities/content-discovery.yaml](capabilities/content-discovery.yaml) | Content discovery workflow - search articles, topics, authors (8 MCP tools) |
| [capabilities/shared/wordpress-rest-api.yaml](capabilities/shared/wordpress-rest-api.yaml) | Shared WordPress REST API consumed definition |

### Vocabulary

| File | Description |
|---|---|
| [techrepublic-vocabulary.yml](vocabulary/techrepublic-vocabulary.yml) | Domain vocabulary for TechRepublic content and technology terms |

## Common Properties

- [Website](https://www.techrepublic.com/)
- [About](https://www.techrepublic.com/about/)
- [Newsletter](https://www.techrepublic.com/newsletters/)
- [RSSFeeds](https://www.techrepublic.com/rssfeeds/)
- [Blog](https://www.techrepublic.com/topic/)
- [Advertising](https://www.techrepublic.com/advertise/)
- [Forum](https://www.techrepublic.com/forums/)
- [Resources](https://www.techrepublic.com/resource-library/)
- [LinkedIn](https://www.linkedin.com/company/techrepublic)
- [X](https://x.com/TechRepublic)
- [Facebook](https://www.facebook.com/TechRepublic/)
- [Instagram](https://www.instagram.com/techrepublic/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
