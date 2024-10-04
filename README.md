# Human Organ Atlas metadata schemas

Metadata schemas for the Human Organ Atlas data.

> [!WARNING]
> The schema is still in draft status and subject to change without warning.

## Metadata location

The actual metadata are stored in two locations:

## Schema docs

### Main schema

- [HOAMetadata](./metadata-schema.md) – `http://yourdomain.com/schemas/myschema.json`

### Other Schemas

#### Objects

- [Donor](./metadata-schema-defs-donor.md "Donor data model") – `http://yourdomain.com/schemas/myschema.json#/$defs/Donor`

- [Proposal](./metadata-schema-defs-proposal.md) – `http://yourdomain.com/schemas/myschema.json#/$defs/Proposal`

- [PublicScanMetadata](./metadata-schema-defs-publicscanmetadata.md) – `http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata`

#### Arrays

- [Proposers](./metadata-schema-defs-proposal-properties-proposers.md "Proposal proposers") – `http://yourdomain.com/schemas/myschema.json#/$defs/Proposal/properties/proposers`

- [Shape](./metadata-schema-properties-shape.md "Shape of dataset") – `http://yourdomain.com/schemas/myschema.json#/properties/shape`

- [Untitled array in HOAMetadata](./metadata-schema-defs-publicscanmetadata-properties-filters-anyof-0.md) – `http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/filters/anyOf/0`
