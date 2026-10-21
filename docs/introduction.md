# Introduction

## 1. Why soil microbiome data need shared context

Soil microbiome research can help investigate relationships among microbial communities, soil characteristics, land management, climate, and ecosystem conditions. 
Microbiome results, however, are difficult to interpret or compare without information describing the sample and the circumstances in which it was collected. 
Context can include location, sampling depth and timing, soil properties, vegetation and land use, management practices, sample handling, storage, and sequencing-related information.

Research and monitoring initiatives often collect overlapping types of information, but describe them using different field names, data structures, definitions, units, controlled vocabularies, and levels of detail. 
One project may record soil moisture as `Percent_Moisture`, another as `soil_water_content`, and another as `soil_moisture`. 
A reviewed schema may not expose a corresponding field at all. These differences make it difficult to determine whether datasets describe the same concept, to combine them reliably, or to reuse data beyond the project that generated it.

The challenge is not simply that field names differ. Two similar names may represent different measurements, and two different names may represent the same concept. Soil moisture and soil water content, for example, may be used interchangeably in some settings, but may also differ according to measurement basis, units, method, and definition. 
Harmonization therefore requires semantic review: definitions, units, expected values, methods, and context must all be considered before fields are treated as equivalent. Likewise, a field missing from a reviewed schema does not prove that a project never collected the information. 
It only indicates that the information was not found in the resource examined.

The CS-DCC Soil Microbiome Specification project is developing a shared framework for describing contextual information associated with terrestrial soil microbiome samples.
Its purpose is to make data easier to connect, compare, interpret, and reuse while allowing projects to retain their existing workflows. It is intended to align with relevant standards and vocabularies rather than replace them, and to evolve through evidence review and community engagement.

## 2. Purpose, objectives, and guiding principles

### 2.1 Purpose

Develop a practical, community-informed contextual data specification that improves consistency and interoperability across soil microbiome research and monitoring initiatives.

### 2.2 Objectives

- Identify common contextual information needs across soil microbiome research and monitoring projects.
- Review existing standards, schemas, vocabularies, literature, grants, and data-management plans to understand current practices and gaps.
- Define clear fields, names, descriptions, examples, requirements, and mappings where appropriate.
- Align with existing standards and ontology terms when they adequately represent the intended concept.
- Use stakeholder feedback to refine scope, field definitions, terminology, and practical guidance.
- Support future implementation, validation, and reuse without requiring projects to replace their local data systems.

### 2.3 Guiding principles

- **Interoperability through shared meaning**, not name matching alone.
- **Reuse of established standards and ontology terms** where suitable.
- **Transparent definitions**, identifiers, units, examples, and guidance.
- **Community-informed development** that accounts for real research and monitoring practices.
- **Clear boundaries** between contextual metadata and analytical or derived outputs.
- **Extensibility**: the specification can evolve as data needs and community feedback change.

## 3. What this specification is not

- It is not a replacement of any other existing standard. It aligns with and maps to existing standards where possible.
- It is not a requirement. Projects can adopt it in full, in part, or use it only as a reference.
- It is not finished. The specification is under active development and will be refined through ongoing stakeholder engagement.

## Where to go next

- [Scope](scope.md) — what is and is not covered by this specification
- [Domains](domains.md) — the four contextual data domains
- [Methodology](methodology.md) — how the specification is being developed
- [Specification files](../specification/) — the full field-by-field data
