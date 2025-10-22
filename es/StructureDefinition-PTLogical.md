# PTLogical - v0.1.0

## Modelo lógico: PTLogical 

**Usages:**

* This Logical Model is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/lang.dependent|current/StructureDefinition/PTLogical)

### Vistas formales del contenido del perfil

 [Descripción de perfiles, diferenciales, instantáneas y sus representaciones](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Tabla diferencial](#tabs-diff) 
*  [Tabla de instantáneas](#tabs-snap) 
*  [Estadísticas/Referencias](#tabs-summ) 
*  [Todos](#tabs-all) 

Esta estructura se deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) .

#### Constraints

Esta estructura se deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) .

**Summary**

 **Vista diferencial** 

Esta estructura se deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) .

 **Vista instantáneaView** 

#### Constraints

Esta estructura se deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) .

**Summary**

 

Otras representaciones de perfil: [CSV](../StructureDefinition-PTLogical.csv), [Excel](../StructureDefinition-PTLogical.xlsx) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "PTLogical",
  "url" : "http://example.org/StructureDefinition/PTLogical",
  "version" : "0.1.0",
  "name" : "PTLogical",
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
  "fhirVersion" : "4.0.1",
  "kind" : "logical",
  "abstract" : false,
  "type" : "http://example.org/StructureDefinition/PTLogical",
  "baseDefinition" : "http://hl7.org/fhir/test/multi-lang/StructureDefinition/LogicalExample",
  "derivation" : "specialization",
  "differential" : {
    "element" : [
      {
        "id" : "PTLogical",
        "path" : "PTLogical",
        "short" : "PTLogical",
        "definition" : "PTLogical"
      }
    ]
  }
}

```
