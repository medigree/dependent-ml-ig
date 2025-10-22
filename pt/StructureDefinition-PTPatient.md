# PTPatient - v0.1.0

## Perfil de recurso: PTPatient 

 
An example profile of the Patient resource. 

**Usos:**

* Exemplos para este Perfil: [Patient/PatientExample](Patient-PatientExample.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/lang.dependent|current/StructureDefinition/PTPatient)

### Vistas formais do conteúdo do perfil

 [Descrição de perfis, diferenciais, instantâneos e suas representações](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Tabela de elementos-chave](#tabs-key) 
*  [Tabela diferencial](#tabs-diff) 
*  [Tabela de instantâneos](#tabs-snap) 
*  [Obrigações](#tabs-obligations) 
*  [Estatísticas/Referências](#tabs-summ) 
*  [Todas](#tabs-all) 

#### Terminologia Ligações

#### Restrições

Esta estrutura deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) 

#### Terminologia Ligações

#### Restrições

Esta estrutura deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) 

**Resumo**

Obrigatório: 1 elemento
 Deve ser suportado: 1 elemento

 **Vista de Elementos-Chave** 

#### Terminologia Ligações

#### Restrições

 **Vista Diferencial** 

Esta estrutura deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) 

 **Vista TotalView** 

#### Terminologia Ligações

#### Restrições

Esta estrutura deriva de [ExampleStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-example.html) 

**Resumo**

Obrigatório: 1 elemento
 Deve ser suportado: 1 elemento

 

Outras representações do perfil: [CSV](../StructureDefinition-PTPatient.csv), [Excel](../StructureDefinition-PTPatient.xlsx), [Schematron](../StructureDefinition-PTPatient.sch) 



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
