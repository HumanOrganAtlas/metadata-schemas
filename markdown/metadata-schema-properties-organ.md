# Organ Schema

```txt
http://yourdomain.com/schemas/myschema.json#/properties/organ
```

Organ name

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [metadata-schema.json\*](../out/metadata-schema.json "open original schema") |

## organ Type

`string` ([Organ](metadata-schema-properties-organ.md))

## organ Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value             | Explanation |
| :---------------- | :---------- |
| `"brain"`         |             |
| `"breast"`        |             |
| `"colon"`         |             |
| `"eye"`           |             |
| `"kidney"`        |             |
| `"liver"`         |             |
| `"lung"`          |             |
| `"heart"`         |             |
| `"oesophagus"`    |             |
| `"spinalCord"`    |             |
| `"spleen"`        |             |
| `"heart+lungs"`   |             |
| `"pancreas"`      |             |
| `"placenta"`      |             |
| `"prostate"`      |             |
| `"testis"`        |             |
| `"uterus"`        |             |
| `"thoracicBlock"` |             |
| `"soleus"`        |             |
