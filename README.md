<div id="top"></div>

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- PROJECT SHIELDS @todo add when te repo goes public
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Web Site][website-shield]][website-url] -->

<br />
<div align="center">
  <a href="https://github.com/onetomapanalytics/Meta_Data">
    <img src="LOGO_02.png" alt="Logo" width="500" height="150"> 
  </a>

<h3 align="center">One to Map meta-data</h3>

  <p align="center">
    Healhcare analytics through research
    <br />
    <a href="https://github.com/onetomapanalytics/Meta_Data"><strong>Explore the docs »</strong></a>
    <br />
    <br />
  </p>
</div>


<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
    <li><a href="#getting-started">Getting Started</a>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#how-to-find-a-database-to-answer-your-clinical-research-question-using-the-one-to-map-meta-data-repository-on-github">How to find a database</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


## About The Project

The Onetomap meta-data repository describes the content of clinical research databases used in research collaborations between multiple research groups and the Department of Surgery at the University of South Florida. Our goal is to develop a centralized inventory that enables users to locate datasets containing the data elements they seek across several datasets, allowing for more efficient and wide-ranging analysis. Of importance, we provide information on datasets with the potential to be linked with other datasets, be they focused on patients, hospitals, the environment, or social determinants of health. Ultimately, our goal is to help researchers evaluate not only research questions focused on hospital environments, but allow for the evaluation the macro-environment surrounding the entire healthcare pathway.

Institutional collaborations are welcome. Please see details in the <a href="#contributing_section">Contributing section</a>.


<p align="right">(<a href="#top">back to top</a>)</p>


## Getting Started

The Onetomap project currently hosts over 40 healthcare-related databases that can be used to address clinical research questions with focus on outcomes, quality improvement, and healthcare delivery. These include:

-  AHA - American Hospital Association Annual Survey database
-  AHRF - Area Health Resources Files
-  AMGA - Advancing High Performance Health Medical Group Compensation and Productivity Survey
-  BCSC - Breast Cancer Surveillance Consortium
-  Care of Chronically Ill Patients
-  CDC SVI - Centers for Disease Control and Prevention, Social Vulnerability Index
-  CMS (Centers for Medicare & Medicaid Services) – Hospital Compare
-  CMS – Physician Compare
-  CMS HCRIS - Healthcare Cost Report Information System
-  CMS Provider Utilization and Payment Data Physician and Other Supplier 
-  CHRR - County Health Rankings Data
-  COVID19 Data
-  DCI - Distressed Communities Index Dataset
-  FL AHCA - Florida Agency for Healthcare Administration
-  HCUP KID - Healthcare Cost and Utilization Project, Kids’ Inpatient Database
-  HCUP NIS - National Inpatient Sample
-  HCUP NRD - Nationwide Readmissions Database
-  HCUP SASD - State Ambulatory Surgery and Services Databases
-  HCUP SEED - State Emergency Department Databases
-  HCUP SID - State Inpatient Database 
-  HIMSS - Healthcare Information and Management Systems Society
-  HSAF - Hospital Services Area Files
-  Intermacs Data - Interagency Registry for Mechanically Assisted Circulatory Support
-  Lown Institute Hospital Index
-  MBSAQIP - Metabolic and Bariatric Surgery Accreditation and Quality Improvement Program
-  MEPS - Medical Expenditure Panel Survey
-  MIMIC - Medical Information Mart for Intensive Care
-  NCDB Dataset - National Cancer Database
-  NHATS - National Health and Aging Trends Study
-  NPDB - National Practitioner Data Bank
-  NSQIP - National Surgical Quality Improvement Program
-  NTDB - National Trauma Database
-  NY SPARCS - Statewide Planning and Research Cooperative System
-  OIG LEIE - Office of Inspector General's List of Excluded Individuals and Entities 
-  RAND corporation
-  SEER - Surveillance, Epidemiology, and End Results Program 
-  STAR - Standard Transplant Analysis and Research Files
-  Texas Hospital Discharge Data
-  USPS Zip Code database - United States Postal Service
-  Vermont Hospital Discharge Data
-  WRDS Bond Data - Wharton Research Data Services 

