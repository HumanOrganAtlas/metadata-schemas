# Proposal Schema

```txt
https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/properties/proposal
```

Proposal information

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [metadata-schema.json\*](../out/metadata-schema.json "open original schema") |

## proposal Type

`object` ([Proposal](metadata-schema-defs-proposal.md))

# proposal Properties

| Property                             | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                |
| :----------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [proposal\_number](#proposal_number) | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-proposal-properties-proposal-number.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Proposal/properties/proposal_number") |
| [title](#title)                      | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-proposal-properties-title.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Proposal/properties/title")                     |
| [proposers](#proposers)              | `array`  | Required | cannot be null | [HOAMetadata](metadata-schema-defs-proposal-properties-proposers.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Proposal/properties/proposers")             |

## proposal\_number

Proposal number.

`proposal_number`

* is required

* Type: `string` ([Proposal Number](metadata-schema-defs-proposal-properties-proposal-number.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-proposal-properties-proposal-number.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Proposal/properties/proposal_number")

### proposal\_number Type

`string` ([Proposal Number](metadata-schema-defs-proposal-properties-proposal-number.md))

## title

Proposal title.

`title`

* is required

* Type: `string` ([Title](metadata-schema-defs-proposal-properties-title.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-proposal-properties-title.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Proposal/properties/title")

### title Type

`string` ([Title](metadata-schema-defs-proposal-properties-title.md))

## proposers

Proposal proposers.

`proposers`

* is required

* Type: `string[]`

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-proposal-properties-proposers.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Proposal/properties/proposers")

### proposers Type

`string[]`
