# PTLogical - v0.1.0

## Logical Model: PTLogical 

**Usages:**

* This Logical Model is not used by any profiles in this Implementation Guide

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/lang.dependent|current/StructureDefinition/PTLogical)

### Formal Views of Profile Content

 [Description Differentials, Snapshots, and other representations](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](../StructureDefinition-PTLogical.csv), [Excel](../StructureDefinition-PTLogical.xlsx) 



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