To see details about each one of these, please check the [Wiki for this repository](https://github.com/onetomapanalytics/Meta_Data/wiki) 


### Meta-data description 

Each dataset is described using the following fields:  

| **Field** | **Description** | **Example based on N3C database** |
|---|---|---|
| **1. General description** |  |  |
| *a. Database primary purpose* | Main objective of the existence of the database  | Provide a large, centralized data resource to allow research teams to study COVID-19 and identify potential treatments as the pandemic evolves. |
| *b. Overall data type* | Type of document where the data is presented (e.g. hospital expenditures, demographics) | Health outcomes |
| *c. Dataset type* | Type of register of the dataset considering the focused subject and the period of time (e.g. longitudinal, cross-sectional) | Longitudinal |
| *d. Data source* | Type of source from where the data was extracted (e.g. claims data, clinical trials) | Electronic Health Records (EHR) |
| *e. Data level* | Minimal level of collection of data (e.g. hospital level, patient level) | Patient level |
| *f. Geographic location of the data collection sites* | Country and institutions from where data was collected | United States;  List of institutions available in https://ncats.nih.gov/n3c/resources/data-contribution/data-transfer-agreement-signatories |
| *g. Sponsor, manager, or home institution* | Institutions related to the funding, management and maintenance of the project | National Center for Advancing Translational Sciences (NCATS); National Institutes of Health (NIH) |
| *h. Date range* | Time interval of data register and/or availability | Jan 1, 2018 to most recent data partner extraction date |
| *i. Geolocation data* | Zip codes, ZCTA, county | Zip codes for patients available under the limited dataset |
| *j. Dates* | Dates availability (day, month, year) | Available under the limited dataset |
| *k. Hospital identifiers* | Code that identifies the hospitals involved in the dataset | Synthetic data partner ID |
| *l. NPI* | If available. National Provider Identifier (NPI) is a unique identification number for covered health care providers. | No |
| *m. Physician identifiers* | Code that identifies the physician involved in the database | Synthetic provider ID |
| *n. Longitudinal tracking* | Pattern used by the dataset to track patients within and across hospitals and/or to track providers | Track patients within and across participating hospitals on the inpatient, outpatient, ED, and office levels. And track providers across 45 hospitals that currently provide the provider ID and hospitals using the occurrences (e.g., visit, procedure) and the above-mentioned IDs.  |
| *o. Financial variables* | Categories of financial related variables contained in the dataset | None |
| *p. Clinical areas of interest* | OMOP-CDM concepts that classify the database | All clinical areas |
| *q. Number of records* | Quantitative measure of data in the dataset  | N3C contains information on approximately 15.5 million anonymized persons as of Sep 8th, 2022. The Enclave has 18.1 billion total rows (Sep 2022) containing more than 6 million COVID+ cases, 1.6 billion clinical observations, 8.5 billion lab results, 2.8 billion medication records, 849.4 million procedures, and 916.0 million visits |
| *r. Variables that are uniquely present in this dataset* | Unusual type or exclusive information provided by the dataset | COVID variables, inpatient medications, drugs in general, labs, zip codes and dates for patients in the limited dataset, and connection among inpatient, outpatient, ED, and office data |
| *s. Database caveats and limitations* | Limitations presented by the database | (1) Hospitals cannot be identified, as defined by the Data Use Agreement (DUA); (2) it is restricted to patients who have undergone a COVID test; (3) all instances of a condition or procedure might be mapped to different OMOP-CDM concepts; (4) lab results values are not necessarily consistent across hospitals |
| *t. Other* | Other important informations about the database | Accordingly to the user and access requirements, there are three types of datasets available that vary in contents: *Limited* - patient data retain PHI such as dates and zip codes. *De-identified* - PHI are changed to protect patients' privacy. *Synthetic* - data derived from the limited dataset that statistically resemble patient information but are not real patient data. |
| **2. Applicable methods** | List of examples of data science methods that can be used with the dataset based on published articles | Association, such as logistic regression models; machine learning; propensity scores; and sensitivity analysis |
| **3. High impact designs** | List of examples of published high-impact articles that used the dataset | [Evaluate COVID-19 severity and risk factors](https://pubmed.ncbi.nlm.nih.gov/34255046/)  |
| **4. Data dictionary** | Detailed description about the content of dataset's domains | N3C data dictionary is available at https://github.com/onetomapanalytics/Meta_Data/wiki/N3C---Data-dictionary  |
| **5. Variable categories** | Group of variables contained in the dataset | Informations about patient demographics, biological samples, death, visits, procedures, drug exposure, device exposure, condition occurrence, measurements, observation, and COVID-19 test |
| **6. Linkage to other datasets** | Suggestions of datasets linkage based on their characteristics | Linkages can be established for any dataset that might have environmental or Social Determinants of Health (SDoH) information |


## Roadmap

So far we have completed an initial description of the meta-data for the following datasets:

- [X] AHA 
- [X] AHRF
- [ ] AMGA
- [X] BCSC Hormone therapy
- [X] BCSC Risk estimation
- [X] BCSC Risk Factors
- [ ] Care of Chronically Ill Patients
- [ ] CBECS
- [X] CDC SVI
- [X] CMS Hospital Compare
- [X] CMS Physician Compare
- [X] CMS HCRIS
- [X] CMS Provider Utilization and Payment Data Physician and Other Supplier 
- [X] CHRR
- [ ] COVID19 Data
- [X] DCI 
- [ ] DRG
- [ ] Feeding America
- [X] FL AHCA
- [ ] Gun violence
- [X] HCUP KID
- [X] HCUP NIS
- [X] HCUP NRD
- [ ] HCUP SASD
- [X] HCUP SEED
- [X] HCUP SID 
- [X] HIMSS
- [X] HSAF
- [X] Intermacs Data
- [ ] Kaiser Hospital Network
- [ ] Lown Institute Hospital Index
- [X] MBSAQIP
- [X] MEPS
- [ ] MIMIC
- [X] N3C
- [X] NCDB
- [ ] NHATS 
- [ ] NORC
- [X] NPDB
- [X] NSQIP 
- [X] NTDB 
- [X] NY SPARCS 
- [ ] OIG LEIE  
- [X] RAND
- [ ] Scotland data
- [X] SEER 
- [X] STAR
- [X] Texas Hospital Discharge Data
- [ ] USPS Zip Code database 
- [ ] Vermont Hospital Discharge Data
- [X] WRDS Bond Data  


<p align="right">(<a href="#top">back to top</a>)</p>


## How to find a database to answer your clinical research question using the One-to-Map meta-data repository on Github
 
<!-- @todo wait until we have the host page (i.e., github or bitbucket) and then create the animated gifs -->

1. Navigate to the [repository or organization page](https://github.com/onetomapanalytics/Meta_Data), type what you are looking for into the search field at the top of the page, and press Enter.

<!-- ![search](figures/add_figure) -->

2. The search will return the fields "Code", "Commits", "Issues", "Discussions", "Packages", and "Wikis". In front of each field is the number of results for your search in that field. Click on "Wiki."

<!-- ![search](figures/add_figure) -->

3. To make your search more specific, you can use Boolean terms like so:

* OR: use this term between similar keywords (i.e., synonyms, acronyms, and variations in spelling within the same idea or concept) or to look for different names representing the same concept. For example, `registry OR database OR claim OR cohort` will search for one of the concepts.
* AND: use this term to link ideas and concepts where you want to see both ideas or concepts showing up simultaneously in your search results. For example, `claims AND patient level` searches for claims databases with patient level data. Instead, `claims AND (patient level OR hospital level)` searches for claims databases with both patient and hospital level data. 
* NOT: use this term to exclude specific keywords from the search. For example, `patient level NOT claims` searches for patient-level data across all meta-data information with the exception of claims, e.g., EHR, surveys, registry/cohort, and randomized trials. 

<!-- ![search](figures/add_figure) -->

4. Place phrases in quotes to search for a set of words in that precise order. For example, "National Center for Biotechnology Information" will return the exact phrase instead of national AND center AND for AND biotechnology AND information. 
*Note*: This tool will improve results, but GitHub search doesn't support exact matching. <!-- @ I don't understand this either --> <!-- @Ricardo, o próprio github diz que não suporta exact matching. Eu fiz vários teste e usar as aspa melhora o filtro sim, mas não "garante" a busca pelo termo exato igual acontece com o pubmed. Buscar "generalized linear regression models" no github ainda vai retornar resultados só com "regression", mas menos do que se colocar sem aspas -->

<!-- ![Example](figures/add_figure) -->


**Limitations:**

- Queries longer than 256 characters are not accepted
- You cannot construct a query using more than five AND, OR, or NOT operators


## <a id="contributing_section">Contributing</a>

If you are interested in a research collaboration with the Onetomap group, please fill out this [form](https://docs.google.com/forms/d/e/1FAIpQLSe3fuuDl9KfPpajeae-voUxlbVIVlGj3RMYb7mw-GrPhQL_rg/viewform?usp=sf_link). 

<p align="right">(<a href="#top">back to top</a>)</p>


## License

All information distributed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License. See [License](https://github.com/onetomapanalytics/Meta_Data/blob/main/LICENSE.md) for more information. Each dataset retains its own original license.

<p align="right">(<a href="#top">back to top</a>)</p>


## Contact

<a href="onetomapanalytics@gmail.com">onetomapanalytics@gmail.com</a>

Paul C. Kuo, MD, MS, MBA - Professor, Department of Surgery, University of South Florida - <a href="paulkuo@usf.edu">paulkuo@usf.edu</a>

Haroon M Janjua, MSc - Director Surgical Data Analytics, University of South Florida - <a href="hmjanjua@usf.edu">hmjanjua@usf.edu</a>

Project Link: [https://github.com/onetomapanalytics/](https://github.com/onetomapanalytics/) 

<p align="right">(<a href="#top">back to top</a>)</p>


## Acknowledgments

* [USF Health](https://health.usf.edu/)
* [SporeData](https://sporedata.com/)


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links 
[contributors-shield]: https://img.shields.io/github/contributors/onetomapanalytics/Meta_Data.svg?style=for-the-badge
[contributors-url]: https://github.com/onetomapanalytics/Meta_Data/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/onetomapanalytics/Meta_Data.svg?style=for-the-badge
[forks-url]: https://github.com/onetomapanalytics/Meta_Data/network/members
[stars-shield]: https://img.shields.io/github/stars/onetomapanalytics/Meta_Data.svg?style=for-the-badge
[stars-url]: https://github.com/onetomapanalytics/Meta_Data/stargazers
[issues-shield]: https://img.shields.io/github/issues/onetomapanalytics/Meta_Data.svg?style=for-the-badge
[issues-url]: https://github.com/onetomapanalytics/Meta_Data/issues
[license-shield]: https://img.shields.io/github/license/onetomapanalytics/Meta_Data.svg?style=for-the-badge
[license-url]: https://github.com/onetomapanalytics/Meta_Data/blob/master/LICENSE.txt
[website-shield]: /website?down_color=lightgrey&down_message=offline&up_color=blue&up_message=online&url=https%3A%2F%2Fshields.io
[website-url]: https://www.onetomapanalytics.com/
[product-screenshot]: images/screenshot.png-->
