# Registration Schema

```txt
https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/properties/registration/anyOf/0
```

A set of registration parameters mapping array coordinates in
source\_dataset to target\_dataset.

The transform is specified as

1. a rotation anticlockwise about the z-axis
2. A isotropic scaling
3. A translation

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [metadata-schema.json\*](../out/metadata-schema.json "open original schema") |

## 0 Type

`object` ([Registration](metadata-schema-defs-registration.md))

# 0 Properties

| Property                           | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :--------------------------------- | :------- | :------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [source\_dataset](#source_dataset) | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-registration-properties-source-dataset.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/source_dataset") |
| [target\_dataset](#target_dataset) | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-registration-properties-target-dataset.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/target_dataset") |
| [translation](#translation)        | `array`  | Required | cannot be null | [HOAMetadata](metadata-schema-defs-registration-properties-translation.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/translation")       |
| [rotation](#rotation)              | `number` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-registration-properties-rotation.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/rotation")             |
| [scale](#scale)                    | `number` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-registration-properties-scale.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/scale")                   |

## source\_dataset

Dataset that is registered

`source_dataset`

* is required

* Type: `string` ([Source Dataset](metadata-schema-defs-registration-properties-source-dataset.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-registration-properties-source-dataset.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/source_dataset")

### source\_dataset Type

`string` ([Source Dataset](metadata-schema-defs-registration-properties-source-dataset.md))

## target\_dataset

Dataset that source\_dataset is registered to.

`target_dataset`

* is required

* Type: `string` ([Target Dataset](metadata-schema-defs-registration-properties-target-dataset.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-registration-properties-target-dataset.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/target_dataset")

### target\_dataset Type

`string` ([Target Dataset](metadata-schema-defs-registration-properties-target-dataset.md))

## translation

Translation

`translation`

* is required

* Type: `array` ([Translation](metadata-schema-defs-registration-properties-translation.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-registration-properties-translation.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/translation")

### translation Type

`array` ([Translation](metadata-schema-defs-registration-properties-translation.md))

### translation Constraints

**maximum number of items**: the maximum number of items for this array is: `3`

**minimum number of items**: the minimum number of items for this array is: `3`

## rotation

Rotation in degrees about z-axis

`rotation`

* is required

* Type: `number` ([Rotation](metadata-schema-defs-registration-properties-rotation.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-registration-properties-rotation.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/rotation")

### rotation Type

`number` ([Rotation](metadata-schema-defs-registration-properties-rotation.md))

## scale

Isotropic scaling factor

`scale`

* is required

* Type: `number` ([Scale](metadata-schema-defs-registration-properties-scale.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-registration-properties-scale.md "https://github.com/HumanOrganAtlas/metadata-schemas/schemas/metadata-schemas.json#/$defs/Registration/properties/scale")

### scale Type

`number` ([Scale](metadata-schema-defs-registration-properties-scale.md))
