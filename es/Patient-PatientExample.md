# PatientExample - v0.1.0

## Ejemplo Patient: PatientExample

-------

**Spanish**

-------

Language: en

Profile: [PTPatient](StructureDefinition-PTPatient.md)

James Pond (no stated gender), DoB Unknown ( 007)

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "PatientExample",
  "meta" : {
    "profile" : ["http://example.org/StructureDefinition/PTPatient"]
  },
  "language" : "en",
  "identifier" : [
    {
      "value" : "007"
    }
  ],
  "name" : [
    {
      "family" : "Pond",
      "given" : ["James"]
    }
  ]
}

```
