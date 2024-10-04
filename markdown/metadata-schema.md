# HOAMetadata Schema

```txt
http://yourdomain.com/schemas/myschema.json
```



| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [metadata-schema.json](../out/metadata-schema.json "open original schema") |

## HOAMetadata Type

`object` ([HOAMetadata](metadata-schema.md))

# HOAMetadata Properties

| Property                         | Type     | Required | Nullable       | Defined by                                                                                                                         |
| :------------------------------- | :------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)                    | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-properties-name.md "http://yourdomain.com/schemas/myschema.json#/properties/name")                   |
| [organ](#organ)                  | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-properties-organ.md "http://yourdomain.com/schemas/myschema.json#/properties/organ")                 |
| [organ\_context](#organ_context) | Merged   | Required | cannot be null | [HOAMetadata](metadata-schema-properties-organ-context.md "http://yourdomain.com/schemas/myschema.json#/properties/organ_context") |
| [scan\_type](#scan_type)         | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-properties-scan-type.md "http://yourdomain.com/schemas/myschema.json#/properties/scan_type")         |
| [roi](#roi)                      | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-properties-roi.md "http://yourdomain.com/schemas/myschema.json#/properties/roi")                     |
| [resolution\_um](#resolution_um) | `number` | Required | cannot be null | [HOAMetadata](metadata-schema-properties-resolution-um.md "http://yourdomain.com/schemas/myschema.json#/properties/resolution_um") |
| [shape](#shape)                  | `array`  | Required | cannot be null | [HOAMetadata](metadata-schema-properties-shape.md "http://yourdomain.com/schemas/myschema.json#/properties/shape")                 |
| [donor](#donor)                  | `object` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-donor.md "http://yourdomain.com/schemas/myschema.json#/properties/donor")                       |
| [scan](#scan)                    | `object` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata.md "http://yourdomain.com/schemas/myschema.json#/properties/scan")           |
| [proposal](#proposal)            | `object` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-proposal.md "http://yourdomain.com/schemas/myschema.json#/properties/proposal")                 |

## name

Unique name for dataset.

`name`

* is required

* Type: `string` ([Name](metadata-schema-properties-name.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-properties-name.md "http://yourdomain.com/schemas/myschema.json#/properties/name")

### name Type

`string` ([Name](metadata-schema-properties-name.md))

## organ

Organ name

`organ`

* is required

* Type: `string` ([Organ](metadata-schema-properties-organ.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-properties-organ.md "http://yourdomain.com/schemas/myschema.json#/properties/organ")

### organ Type

`string` ([Organ](metadata-schema-properties-organ.md))

### organ Constraints

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

## organ\_context

Context for location of the dataset within the whole organ.

`organ_context`

* is required

* Type: merged type ([Organ Context](metadata-schema-properties-organ-context.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-properties-organ-context.md "http://yourdomain.com/schemas/myschema.json#/properties/organ_context")

### organ\_context Type

merged type ([Organ Context](metadata-schema-properties-organ-context.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-properties-organ-context-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-properties-organ-context-anyof-1.md "check type definition")

## scan\_type



`scan_type`

* is required

* Type: `string` ([Scan Type](metadata-schema-properties-scan-type.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-properties-scan-type.md "http://yourdomain.com/schemas/myschema.json#/properties/scan_type")

### scan\_type Type

`string` ([Scan Type](metadata-schema-properties-scan-type.md))

### scan\_type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value        | Explanation |
| :----------- | :---------- |
| `"overview"` |             |
| `"zoom"`     |             |

## roi

Region of interest name for dataset.

`roi`

* is required

* Type: `string` ([Roi](metadata-schema-properties-roi.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-properties-roi.md "http://yourdomain.com/schemas/myschema.json#/properties/roi")

### roi Type

`string` ([Roi](metadata-schema-properties-roi.md))

## resolution\_um

Isotropic voxel size in micrometers.

`resolution_um`

* is required

* Type: `number` ([Resolution Um](metadata-schema-properties-resolution-um.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-properties-resolution-um.md "http://yourdomain.com/schemas/myschema.json#/properties/resolution_um")

### resolution\_um Type

`number` ([Resolution Um](metadata-schema-properties-resolution-um.md))

## shape

Shape of dataset

`shape`

* is required

* Type: `array` ([Shape](metadata-schema-properties-shape.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-properties-shape.md "http://yourdomain.com/schemas/myschema.json#/properties/shape")

### shape Type

`array` ([Shape](metadata-schema-properties-shape.md))

### shape Constraints

**maximum number of items**: the maximum number of items for this array is: `3`

**minimum number of items**: the minimum number of items for this array is: `3`

## donor

Donor data model.

`donor`

* is required

* Type: `object` ([Donor](metadata-schema-defs-donor.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor.md "http://yourdomain.com/schemas/myschema.json#/properties/donor")

### donor Type

`object` ([Donor](metadata-schema-defs-donor.md))

## scan

Scan metadata

`scan`

* is required

* Type: `object` ([PublicScanMetadata](metadata-schema-defs-publicscanmetadata.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata.md "http://yourdomain.com/schemas/myschema.json#/properties/scan")

### scan Type

`object` ([PublicScanMetadata](metadata-schema-defs-publicscanmetadata.md))

## proposal

Proposal information

`proposal`

* is required

* Type: `object` ([Proposal](metadata-schema-defs-proposal.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-proposal.md "http://yourdomain.com/schemas/myschema.json#/properties/proposal")

### proposal Type

`object` ([Proposal](metadata-schema-defs-proposal.md))

# HOAMetadata Definitions

## Definitions group Donor

Reference this group by using

```json
{"$ref":"http://yourdomain.com/schemas/myschema.json#/$defs/Donor"}
```

| Property                             | Type     | Required | Nullable       | Defined by                                                                                                                                                    |
| :----------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id)                            | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-id.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/id")                           |
| [age](#age)                          | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-age.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/age")                         |
| [sex](#sex)                          | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-sex.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/sex")                         |
| [weight](#weight)                    | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-weight.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/weight")                   |
| [height](#height)                    | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-height.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/height")                   |
| [cause\_of\_death](#cause_of_death)  | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/cause_of_death")   |
| [date\_of\_death](#date_of_death)    | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-date-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/date_of_death")     |
| [medical\_history](#medical_history) | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-medical-history.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/medical_history") |
| [diabetes](#diabetes)                | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-diabetes.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/diabetes")               |
| [hypertension](#hypertension)        | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-hypertension.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/hypertension")       |
| [smoker](#smoker)                    | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-donor-properties-smoker.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/smoker")                   |

### id



`id`

* is required

* Type: `string` ([Id](metadata-schema-defs-donor-properties-id.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-id.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/id")

#### id Type

`string` ([Id](metadata-schema-defs-donor-properties-id.md))

### age

Age at death.

`age`

* is optional

* Type: merged type ([Age](metadata-schema-defs-donor-properties-age.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-age.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/age")

#### age Type

merged type ([Age](metadata-schema-defs-donor-properties-age.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-donor-properties-age-anyof-0.md "check type definition")

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-age-anyof-1.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-age-anyof-2.md "check type definition")

### sex



`sex`

* is optional

* Type: merged type ([Sex](metadata-schema-defs-donor-properties-sex.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-sex.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/sex")

#### sex Type

merged type ([Sex](metadata-schema-defs-donor-properties-sex.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-sex-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-sex-anyof-1.md "check type definition")

### weight

Weight in kg at death.

`weight`

* is optional

* Type: merged type ([Weight](metadata-schema-defs-donor-properties-weight.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-weight.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/weight")

#### weight Type

merged type ([Weight](metadata-schema-defs-donor-properties-weight.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-donor-properties-weight-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-weight-anyof-1.md "check type definition")

### height

Height in cm at death.

`height`

* is optional

* Type: merged type ([Height](metadata-schema-defs-donor-properties-height.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-height.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/height")

#### height Type

merged type ([Height](metadata-schema-defs-donor-properties-height.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-donor-properties-height-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-height-anyof-1.md "check type definition")

### cause\_of\_death

Cause of death.

`cause_of_death`

* is optional

* Type: merged type ([Cause Of Death](metadata-schema-defs-donor-properties-cause-of-death.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/cause_of_death")

#### cause\_of\_death Type

merged type ([Cause Of Death](metadata-schema-defs-donor-properties-cause-of-death.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-cause-of-death-anyof-1.md "check type definition")

### date\_of\_death

Date of death.

`date_of_death`

* is optional

* Type: merged type ([Date Of Death](metadata-schema-defs-donor-properties-date-of-death.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-date-of-death.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/date_of_death")

#### date\_of\_death Type

merged type ([Date Of Death](metadata-schema-defs-donor-properties-date-of-death.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-date-of-death-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-date-of-death-anyof-1.md "check type definition")

### medical\_history

Medical history.

`medical_history`

* is optional

* Type: merged type ([Medical History](metadata-schema-defs-donor-properties-medical-history.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-medical-history.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/medical_history")

#### medical\_history Type

merged type ([Medical History](metadata-schema-defs-donor-properties-medical-history.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-medical-history-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-medical-history-anyof-1.md "check type definition")

### diabetes

Diabetes history.

`diabetes`

* is optional

* Type: merged type ([Diabetes](metadata-schema-defs-donor-properties-diabetes.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-diabetes.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/diabetes")

#### diabetes Type

merged type ([Diabetes](metadata-schema-defs-donor-properties-diabetes.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-diabetes-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-diabetes-anyof-1.md "check type definition")

### hypertension

Hypertension history.

`hypertension`

* is optional

* Type: merged type ([Hypertension](metadata-schema-defs-donor-properties-hypertension.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-hypertension.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/hypertension")

#### hypertension Type

merged type ([Hypertension](metadata-schema-defs-donor-properties-hypertension.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-hypertension-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-hypertension-anyof-1.md "check type definition")

### smoker

Smoking history.

`smoker`

* is optional

* Type: merged type ([Smoker](metadata-schema-defs-donor-properties-smoker.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-donor-properties-smoker.md "http://yourdomain.com/schemas/myschema.json#/$defs/Donor/properties/smoker")

#### smoker Type

merged type ([Smoker](metadata-schema-defs-donor-properties-smoker.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-donor-properties-smoker-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-donor-properties-smoker-anyof-1.md "check type definition")

## Definitions group Proposal

Reference this group by using

```json
{"$ref":"http://yourdomain.com/schemas/myschema.json#/$defs/Proposal"}
```

| Property                             | Type     | Required | Nullable       | Defined by                                                                                                                                                          |
| :----------------------------------- | :------- | :------- | :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [proposal\_number](#proposal_number) | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-proposal-properties-proposal-number.md "http://yourdomain.com/schemas/myschema.json#/$defs/Proposal/properties/proposal_number") |
| [title](#title)                      | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-proposal-properties-title.md "http://yourdomain.com/schemas/myschema.json#/$defs/Proposal/properties/title")                     |
| [proposers](#proposers)              | `array`  | Required | cannot be null | [HOAMetadata](metadata-schema-defs-proposal-properties-proposers.md "http://yourdomain.com/schemas/myschema.json#/$defs/Proposal/properties/proposers")             |

### proposal\_number

Proposal number.

`proposal_number`

* is required

* Type: `string` ([Proposal Number](metadata-schema-defs-proposal-properties-proposal-number.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-proposal-properties-proposal-number.md "http://yourdomain.com/schemas/myschema.json#/$defs/Proposal/properties/proposal_number")

#### proposal\_number Type

`string` ([Proposal Number](metadata-schema-defs-proposal-properties-proposal-number.md))

### title

Proposal title.

`title`

* is required

* Type: `string` ([Title](metadata-schema-defs-proposal-properties-title.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-proposal-properties-title.md "http://yourdomain.com/schemas/myschema.json#/$defs/Proposal/properties/title")

#### title Type

`string` ([Title](metadata-schema-defs-proposal-properties-title.md))

### proposers

Proposal proposers.

`proposers`

* is required

* Type: `string[]`

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-proposal-properties-proposers.md "http://yourdomain.com/schemas/myschema.json#/$defs/Proposal/properties/proposers")

#### proposers Type

`string[]`

## Definitions group PublicScanMetadata

Reference this group by using

```json
{"$ref":"http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata"}
```

| Property                                                  | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                  |
| :-------------------------------------------------------- | :------- | :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [dataset\_name](#dataset_name)                            | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-dataset-name.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/dataset_name")                           |
| [date](#date)                                             | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-date.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/date")                                           |
| [beamline](#beamline)                                     | `string` | Required | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-beamline.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/beamline")                                   |
| [energy](#energy)                                         | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-energy.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/energy")                                       |
| [current\_start](#current_start)                          | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-current-start.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/current_start")                         |
| [filling\_mode](#filling_mode)                            | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filling-mode.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/filling_mode")                           |
| [n\_projections](#n_projections)                          | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-projections.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_projections")                         |
| [n\_ref](#n_ref)                                          | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-ref.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_ref")                                         |
| [n\_dark](#n_dark)                                        | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-dark.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_dark")                                       |
| [latency\_time](#latency_time)                            | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-latency-time.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/latency_time")                           |
| [exposure\_time](#exposure_time)                          | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-exposure-time.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/exposure_time")                         |
| [accumulation\_n\_frames](#accumulation_n_frames)         | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-accumulation-n-frames.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/accumulation_n_frames")         |
| [scan\_type](#scan_type-1)                                | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-type.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scan_type")                                 |
| [scan\_range](#scan_range)                                | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-range.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scan_range")                               |
| [n\_scans](#n_scans)                                      | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-scans.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_scans")                                     |
| [acquisition](#acquisition)                               | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-acquisition.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/acquisition")                             |
| [half\_acquisition\_value](#half_acquisition_value)       | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-half-acquisition-value.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/half_acquisition_value")       |
| [quarter\_acquisition\_value](#quarter_acquisition_value) | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-quarter-acquisition-value.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/quarter_acquisition_value") |
| [z\_step](#z_step)                                        | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-z-step.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/z_step")                                       |
| [scan\_time](#scan_time)                                  | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-time.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scan_time")                                 |
| [filters](#filters)                                       | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filters.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/filters")                                     |
| [scintillator](#scintillator)                             | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scintillator.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scintillator")                           |
| [optic](#optic)                                           | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-optic.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/optic")                                         |
| [distance\_sample\_detector](#distance_sample_detector)   | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-distance-sample-detector.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/distance_sample_detector")   |
| [sensor\_name](#sensor_name)                              | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-name.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_name")                             |
| [sensor\_mode](#sensor_mode)                              | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-mode.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_mode")                             |
| [sensor\_magnification](#sensor_magnification)            | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-magnification.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_magnification")           |
| [sensor\_roi\_x\_size](#sensor_roi_x_size)                | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-x-size.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_roi_x_size")                 |
| [sensor\_roi\_y\_size](#sensor_roi_y_size)                | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-y-size.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_roi_y_size")                 |
| [pixel\_size](#pixel_size)                                | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-pixel-size.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/pixel_size")                               |
| [xray\_magnification](#xray_magnification)                | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-xray-magnification.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/xray_magnification")               |
| [proposal](#proposal-1)                                   | Merged   | Optional | cannot be null | [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-proposal.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/proposal")                                   |

### dataset\_name



`dataset_name`

* is required

* Type: `string` ([Dataset Name](metadata-schema-defs-publicscanmetadata-properties-dataset-name.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-dataset-name.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/dataset_name")

#### dataset\_name Type

`string` ([Dataset Name](metadata-schema-defs-publicscanmetadata-properties-dataset-name.md))

### date

Date when the scan was performed.

`date`

* is optional

* Type: merged type ([Date](metadata-schema-defs-publicscanmetadata-properties-date.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-date.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/date")

#### date Type

merged type ([Date](metadata-schema-defs-publicscanmetadata-properties-date.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-date-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-date-anyof-1.md "check type definition")

### beamline

ESRF beamline where scan was performed.

`beamline`

* is required

* Type: `string` ([Beamline](metadata-schema-defs-publicscanmetadata-properties-beamline.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-beamline.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/beamline")

#### beamline Type

`string` ([Beamline](metadata-schema-defs-publicscanmetadata-properties-beamline.md))

#### beamline Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | :---------- |
| `"BM05"` |             |
| `"BM18"` |             |

### energy

Energy used during the scan, measured in keV.

`energy`

* is optional

* Type: merged type ([Energy](metadata-schema-defs-publicscanmetadata-properties-energy.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-energy.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/energy")

#### energy Type

merged type ([Energy](metadata-schema-defs-publicscanmetadata-properties-energy.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-energy-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-energy-anyof-1.md "check type definition")

### current\_start

Current of the synchrotron at the start of the scan, measured in mA.

`current_start`

* is optional

* Type: merged type ([Current Start](metadata-schema-defs-publicscanmetadata-properties-current-start.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-current-start.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/current_start")

#### current\_start Type

merged type ([Current Start](metadata-schema-defs-publicscanmetadata-properties-current-start.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-current-start-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-current-start-anyof-1.md "check type definition")

### filling\_mode

Mode of filling used in the synchrotron storage ring.

`filling_mode`

* is optional

* Type: merged type ([Filling Mode](metadata-schema-defs-publicscanmetadata-properties-filling-mode.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filling-mode.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/filling_mode")

#### filling\_mode Type

merged type ([Filling Mode](metadata-schema-defs-publicscanmetadata-properties-filling-mode.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filling-mode-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filling-mode-anyof-1.md "check type definition")

### n\_projections

Number of projection images acquired during the scan.

`n_projections`

* is optional

* Type: merged type ([N Projections](metadata-schema-defs-publicscanmetadata-properties-n-projections.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-projections.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_projections")

#### n\_projections Type

merged type ([N Projections](metadata-schema-defs-publicscanmetadata-properties-n-projections.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-projections-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-projections-anyof-1.md "check type definition")

### n\_ref

Number of reference images collected during the scan.

`n_ref`

* is optional

* Type: merged type ([N Ref](metadata-schema-defs-publicscanmetadata-properties-n-ref.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-ref.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_ref")

#### n\_ref Type

merged type ([N Ref](metadata-schema-defs-publicscanmetadata-properties-n-ref.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-ref-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-ref-anyof-1.md "check type definition")

### n\_dark

Number of dark images (without illumination) collected during the scan.

`n_dark`

* is optional

* Type: merged type ([N Dark](metadata-schema-defs-publicscanmetadata-properties-n-dark.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-dark.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_dark")

#### n\_dark Type

merged type ([N Dark](metadata-schema-defs-publicscanmetadata-properties-n-dark.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-dark-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-dark-anyof-1.md "check type definition")

### latency\_time

Time delay between projections, measured in seconds.

`latency_time`

* is optional

* Type: merged type ([Latency Time](metadata-schema-defs-publicscanmetadata-properties-latency-time.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-latency-time.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/latency_time")

#### latency\_time Type

merged type ([Latency Time](metadata-schema-defs-publicscanmetadata-properties-latency-time.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-latency-time-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-latency-time-anyof-1.md "check type definition")

### exposure\_time

Exposure time of each frame, measured in seconds.

`exposure_time`

* is optional

* Type: merged type ([Exposure Time](metadata-schema-defs-publicscanmetadata-properties-exposure-time.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-exposure-time.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/exposure_time")

#### exposure\_time Type

merged type ([Exposure Time](metadata-schema-defs-publicscanmetadata-properties-exposure-time.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-exposure-time-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-exposure-time-anyof-1.md "check type definition")

### accumulation\_n\_frames

Number of frames accumulated per exposure.

`accumulation_n_frames`

* is optional

* Type: merged type ([Accumulation N Frames](metadata-schema-defs-publicscanmetadata-properties-accumulation-n-frames.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-accumulation-n-frames.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/accumulation_n_frames")

#### accumulation\_n\_frames Type

merged type ([Accumulation N Frames](metadata-schema-defs-publicscanmetadata-properties-accumulation-n-frames.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-accumulation-n-frames-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-accumulation-n-frames-anyof-1.md "check type definition")

### scan\_type

Type of scan.

`scan_type`

* is optional

* Type: merged type ([Scan Type](metadata-schema-defs-publicscanmetadata-properties-scan-type.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-type.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scan_type")

#### scan\_type Type

merged type ([Scan Type](metadata-schema-defs-publicscanmetadata-properties-scan-type.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-type-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-type-anyof-1.md "check type definition")

### scan\_range

Angular range of a single scan in degrees.

`scan_range`

* is optional

* Type: merged type ([Scan Range](metadata-schema-defs-publicscanmetadata-properties-scan-range.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-range.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scan_range")

#### scan\_range Type

merged type ([Scan Range](metadata-schema-defs-publicscanmetadata-properties-scan-range.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-range-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-range-anyof-1.md "check type definition")

### n\_scans

Total number of scans. For a helical scan this is always 1. For a zseries this is the total number of scans concatenated to make the full data volume.

`n_scans`

* is optional

* Type: merged type ([N Scans](metadata-schema-defs-publicscanmetadata-properties-n-scans.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-scans.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/n_scans")

#### n\_scans Type

merged type ([N Scans](metadata-schema-defs-publicscanmetadata-properties-n-scans.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-scans-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-n-scans-anyof-1.md "check type definition")

### acquisition

Type of tomographic acquisition.

`acquisition`

* is optional

* Type: merged type ([Acquisition](metadata-schema-defs-publicscanmetadata-properties-acquisition.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-acquisition.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/acquisition")

#### acquisition Type

merged type ([Acquisition](metadata-schema-defs-publicscanmetadata-properties-acquisition.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-acquisition-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-acquisition-anyof-1.md "check type definition")

### half\_acquisition\_value

Value representing if the scan was taken in half-acquisition or not.

`half_acquisition_value`

* is optional

* Type: merged type ([Half Acquisition Value](metadata-schema-defs-publicscanmetadata-properties-half-acquisition-value.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-half-acquisition-value.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/half_acquisition_value")

#### half\_acquisition\_value Type

merged type ([Half Acquisition Value](metadata-schema-defs-publicscanmetadata-properties-half-acquisition-value.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-half-acquisition-value-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-half-acquisition-value-anyof-1.md "check type definition")

### quarter\_acquisition\_value

Value representing if the scan was taken in quarter-acquisition or not.

`quarter_acquisition_value`

* is optional

* Type: merged type ([Quarter Acquisition Value](metadata-schema-defs-publicscanmetadata-properties-quarter-acquisition-value.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-quarter-acquisition-value.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/quarter_acquisition_value")

#### quarter\_acquisition\_value Type

merged type ([Quarter Acquisition Value](metadata-schema-defs-publicscanmetadata-properties-quarter-acquisition-value.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-quarter-acquisition-value-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-quarter-acquisition-value-anyof-1.md "check type definition")

### z\_step

Displacement in millimeters between scans.

`z_step`

* is optional

* Type: merged type ([Z Step](metadata-schema-defs-publicscanmetadata-properties-z-step.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-z-step.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/z_step")

#### z\_step Type

merged type ([Z Step](metadata-schema-defs-publicscanmetadata-properties-z-step.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-z-step-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-z-step-anyof-1.md "check type definition")

### scan\_time

Total duration of a single scan in seconds.

`scan_time`

* is optional

* Type: merged type ([Scan Time](metadata-schema-defs-publicscanmetadata-properties-scan-time.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-time.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scan_time")

#### scan\_time Type

merged type ([Scan Time](metadata-schema-defs-publicscanmetadata-properties-scan-time.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-time-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scan-time-anyof-1.md "check type definition")

### filters

List of filters used during the scan.

`filters`

* is optional

* Type: merged type ([Filters](metadata-schema-defs-publicscanmetadata-properties-filters.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filters.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/filters")

#### filters Type

merged type ([Filters](metadata-schema-defs-publicscanmetadata-properties-filters.md))

any of

* [Untitled array in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filters-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-filters-anyof-1.md "check type definition")

### scintillator

Scintillator used for converting X-rays to visible light.

`scintillator`

* is optional

* Type: merged type ([Scintillator](metadata-schema-defs-publicscanmetadata-properties-scintillator.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scintillator.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/scintillator")

#### scintillator Type

merged type ([Scintillator](metadata-schema-defs-publicscanmetadata-properties-scintillator.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scintillator-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-scintillator-anyof-1.md "check type definition")

### optic

Optical components used during the scan

`optic`

* is optional

* Type: merged type ([Optic](metadata-schema-defs-publicscanmetadata-properties-optic.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-optic.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/optic")

#### optic Type

merged type ([Optic](metadata-schema-defs-publicscanmetadata-properties-optic.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-optic-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-optic-anyof-1.md "check type definition")

### distance\_sample\_detector

Distance between the sample and the detector, measured in millimeters.

`distance_sample_detector`

* is optional

* Type: merged type ([Distance Sample Detector](metadata-schema-defs-publicscanmetadata-properties-distance-sample-detector.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-distance-sample-detector.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/distance_sample_detector")

#### distance\_sample\_detector Type

merged type ([Distance Sample Detector](metadata-schema-defs-publicscanmetadata-properties-distance-sample-detector.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-distance-sample-detector-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-distance-sample-detector-anyof-1.md "check type definition")

### sensor\_name

Name of the sensor used during the scan.

`sensor_name`

* is optional

* Type: merged type ([Sensor Name](metadata-schema-defs-publicscanmetadata-properties-sensor-name.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-name.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_name")

#### sensor\_name Type

merged type ([Sensor Name](metadata-schema-defs-publicscanmetadata-properties-sensor-name.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-name-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-name-anyof-1.md "check type definition")

### sensor\_mode

Operating mode of the sensor during the scan.

`sensor_mode`

* is optional

* Type: merged type ([Sensor Mode](metadata-schema-defs-publicscanmetadata-properties-sensor-mode.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-mode.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_mode")

#### sensor\_mode Type

merged type ([Sensor Mode](metadata-schema-defs-publicscanmetadata-properties-sensor-mode.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-mode-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-mode-anyof-1.md "check type definition")

### sensor\_magnification

Magnification in the sensor setup.

`sensor_magnification`

* is optional

* Type: merged type ([Sensor Magnification](metadata-schema-defs-publicscanmetadata-properties-sensor-magnification.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-magnification.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_magnification")

#### sensor\_magnification Type

merged type ([Sensor Magnification](metadata-schema-defs-publicscanmetadata-properties-sensor-magnification.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-magnification-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-magnification-anyof-1.md "check type definition")

### sensor\_roi\_x\_size

Number of pixels in the x-dimension of the sensor's region of interest (ROI).

`sensor_roi_x_size`

* is optional

* Type: merged type ([Sensor Roi X Size](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-x-size.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-x-size.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_roi_x_size")

#### sensor\_roi\_x\_size Type

merged type ([Sensor Roi X Size](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-x-size.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-x-size-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-x-size-anyof-1.md "check type definition")

### sensor\_roi\_y\_size

Number of pixels in the y-dimension of the sensor's region of interest (ROI).

`sensor_roi_y_size`

* is optional

* Type: merged type ([Sensor Roi Y Size](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-y-size.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-y-size.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/sensor_roi_y_size")

#### sensor\_roi\_y\_size Type

merged type ([Sensor Roi Y Size](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-y-size.md))

any of

* [Untitled integer in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-y-size-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-sensor-roi-y-size-anyof-1.md "check type definition")

### pixel\_size

Size of a pixel at the source, measured in micrometers.

`pixel_size`

* is optional

* Type: merged type ([Pixel Size](metadata-schema-defs-publicscanmetadata-properties-pixel-size.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-pixel-size.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/pixel_size")

#### pixel\_size Type

merged type ([Pixel Size](metadata-schema-defs-publicscanmetadata-properties-pixel-size.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-pixel-size-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-pixel-size-anyof-1.md "check type definition")

### xray\_magnification

Magnification of X-rays due to divergence between the source and detector.

`xray_magnification`

* is optional

* Type: merged type ([Xray Magnification](metadata-schema-defs-publicscanmetadata-properties-xray-magnification.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-xray-magnification.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/xray_magnification")

#### xray\_magnification Type

merged type ([Xray Magnification](metadata-schema-defs-publicscanmetadata-properties-xray-magnification.md))

any of

* [Untitled number in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-xray-magnification-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-xray-magnification-anyof-1.md "check type definition")

### proposal

ID of the ESRF proposal under which the scan was performed.

`proposal`

* is optional

* Type: merged type ([Proposal](metadata-schema-defs-publicscanmetadata-properties-proposal.md))

* cannot be null

* defined in: [HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-proposal.md "http://yourdomain.com/schemas/myschema.json#/$defs/PublicScanMetadata/properties/proposal")

#### proposal Type

merged type ([Proposal](metadata-schema-defs-publicscanmetadata-properties-proposal.md))

any of

* [Untitled string in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-proposal-anyof-0.md "check type definition")

* [Untitled null in HOAMetadata](metadata-schema-defs-publicscanmetadata-properties-proposal-anyof-1.md "check type definition")
