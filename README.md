# Requirements-driven data preparation for AI-powered systems

This repository contains the supplementary materials for the article:

**Requirements-driven data preparation for AI-powered systems: A framework and transportation-domain evaluation**

The article introduces the **Requirements-Driven Data Preparation (RDP)** framework, which treats data preparation for AI-powered systems as a requirements-engineering concern. RDP links organizational and domain objectives to system-level requirements, derives data obligations from those requirements, expresses the obligations through data-quality dimensions, and translates them into data-preparation task families.

## Repository contents

| File | Description |
|---|---|
| `Article RDP Highlights.pdf` | One-page highlights for the article. |
| `S1_Articles_thematic_analysis.xlsx` | Supplementary Material S1: focused literature review corpus, thematic coding, derivation matrices, and ISO/IEC alignment. |
| `S2_Participants_thematic_analysis.xlsx` | Supplementary Material S2: interview protocols and thematic analysis for expert and transportation-domain participants. |
| `S3_Case_Documentation.docx` | Supplementary Material S3: de-identified case documentation for the National Transportation Big-Data Infrastructure action-research case study. |

## Supplementary Material S1

`S1_Articles_thematic_analysis.xlsx` documents the literature-based construction of the initial RDP framework.

It includes four worksheets:

1. **Article themes**  
   Source-to-category mapping for the focused literature review. The sheet documents the reviewed articles, article metadata, raw data-quality terms, supporting quotes, consolidated data-quality dimensions, mapped system-level requirements, data-preparation tasks, supporting evidence, and task families.

2. **Derivation of data-quality dimensions**  
   Matrix showing how system-level requirements imply data obligations and how these obligations are expressed through RDP data-quality dimensions.

3. **Derivation of data-preparation**  
   Matrix showing how data-quality dimensions imply concrete data-preparation actions and how these actions are operationalized through RDP task families.

4. **ISO IEC alignment and boundary**  
   Mapping between the RDP data-quality dimensions and ISO/IEC 25012 and ISO/IEC 5259 concepts, including alignment rationale and boundary clarification.

## Supplementary Material S2

`S2_Participants_thematic_analysis.xlsx` documents the empirical interview materials and thematic analysis.

It includes four worksheets:

1. **Experts questions**  
   Interview questions used with five data and AI experts.

2. **Experts thematic analysis**  
   Thematic analysis of expert interviews, including data-quality quotes, mapped data-quality dimensions, system-requirement quotes, mapped system-level requirements, data-preparation quotes, and mapped task families.

3. **Transportation domain questions**  
   Interview questions used with transportation-domain participants.

4. **Transportation thematic analysis**  
   Thematic analysis of transportation-domain interviews, including data-quality quotes, system-requirement quotes, data-preparation quotes, and their mappings to RDP constructs.

## Supplementary Material S3

`S3_Case_Documentation.docx` provides de-identified case documentation for the prospective application of RDP in the National Transportation Big-Data Infrastructure case.

The document summarizes:

- the scope of the case documentation;
- the SRS-derived topological data model;
- the common-language standards profile and integration services;
- derived data-related requirements and their primary data obligations;
- a corridor proof-of-concept instantiation;
- a national traffic-metrics catalogue sample;
- traceability between derived requirements, RDP layers, and instantiating artifacts.

## RDP framework overview

The RDP framework follows the derivation chain:

```text
organizational and domain objectives
        ↓
system-level requirements
        ↓
data obligations expressed through data-quality dimensions
        ↓
data-preparation task families
        ↓
prepared data substrate for AI-powered systems
```

## RDP data-quality dimensions

The framework consolidates eight data-quality dimensions:

1. **Accuracy & Validity**
2. **Completeness**
3. **Consistency & Integrity**
4. **Timeliness & Currency**
5. **Representativeness & Distributional Coverage**
6. **Traceability & Provenance**
7. **Confidentiality & Identifiability**
8. **Relevance & Usability**

## RDP data-preparation task families

The framework organizes data-preparation work into six task families:

1. **Data Assessment and Qualification**
2. **Data Cleaning, Repair, and Structuring**
3. **Data Integration and Semantic Alignment**
4. **Data Enrichment and Adjustments**
5. **Data Traceability, Protection, and Governance**
6. **Data Maintenance and Operational Control**

## How to use this repository

Use the materials as follows:

- Use **S1** to inspect how the literature review evidence was coded, consolidated, and mapped into RDP constructs.
- Use **S2** to inspect how expert and transportation-domain interview evidence was analyzed and mapped to the framework.
- Use **S3** to inspect how RDP was prospectively applied in the National Transportation Big-Data Infrastructure case and how derived requirements were traced to artifacts.
- Use the **Highlights** file for a concise statement of the article’s main contributions.

## Data and confidentiality

The repository contains de-identified supplementary materials. It does not include identifiable participant information or confidential full project documentation. The case material is reported as a de-identified summary of SRS findings and supporting artifacts.

## Citation

The article is currently under submission. Until a DOI is available, please cite the manuscript as:

```bibtex
@article{sadovski_rdp_ai_data_preparation,
  title   = {Requirements-driven data preparation for AI-powered systems: A framework and transportation-domain evaluation},
  author  = {Sadovski, Eran and Aviv, Itzhak and Hadar, Irit},
  journal = {Submitted manuscript},
  year    = {2026}
}
```

## Contact

For questions about the repository or the RDP framework, contact:

**Eran Sadovski**  
University of Haifa  
Email: sdv.eran@gmail.com

## License

No license has been assigned yet. Reuse is not permitted unless a license is added or explicit permission is granted by the authors.
