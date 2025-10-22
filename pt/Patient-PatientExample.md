# PatientExample - v0.1.0

## Exemplo Patient: PatientExample

-------

**Portuguese**

-------

Língua: en

Perfil: [PTPatient](StructureDefinition-PTPatient.md)

James Pond (sem género declarado), DN Desconhecida ( 007)

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
