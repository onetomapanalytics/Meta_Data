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
-  CHR - County Health Rankings Data
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


| **Field**                                                | **Description and examples**                                                                                                                        |
|----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. General description                         |         |                                               
|   a. Database primary purpose      | e.g., develop networks or infrastructure, provide a longitudinal population health dataset, drive policy-making, hospital reimbursement information |
|   a. Overall data type                                    | health facilities, hospital expenditures, demographics, health outcomes, SDOH, economics, environment                                               |
|   b. Dataset type                                         | longitudinal or cross-sectional                                                                                                                     |
|   c. Data source                                          | EHR, Claims, Registry/cohort, randomized trials, survey, satellite                                                                                  |
|   d. Data level                                           | patient level or hospital level                                                                                                                     |
|   e. Geographic location of the data collection sites     |                                                                                                                                                     |
|   f. Sponsor, manager, or home institution                | govern, agency, department                                                                                                                          |
|   g. Date range                                           |                                                                                                                                                     |
|   h. Geolocation data                                     | Zip codes, ZCTA, county                                                                                                                             |
|   i. Dates                                                |                                                                                                                                                     |
|   j. Hospital identifiers                                 |                                                                                                                                                     |
|   k. NPI                                                  |                                                                                                                                                     |
|   l. Longitudinal tracking                                | Track patients within hospitals, Track patients across hospitals, Track providers                                                                   |
|   m. Financial variables                                  |                                                                                                                                                     |
|   n. Clinical areas of interest                           | Use omop-cdm concepts to classify the databases                                                                                                     |
|   o. Number of records                                    |                                                                                                                                                     |
|   p. Variables that are uniquely present in this dataset  |                                                                                                                                                     |
|   q. Database caveats and limitations                     | List overall limitations                                                                                                                            |
|   r. Other                                                |                                                                                                                                                     |
| 2. Applicable methods                                    | Which Data Science methods can be used with this dataset                                                                                            |
| 3. High impact designs and novel variables               | High impact publications                                                                                                                         |
| 4. Data dictionary                                       |                                                                                                                                                     |
| 5. Variable categories                                   | Patient demographiscs, hospital discharge records, charges, diagnosis                                                                               |
| 6. Linkage to other datasets                             |                                                                                                                                                     |
| 7. Missing data patterns                                 |                                                                                                                                                     |


## Roadmap

So far we have completed an initial description of the meta-data for the following datasets:

- [X] AHA 
- [ ] AHRF
- [ ] AMGA
- [ ] BCSC
- [ ] Care of Chronically Ill Patients
- [ ] CDC SVI
- [X] CMS Hospital Compare
- [ ] CMS Physician Compare
- [ ] CMS HCRIS
- [ ] CMS Provider Utilization and Payment Data Physician and Other Supplier 
- [ ] CHR 
- [ ] COVID19 Data
- [X] DCI 
- [X] FL AHCA
- [ ] HCUP KID
- [ ] HCUP NIS
- [ ] HCUP NRD
- [ ] HCUP SASD
- [ ] HCUP SEED
- [X] HCUP SID 
- [ ] HIMSS
- [ ] HSAF
- [ ] Intermacs Data
- [ ] Lown Institute Hospital Index
- [ ] MBSAQIP
- [ ] MEPS
- [ ] MIMIC
- [ ] NCDB Dataset 
- [ ] NHATS 
- [ ] NPDB
- [ ] NSQIP 
- [ ] NTDB 
- [X] NY SPARCS 
- [ ] OIG LEIE  
- [ ] RAND
- [ ] SEER 
- [ ] STAR
- [ ] Texas Hospital Discharge Data
- [ ] USPS Zip Code database 
- [ ] Vermont Hospital Discharge Data
- [ ] WRDS Bond Data  


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
