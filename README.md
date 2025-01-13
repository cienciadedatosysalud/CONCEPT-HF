![Logo of the project](main_logo.png)

<small><i>This project follows the structure built using the [Common Data Model Builder](https://github.com/cienciadedatosysalud/cdmb), a tool that allows you to create common data models to facilitate interoperability and reproducibility of the analyses.</i></small>


# CONCEPT-HF

Common Data Model for Cohort Analysis of Patients in the CONCEPT-HF Project.

This data model includes cohort definition information with the specification for selecting hospitalization episodes due to heart failure based on the primary diagnosis (i.e., ICD-9 or ICD-10), and the specification and definition of the minimum set of variables required to accomplish the study's objectives. 
A schematic figure is also included to depict the expected sources of the required information within the information systems of different levels of care, according to the sequence of the care process.


## Main specific aims:

The CONCEPT-HF project aims to analyze the effectiveness of the healthcare process experienced by HF patients.

Specific Objectives are to identify and characterize the healthcare trajectories experienced by HF patients within the healthcare system and compare care pathways experienced by HF patients with the theoretical trajectories derived from clinical guidelines, including process indicators, diagnosis, clinical follow-up, and pharmacological treatment recommendations.

A third point of interest is to evaluate the effect of adherence to clinical guidelines by patients and healthcare providers on health outcomes.

Finally, we want to evaluate the quality improvement strategies based on HF Programs concerning process and outcome indicators, analyzing deviations from observed healthcare trajectories compared to theoretical ones and the differences in HF care and outcomes between three Spanish healthcare systems: Andalusian, Aragonese, and Basque

## Cohort definition:

The cohort is defined as patients admitted to hospital due to acute ischaemic stroke.

### Inclusion criteria: 

Patients 18 years old or older with at least a hospital admission with a main diagnosis of heart failure within the period of study.

### Exclusion criteria: 

Patients younger than 18 years.

Patients with a secondary diagnosis of heart failure or a diagnosis of heart failure at primary care without any hospital admissions due to this during the period of study.


## Study period:

From 01-01-2015 until 31-12-2022

## IN ORDER TO RUN THE DOCKER FOLLOW THE NEXT STEPS

### 1-HOW TO RUN
Use the following code snippet to create the container.
```bash
docker pull ghcr.io/cienciadedatosysalud/concept-hf:latest

```

```bash

docker run -d -p 127.0.0.1:3000:3000 --name concept-hf-aspire ghcr.io/cienciadedatosysalud/concept-hf:latest

```

Open your web browser at http://localhost:3000

### 2-Run the analysis

Follow the steps below.
  1. Map your data in the "MAP DATA" tab.
  2. If everything has worked well, in the "RUN ANALYSIS" tab, select the project "CONCEPT-HF" and select the script "**analysis_concept.qmd**"
  3. Go to the "OUTPUTS" tab and download the results.

# Authoring

| Surname, name | Affiliation | ![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png) ORCID |
|---------------|-------------|------------------------------------------------------------------------------|
| Quirós-López, Raúl | Hospital Universitario Costa del Sol |  https://orcid.org/0000-0002-2802-2477
| Estupiñan-Romero, Francisco | Instituto Aragonés de Ciencias de la Salud (IACS) | https://orcid.org/0000-0002-6285-8120 |
| Jiménez-García, Nicolás | Hospital Universitario Costa del Sol | https://orcid.org/0000-0002-6839-0303
| Millán-Ortuondo, Eduardo | Osakidetza-Servicio Vasco de Salud | https://orcid.org/0000-0002-9688-9304
| Royo-Sierra, Santiago | Instituto Aragonés de Ciencias de la Salud (IACS) | https://orcid.org/0000-0002-0048-4370 |
| González-Galindo, Javier | Instituto Aragonés de Ciencias de la Salud (IACS) | https://orcid.org/0000-0002-8783-5478 |
| Bernal-Delgado, Enrique | Instituto Aragonés de Ciencias de la Salud (IACS) | https://orcid.org/0000-0002-0961-3298 |

__Project leader: [Bernal-Delgado, Enrique](https://orcid.org/0000-0002-0961-3298)__



# How to contribute
- Repository: https://github.com/cienciadedatosysalud/CONCEPT-HF
- Issue tracker: https://github.com/cienciadedatosysalud/CONCEPT-HF/issues

> [!CAUTION]
> Please note that the information is provided as-is, in compliance with the specifications of the CONCEPT-HF project. The details included in this data model are subject to change, as this is the first version of the specification. They are confined to the design process of the proposed study in CONCEPT-HF and should not be interpreted outside of this scope. For any comments, clarifications, or verification, please contact us at: http://cienciadedatosysalud.org/contacto/.

# References
- Data Science for Health Services and Policy Research group: https://cienciadedatosysalud.org/en/
- Common Data Model Builder library :https://github.com/cienciadedatosysalud/cdmb
- Analytic Software Pipeline Interface for Reproducible Execution (ASPIRE): https://github.com/cienciadedatosysalud/ASPIRE
- Atlas VPM community in Zenodo: https://zenodo.org/communities/atlasvpm
- Research Object Crate (RO-Crate): https://www.researchobject.org/ro-crate/
- ORCID: https://orcid.org/

<!--[![DOI](https://zenodo.org/badge/.svg)](https://zenodo.org/badge/latestdoi/)-->
<a href="https://creativecommons.org/licenses/by/4.0/" target="_blank" ><img src="https://img.shields.io/badge/license-CC--BY%204.0-lightgrey" alt="License: CC-BY 4.0"></a>

