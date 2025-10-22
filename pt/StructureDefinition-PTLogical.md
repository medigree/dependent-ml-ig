# PTLogical - v0.1.0

## Modelo lógico: PTLogical 

**Usos:**

* Este Modelo lógico não é utilizado por nenhum perfil neste guia de implementação

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/lang.dependent|current/StructureDefinition/PTLogical)

### Vistas formais do conteúdo do perfil

 [Descrição de perfis, diferenciais, instantâneos e suas representações](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

*  [Tabela diferencial](#tabs-diff) 
*  [Tabela de instantâneos](#tabs-snap) 
*  [Estatísticas/Referências](#tabs-summ) 
*  [Todas](#tabs-all) 

Esta estrutura deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) 

#### Restrições

Esta estrutura deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) 

**Resumo**

 **Vista Diferencial** 

Esta estrutura deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) 

 **Vista TotalView** 

#### Restrições

Esta estrutura deriva de [ExampleLogicalStructureDefinition](https://build.fhir.org/ig/FHIR/multi-lang-test-ig/StructureDefinition-LogicalExample.html) 

**Resumo**

 

Outras representações do perfil: [CSV](../StructureDefinition-PTLogical.csv), [Excel](../StructureDefinition-PTLogical.xlsx) 



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
