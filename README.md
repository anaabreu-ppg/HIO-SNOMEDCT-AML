# Ontologies in Hearing Impairment: Structural Analysis and Perspectives on Semantic Interoperability

**Manuscript ID:** 10652

## Authors

- Ana Paula Lopes de Abreu Ferreira
- Sandro José Rigo
- Luis Felipe Maldaner

## Affiliation

Graduate Program in Applied Computing  
Universidade do Vale do Rio dos Sinos (UNISINOS)  
São Leopoldo, RS, Brazil

---

## Repository Purpose

This repository provides supplementary information to support the reproducibility of the ontology alignment experiment described in the manuscript *"Ontologies in Hearing Impairment: Structural Analysis and Perspectives on Semantic Interoperability"*.

The study investigates semantic interoperability in the hearing health domain through a comparative analysis between the Hearing Impairment Ontology (HIO) and the Systematized Nomenclature of Medicine – Clinical Terms (SNOMED CT).

The objective is to identify conceptual correspondences, semantic overlaps, and potential interoperability relationships between ontological models applied to hearing impairment.

---

## Ontologies Used

### Hearing Impairment Ontology (HIO)

Official source:

https://bioportal.bioontology.org/ontologies/HIO

The Hearing Impairment Ontology (HIO) is a biomedical ontology designed to represent knowledge related to hearing impairment, including clinical, genetic, phenotypic, and therapeutic aspects.

---

### SNOMED CT

Maintained by:

SNOMED International

https://www.snomed.org

Official distribution source provided by the U.S. National Library of Medicine (NLM):

https://www.nlm.nih.gov/healthit/snomedct/archive.html

### Version Used

**SNOMED CT International Release 2024-09**

The OWL file used in this study is not redistributed through this repository.

Researchers interested in reproducing the experiment should obtain the corresponding SNOMED CT release directly from official distribution channels maintained by SNOMED International or authorized National Release Centers.

Access to SNOMED CT resources may require registration, acceptance of licensing terms, or compliance with institutional and national requirements established by the organizations responsible for its distribution. Researchers are encouraged to follow the procedures defined by the official providers to obtain authorization and access to the resources required for research and reproducibility purposes.

For the purposes of this study, a domain-specific subset of SNOMED CT associated with hearing loss and hearing impairment was derived from the official release. The extraction process was centered on the concept:

**Hearing disorder (Disorder)**  
**SNOMED CT Concept ID: 15188001**

and its associated hierarchical structure within the hearing health domain.

The resulting subset comprised **797 classes**, which were compared with the **495 classes** of the Hearing Impairment Ontology (HIO).

The extraction of hearing loss-related concepts was performed exclusively for research and reproducibility purposes and does not modify, replace, or redistribute the original SNOMED CT release maintained by SNOMED International.

---

## Ontology Alignment Tool

### AgreementMakerLight (AML)

Official repository:

https://github.com/AgreementMakerLight/AML-Project

### Version Used

**AgreementMakerLight (AML) 3.2**

AgreementMakerLight (AML) is a widely used ontology matching system designed to support semantic interoperability between large ontologies, particularly within biomedical domains.

---

## Ontology Alignment Procedure

To reproduce the experiment, the ontologies should be obtained from their respective official sources and loaded into AgreementMakerLight (AML) using OWL-compatible formats.

During the alignment process:

- Source Ontology: Hearing Impairment Ontology (HIO)
- Target Ontology: SNOMED CT (hearing loss-related subset)

After loading the ontologies, AML automatically executes its semantic matching mechanisms to identify correspondences between concepts based on lexical and structural similarities.

The resulting alignments are presented by AML as mappings associated with confidence values, allowing detailed inspection of the semantic relationships identified between the ontologies.

---

## Experimental Configuration

The following configuration was used during the experiment:

| Parameter | Value |
|------------|---------|
| Alignment Tool | AgreementMakerLight (AML) |
| AML Version | 3.2 |
| Similarity Threshold | 0.5 |
| Source Ontology | Hearing Impairment Ontology (HIO) |
| Target Ontology | SNOMED CT (hearing loss-related subset) |
| HIO Classes Analyzed | 495 |
| SNOMED CT Classes Analyzed | 797 |
| Valid Mappings Identified | 39 |

The alignment process was performed automatically using the native ontology matching mechanisms provided by AML.

---

## Alignment Results

The ontology alignment experiment identified **39 valid semantic correspondences (mappings)** between concepts from SNOMED CT and HIO.

The results were generated through the AML Alignment Panel, which records the identified mappings, their associated confidence values, and the semantic relationships established between the compared ontologies.

The correspondences were primarily concentrated in established clinical concepts related to hearing loss, including diagnostic categories and hearing impairment-associated syndromes.

Examples include:

- Hearing impairment
- Usher syndrome
- Waardenburg syndrome
- Pendred syndrome

AML also enables detailed inspection of each identified mapping, supporting the analysis of concept-level correspondences and confidence values generated during the matching process.


---

## Reproducibility

Researchers interested in reproducing this study may obtain the ontologies from their respective official providers and execute the experiment using the configuration described in this repository.

To maximize reproducibility, it is recommended that researchers use:

- The same ontology versions;
- The same SNOMED CT release;
- AgreementMakerLight (AML) version 3.2;
- The same similarity threshold (0.5).

The use of all referenced resources remains subject to the licensing terms, registration requirements, institutional policies, and applicable regulations established by the organizations responsible for each ontology.

---

## Manuscript

**Ontologies in Hearing Impairment: Structural Analysis and Perspectives on Semantic Interoperability**

Manuscript ID: **10652**

---






