# Citation Schema

```txt
https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/properties/citation
```

Dataset citation.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [metadata-schema.json\*](../out/metadata-schema.json "open original schema") |

## citation Type

`object` ([Citation](metadata-schema-defs-citation.md))

# citation Properties

| Property            | Type     | Required | Nullable       | Defined by                                                                                                                                                                                |
| :------------------ | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [title](#title)     | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-citation-properties-title.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Citation/properties/title")     |
| [authors](#authors) | `array`  | Required | cannot be null | [HOAMetadata](metadata-schema-defs-citation-properties-authors.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Citation/properties/authors") |
| [doi](#doi)         | Merged   | Required | cannot be null | [HOAMetadata](metadata-schema-defs-citation-properties-doi.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Citation/properties/doi")         |

## title

Citation title.

`title`

* is required

* Type: `string` ([Title](metadata-schema-defs-citation-properties-title.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-citation-properties-title.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Citation/properties/title")

### title Type

`string` ([Title](metadata-schema-defs-citation-properties-title.md))

## authors

Dataset authors.

`authors`

* is required

* Type: `string[]`

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-citation-properties-authors.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Citation/properties/authors")

### authors Type

`string[]`

## doi

Dataset DOI.

`doi`

* is required

* Type: merged type ([Doi](metadata-schema-defs-citation-properties-doi.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-citation-properties-doi.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Citation/properties/doi")

### doi Type

merged type ([Doi](metadata-schema-defs-citation-properties-doi.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-citation-properties-doi-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-citation-properties-doi-anyof-1.md "check type definition")
