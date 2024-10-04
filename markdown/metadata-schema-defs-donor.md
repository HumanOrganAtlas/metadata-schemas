# Donor Schema

```txt
http://yourdomain.com/schemas/myschema.json#/properties/donor
```

Donor data model.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :--------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [metadata-schema.json\*](../out/metadata-schema.json "open original schema") |

## donor Type

`object` ([Donor](metadata-schema-defs-donor.md))

# donor Properties

| Property                            | Type     | Required | Nullable       | Defined by                                                                                                                                                    |
| :---------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                           | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-id.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/id")                           |
| [age](#age)                         | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-age.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/age")                         |
| [sex](#sex)                         | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-sex.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/sex")                         |
| [weight](#weight)                   | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-weight.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/weight")                   |
| [height](#height)                   | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-height.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/height")                   |
| [cause_of_death](#cause_of_death)   | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/cause_of_death")   |
| [date_of_death](#date_of_death)     | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-date-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/date_of_death")     |
| [medical_history](#medical_history) | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-medical-history.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/medical_history") |
| [diabetes](#diabetes)               | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-diabetes.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/diabetes")               |
| [hypertension](#hypertension)       | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-hypertension.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/hypertension")       |
| [smoker](#smoker)                   | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-smoker.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/smoker")                   |

## id

`id`

- is required

- Type: `string` ([Id](metadata-schema-defs-donor-properties-id.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-id.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/id")

### id Type

`string` ([Id](metadata-schema-defs-donor-properties-id.md))

## age

Age at death.

`age`

- is optional

- Type: merged type ([Age](metadata-schema-defs-donor-properties-age.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-age.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/age")

### age Type

merged type ([Age](metadata-schema-defs-donor-properties-age.md))

any of

- [Untitled integer in HOAMetadata](metadata-schema-defs-donor-properties-age-anyof-0.md "check type definition")

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-age-anyof-1.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-age-anyof-2.md "check type definition")

## sex

`sex`

- is optional

- Type: merged type ([Sex](metadata-schema-defs-donor-properties-sex.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-sex.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/sex")

### sex Type

merged type ([Sex](metadata-schema-defs-donor-properties-sex.md))

any of

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-sex-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-sex-anyof-1.md "check type definition")

## weight

Weight in kg at death.

`weight`

- is optional

- Type: merged type ([Weight](metadata-schema-defs-donor-properties-weight.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-weight.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/weight")

### weight Type

merged type ([Weight](metadata-schema-defs-donor-properties-weight.md))

any of

- [Untitled number in HOAMetadata](metadata-schema-defs-donor-properties-weight-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-weight-anyof-1.md "check type definition")

## height

Height in cm at death.

`height`

- is optional

- Type: merged type ([Height](metadata-schema-defs-donor-properties-height.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-height.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/height")

### height Type

merged type ([Height](metadata-schema-defs-donor-properties-height.md))

any of

- [Untitled number in HOAMetadata](metadata-schema-defs-donor-properties-height-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-height-anyof-1.md "check type definition")

## cause_of_death

Cause of death.

`cause_of_death`

- is optional

- Type: merged type ([Cause Of Death](metadata-schema-defs-donor-properties-cause-of-death.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/cause_of_death")

### cause_of_death Type

merged type ([Cause Of Death](metadata-schema-defs-donor-properties-cause-of-death.md))

any of

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death-anyof-1.md "check type definition")

## date_of_death

Date of death.

`date_of_death`

- is optional

- Type: merged type ([Date Of Death](metadata-schema-defs-donor-properties-date-of-death.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-date-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/date_of_death")

### date_of_death Type

merged type ([Date Of Death](metadata-schema-defs-donor-properties-date-of-death.md))

any of

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-date-of-death-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-date-of-death-anyof-1.md "check type definition")

## medical_history

Medical history.

`medical_history`

- is optional

- Type: merged type ([Medical History](metadata-schema-defs-donor-properties-medical-history.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-medical-history.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/medical_history")

### medical_history Type

merged type ([Medical History](metadata-schema-defs-donor-properties-medical-history.md))

any of

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-medical-history-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-medical-history-anyof-1.md "check type definition")

## diabetes

Diabetes history.

`diabetes`

- is optional

- Type: merged type ([Diabetes](metadata-schema-defs-donor-properties-diabetes.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-diabetes.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/diabetes")

### diabetes Type

merged type ([Diabetes](metadata-schema-defs-donor-properties-diabetes.md))

any of

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-diabetes-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-diabetes-anyof-1.md "check type definition")

## hypertension

Hypertension history.

`hypertension`

- is optional

- Type: merged type ([Hypertension](metadata-schema-defs-donor-properties-hypertension.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-hypertension.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/hypertension")

### hypertension Type

merged type ([Hypertension](metadata-schema-defs-donor-properties-hypertension.md))

any of

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-hypertension-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-hypertension-anyof-1.md "check type definition")

## smoker

Smoking history.

`smoker`

- is optional

- Type: merged type ([Smoker](metadata-schema-defs-donor-properties-smoker.md))

- cannot be null

- defined in: [HOAMetadata](metadata-schema-defs-donor-properties-smoker.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/smoker")

### smoker Type

merged type ([Smoker](metadata-schema-defs-donor-properties-smoker.md))

any of

- [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-smoker-anyof-0.md "check type definition")

- [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-smoker-anyof-1.md "check type definition")
