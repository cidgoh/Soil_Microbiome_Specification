# Frequently Asked Questions

## About the specification

### What is the Soil Microbiome Specification?
A developing framework for describing contextual information associated with soil microbiome samples in a consistent and interpretable way.

### Why is it needed?
Projects often describe related information with different field names, structures, definitions, units, and levels of detail. A shared specification can make relationships clearer and support integration, comparison, and reuse across projects.

### What is contextual data?
Information describing the sample and its circumstances, including collection details, soil properties, environmental and management context, and processing and sequencing context.

### Who is developing this specification?
The specification is being developed by the Centre for Infectious Disease Genomics and One Health (CIDGOH) at Simon Fraser University (SFU), as part of the Climate-Smart Digital Agriculture - Data Coordination Centre (CS-DCC) project, with input from ICT research teams, federal partners, and community stakeholders across Canada.

### Is the specification complete?
The specification structure is in place and stakeholder engagement is informing ongoing refinement. Further refinement and validation are part of the development process.

### What version is the specification at, and how do I know what changed?
The current version is reflected in the specification filename in the specification/ folder. Once formal releases are made, changes between versions will be recorded in GitHub Releases, including a summary of fields added, removed, or updated.

---

## Scope

### What environments are in scope?
Terrestrial soil microbiome samples from agricultural, forest, grassland, and urban environments.

### Are sediments included?
No. Aquatic sediments and depositional contexts are outside the current terrestrial soil scope and may be addressed through the existing wastewater specification.

### Are microbiome sequence outputs or derived ecological indicators included?
No. Analytical or derived microbiome data, such as downstream bioinformatic outputs, statistical analyses, and derived ecological indicators, are outside the current scope.

### Does a missing field in a project schema mean the project never collected the data?
No. It only means the field was not found in the schema or resource reviewed. The information may be stored elsewhere in the project.

---

## Fields and terms

### If two fields have similar names, can they be mapped automatically?
No. Definitions, units, expected values, methods, and context all need to be checked before treating fields as equivalent.

### What if two fields have different names but mean the same thing?
They may be candidates for alignment after semantic review. A shared specification field can be defined and mapped to both original fields where the equivalence is supported by evidence.

### What are ontologies and why are they used?
Ontologies provide defined concepts, persistent identifiers, and relationships between terms. Reusing appropriate ontology terms helps clarify what a field means and supports consistent interpretation across systems.

### Does every specification field already have an ontology term?
Not necessarily. Mapping coverage may be incomplete during development. Where a suitable existing term is available it should be reused; where a gap exists it should be documented and addressed through the curation process.

---

## Implementation

### What is DataHarmonizer?
DataHarmonizer is a tool that allows researchers to enter and validate data against a specification template. A DataHarmonizer template for this specification is in development.

### Is the DataHarmonizer template available now?
Not yet. DataHarmonizer resources are in development alongside the specification.

### What is intended to be included in the full project package?
A data collection template, field and term reference guides, a curation SOP, DataHarmonizer instructions, and a New Term Request SOP, with versioning and release notes.

### Will the specification replace our existing data system?
No. The goal is to provide a shared reference for interoperability while projects retain their local systems and workflows.

### Does harmonization mean all data must be openly shared?
No. Interoperability and open access are different things. Data access and sharing remain subject to applicable permissions, privacy, sensitivity, licensing, consent, and governance arrangements.

---

## Contributing

### How can I request a new field or term?
Use the repository issue request form and follow the New Term Request SOP when available. Explain the data need, definition, example value, context, and why existing fields or terms are insufficient. Requests are reviewed through working-group discussion.

### Will every new term request be accepted?
Not necessarily. Requests are reviewed for relevance, meaning, data structure fit, and whether an existing field or term can already meet the need.

### How can a project or researcher contribute more broadly?
Share feedback on fields and definitions, identify missing concepts, suggest terms, and describe current data practices through the repository's contribution route.

---

## Engagement and governance

### Why is stakeholder engagement important?
It checks whether proposed fields reflect real practices, identifies missing information, clarifies definitions, and helps prioritize improvements.

### Why is an ethics review relevant?
Where interviews or other research activities involve people, ethics review helps ensure appropriate consent, confidentiality, data handling, and risk management.

---

## Climate data

### What is the proposed climate-data work?
A possible next phase to inventory climate-related outputs across projects, compare definitions and units, identify shared needs, align suitable concepts, and pilot a shared approach with project teams.
