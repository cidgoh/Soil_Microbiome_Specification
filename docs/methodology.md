# Methodology

## Development approach

The specification is being developed through a structured process that combines existing evidence with stakeholder knowledge. This avoids treating harmonization as a simple exercise in renaming spreadsheet columns. The team first examines the landscape of standards and data practices, defines the boundaries of the work, compares schemas, drafts a shared structure, and then uses stakeholder engagement to test and refine the result.

| Development activity | What it contributes |
|---|---|
| Review standards and resources | Identifies established metadata approaches, ontology terms, controlled vocabularies, and potential mappings |
| Review literature | Shows which contextual variables are reported in soil microbiome studies and helps identify relevant concepts and gaps |
| Review project schemas and documentation | Examines actual fields and structures in ICT schemas, grants, and data-management plans |
| Define scope and common concepts | Clarifies the terrestrial soil focus, intended users, common needs, and exclusions |
| Compare fields and data practices | Identifies overlap, differences, and omissions in reviewed schemas, and areas where definitions need closer examination |
| Develop the specification structure | Defines candidate fields, standardized names, descriptions, examples, requirement levels, and mappings where appropriate |
| Engage stakeholders | Underway — a needs assessment questionnaire has been developed and is being used to gather input from research teams on missing fields, definitions, formats, and priorities |
| Refine and validate | Ongoing — feedback from stakeholder engagement is being used to improve fields, terminology, and documentation |

## Evidence sources

The specification draws on three main sources of evidence:

**Literature review**: 5,815 papers screened; 76 retained for detailed review based on relevance to soil microbiome contextual data.

**Standards and schemas**: 29 ICT schemas in the CS-DCC Harmonization HUB library reviewed.

**Specification development**: Cield counts and ontology mappings are updated continuously as the specification evolves. 

- **MIxS Soil**: an existing soil-related metadata package used as a mapping and alignment reference
- **NMDC** (National Microbiome Data Collaborative): reviewed as part of the metadata landscape
- **GENEPIO**: an ontology used for sample and contextual data concepts
- **ENVO and AGRO**: ontologies relevant to environmental and agricultural concepts
- **Canadian Soil Observatory (CSBO)**: a national initiative focused on soil monitoring and data across Canada
- **GRDI and ICT schemas**: sources for comparison and cross-project alignment

Alignment is not a claim that every field must map to an existing term. Where a suitable term exists, reuse promotes consistency. Where a concept is not adequately represented, the gap should be documented and a new term considered through the appropriate curation process.

## From different fields to shared concepts

A central task is to determine how fields from different projects relate to each other. For example, one schema may use `Soil_pH`, another `pH_level`, and another may not expose a soil pH field at all. This creates a useful starting point for review, but it is not enough to conclude that the fields are equivalent. Their definitions, units, expected values, measurement methods, and intended context must all be compared.

The same applies to moisture-related fields. `Percent_Moisture`, `soil_water_content`, and `soil_moisture` may refer to related measurements, but the underlying concept may differ depending on whether water content is expressed on a gravimetric or volumetric basis, the units used, or the measurement method. A harmonized specification should make these distinctions visible rather than obscure them behind a common label.

The comparison process moves from observed field names to a carefully defined shared concept. Where the concept matches an existing standard or ontology term, the specification maps to that resource. Where it does not, the gap is documented and a new term may be considered. The aim is to make mappings defensible and transparent, not to force all fields into equivalence.

## Ontologies and data quality

An ontology is a structured set of defined concepts connected through relationships. Ontology terms commonly have persistent identifiers and may include synonyms, definitions, and relationships to other concepts. Linking a field to an appropriate ontology term helps clarify what the field represents beyond the local name chosen by a project.

A field and an ontology term are related but not identical: the field is part of a data structure in which a value is recorded, while the ontology term represents the concept to which the field refers. Not every field will have a suitable ontology mapping at every stage of development. The status of mappings will be documented and updated as the specification evolves.
