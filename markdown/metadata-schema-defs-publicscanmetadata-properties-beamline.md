# Beamline Schema

```txt
http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/beamline
```

ESRF beamline where scan was performed.

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [metadata-schema.json\*](../out/metadata-schema.json "open original schema") |

## beamline Type

`string` ([Beamline](metadata-schema-defs-publicscanmetadata-properties-beamline.md))

## beamline Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"BM05"` |             |
| `"BM18"` |             |