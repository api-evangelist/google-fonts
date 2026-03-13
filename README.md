# Google Fonts Developer API

The Google Fonts Developer API provides programmatic access to the metadata for all font families served by Google Fonts. Developers can query for available font families, retrieve details about variants, subsets, and categories, access font file URLs, and work with variable font axis metadata. The API supports sorting and filtering to help applications discover and integrate web fonts.

## Artifacts

- **APIs.yml** - Machine-readable API metadata following the APIs.json specification.
- **OpenAPI** (`openapi/openapi.yml`) - OpenAPI 3.1.0 specification describing the Fonts Developer API endpoint, parameters, and response schemas.
- **JSON Schema** (`json-schema/google-fonts.json`) - JSON Schema (draft 2020-12) defining response objects for the Fonts API.
- **JSON-LD** (`json-ld/google-fonts.jsonld`) - JSON-LD context mapping Fonts API terms to schema.org and API-specific vocabularies.

## Key Endpoints

| Method | Path | Description |
|--------|------|-------------|
| GET | `/webfonts/v1/webfonts` | List all available font families with metadata |

## Resources

- [Developer API Documentation](https://developers.google.com/fonts/docs/developer_api)
- [Getting Started](https://developers.google.com/fonts/docs/getting_started)
- [Google Fonts](https://fonts.google.com)

## Maintainer

Kin Lane - kin@apievangelist.com
