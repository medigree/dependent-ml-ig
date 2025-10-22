# PTPatient - v0.1.0

## Perfil de los recursos: PTPatient 

 
An example profile of the Patient resource. 

**Usages:**

* Examples for this Profile: [Patient/PatientExample](Patient-PatientExample.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/lang.dependent|current/StructureDefinition/PTPatient)

### Vistas formales del contenido del perfil

 [Descripción de perfiles, diferenciales, instantáneas y sus representaciones](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Tabla de elementos clave](#tabs-key) 
*  [Tabla diferencial](#tabs-diff) 
*  [Tabla de instantáneas](#tabs-snap) 
*  [Obligaciones](#tabs-obligations) 
*  [Estadísticas/Referencias](#tabs-summ) 
*  [Todos](#tabs-all) 

#### Terminology Bindings

#### Constraints

Esta estructura se deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) .

#### Terminology Bindings

#### Constraints

Esta estructura se deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) .

**Summary**

Mandatory: 1 element
 Must-Support: 1 element

 **Vista de elementos clave** 

#### Terminology Bindings

#### Constraints

 **Vista diferencial** 

Esta estructura se deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) .

 **Vista instantáneaView** 

#### Terminology Bindings

#### Constraints

Esta estructura se deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) .

**Summary**

Mandatory: 1 element
 Must-Support: 1 element

 

Otras representaciones de perfil: [CSV](../StructureDefinition-PTPatient.csv), [Excel](../StructureDefinition-PTPatient.xlsx), [Schematron](../StructureDefinition-PTPatient.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "PTPatient",
  "url" : "http://example.org/StructureDefinition/PTPatient",
  "version" : "0.1.0",
  "name" : "PTPatient",
  "status" : "draft",
  "date" : "2025-10-22T16:35:27+00:00",
  "publisher" : "Example Publisher",
  "contact" : [
    {
      "name" : "Example Publisher",
      "telecom" : [
        {
          "system" : "url",
          "value" : "http://example.org/example-publisher"
        }
      ]
    }
  ],
  "description" : "An example profile of the Patient resource.",
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "cda",
      "uri" : "http://hl7.org/v3/cda",
      "name" : "CDA (R2)"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    },
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 v2 Mapping"
    },
    {
      "identity" : "loinc",
      "uri" : "http://loinc.org",
      "name" : "LOINC code for the element"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Patient",
  "baseDefinition" : "http://hl7.org/fhir/test/multi-lang/StructureDefinition/example",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Patient",
        "path" : "Patient"
      },
      {
        "id" : "Patient.name",
        "path" : "Patient.name",
        "min" : 1,
        "mustSupport" : true
      }
    ]
  }
}

```
