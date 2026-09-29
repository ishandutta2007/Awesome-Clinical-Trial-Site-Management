# Awesome-Clinical-Trial-Site-Management

## Top Clinical Trial Site Management Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Site Enablement, eRegulatory Binders, Financial Management & Multi-Sponsor Operations*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Clinical Trial Site Management**. These tools help research sites, site networks, and academic medical centers manage regulatory documents, patient visits, study budgets, and sponsor relationships across multiple concurrent trials.



**Examples** include Florence Healthcare, RealTime-CTMS, Clinical Conductor, Advarra OnCore, SiteVault, Complion, Trial Interactive, CRIO, ClinPlus, and SimpleTrials (the category leaders).



**Open-source emphasis**: Clinical trial site management has a **modest but meaningful open-source ecosystem**. **Phoenix CTMS** (51 stars, 35 forks) is an active Java-based CTMS/PRS/CDMS . **LibreClinica** is the community successor to OpenClinica, providing EDC and CDM capabilities . The **clinicedc** ecosystem offers modular Django packages for building custom site workflows . This section documents these self-hostable solutions and their practical applications.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Florence Healthcare](https://florencehc.com/)**

  Leading **Site Enablement Platform** used by 65,000 study sites across 90+ countries. Provides eRegulatory binders (eISF), remote site access for sponsors, eConsent, eSource capture, and document management. FDA 21 CFR Part 11 compliant, ICH GCP E6(R2), EU Annex 11, and MHRA Data Integrity Guidance certified. eBinders platform reduces document cycle times by 40% . Strategic integrations with Cognizant Shared Investigator Platform (SIP) enable seamless sponsor-to-site document exchange .



- **[RealTime-CTMS](https://realtime-ctms.com/)**

  Cloud-based CTMS designed **specifically for research sites and SMOs** rather than sponsors. Focuses on site-side operational workflows: patient recruitment, coordinator scheduling, visit tracking, regulatory document management, and financial management of site budgets and payments. Strong adoption among SMOs managing multiple sponsor relationships simultaneously .



- **[Clinical Conductor](https://www.advarra.com/)**

  **The leading CTMS for top academic medical centers and cancer centers**. Two linked components: **Clinical Conductor Enterprise (CCE)** for trial managers (study building, fee linkage, reporting, finances) and **Clinical Conductor Site (CCS)** for coordinators (patient management, visits). Used by hundreds of research sites globally. Advarra acquired Bio-Optronics to pair Clinical Conductor with IRB services . Offers CCText (two-way patient messaging) and CCPay (patient payment system) add-ons .



- **[Advarra OnCore](https://www.advarra.com/)**

  Enterprise CTMS within Advarra's connected research network. Integrates with Advarra's IRB services and credentials for site activation at scale. Offers financial management, analytics, and data management .



- **[SiteVault](https://www.veeva.com/)**

  Veeva's site-focused platform for regulatory document management and eISF. Integrates with Veeva eTMF for sponsor-to-site document exchange.



- **[Complion](https://complion.com/)**

  Site-focused eRegulatory and eISF platform. Provides document management, eSignatures, and compliance tracking for research sites.



- **[Trial Interactive](https://www.transperfect.com/)**

  eTMF and site document exchange platform with translation and linguistic validation services.



- **[CRIO](https://www.crioclinical.com/)**

  Leader in **eSource technology** supporting 2,000+ global medical research sites. Provides a holistic paperless platform for conducting clinical trials, reducing data errors, streamlining regulatory workflows, and accelerating timelines. Partnership with Sitero offers turnkey services and technology including eConsent, eRegulatory/eISF, eSource, and patient stipends .



- **[ClinPlus](https://clinplus.com/)**

  CTMS and data management platform for research sites and sponsors.



- **[SimpleTrials](https://simpletrials.com/)**

  CTMS for small to mid-sized research sites. Provides study management, budgeting, and regulatory document tracking.



## Open-Source GitHub Projects



- **[Phoenix CTMS](https://github.com/phoenixctms/ctsms)**

  **The most actively developed open-source CTMS.** **51 GitHub stars, 35 forks, Java-based** . Described as "the ultimate CTMS/PRS/CDMS" (Clinical Trial Management System / Patient Recruitment System / Clinical Data Management System) . Provides comprehensive clinical trial management capabilities including study setup, patient management, and data capture. Actively maintained (updated within the last week as of September 2026) . Java stack with 47.4 MB repository size . **Open source**.



- **[LibreClinica](https://github.com/reliatec-gmbh/LibreClinica)**

  **Community-driven successor to OpenClinica**, providing open-source clinical trial software for **Electronic Data Capture (EDC) and Clinical Data Management (CDM)** . Supports study building, eCRF design, data validation, audit trails, and CDISC ODM-XML export. **LGPL-3.0**, Java-based. 40 GitHub stars. While primarily EDC-focused, it provides the data management foundation for site operations .



- **[clinicedc](https://github.com/clinicedc)**

  **Modular Django-based clinical trial data management framework.** Provides a collection of Python packages for building EDC/eSource systems, including appointment scheduling (`edc-appointment`), visit tracking (`edc-visit-schedule`), patient registration (`edc-registration`), adverse events (`edc-adverse-event`), and dashboards (`edc-dashboard`). The `edc` core module has 28 stars and 3.48k monthly downloads . Used in NIH-funded trials at Harvard T.H. Chan School of Public Health and Botswana-Harvard AIDS Institute Partnership. **GPL-3.0**. Provides building blocks for custom site management workflows .



- **[OpenClinica](https://github.com/OpenClinica/OpenClinica)**

  **The world's first commercial open-source clinical trial software** for EDC and CDM. 401 GitHub stars, updated 3 months ago . Provides study design, eCRF creation, data capture, validation rules, and audit trails. Community edition available; enterprise version offers additional modules including ePRO and CTMS integration .



- **[CORTEX (Clinical ORder and Trial EXecution)](https://github.com/)** 

  Open-source clinical trial management platform. Early-stage project focused on site operations and trial execution.



- **[FreeMED](https://github.com/freemed/freemed)**

  **FreeMED Electronic Medical Record / Practice Management System.** 101 GitHub stars . While primarily an EMR, it provides practice management capabilities that can be adapted for clinical research site administration.



### Additional Strong Open-Source Options



- **CTMS/PRS/CDMS**: **Phoenix CTMS** (most active, Java, 51 stars), **LibreClinica** (EDC/CDM, LGPL-3.0) .

- **EDC Foundations**: **OpenClinica** (401 stars, commercial open-source), **clinicedc** (modular Django packages) .

- **Site Workflow Building Blocks**: **edc-appointment** (scheduling), **edc-visit-schedule** (visit tracking), **edc-registration** (patient intake), **edc-adverse-event** (safety tracking) .

- **EMR/PM Integration**: **FreeMED** (EMR/PM system adaptable for research sites) .



**Frameworks for building custom systems**: Combine **Phoenix CTMS** for comprehensive trial management, **LibreClinica** for EDC/CDM, and **clinicedc** packages for custom Django-based site workflows (appointment scheduling, visit tracking, patient registration). Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Clinical trial site management platforms handle sensitive patient and regulatory data; ensure compliance with 21 CFR Part 11, ICH-GCP, HIPAA, GDPR, and applicable regional regulations.

- **Open-source reality**: The open-source ecosystem for clinical trial site management is **developing but not yet equivalent to commercial platforms**. **Phoenix CTMS** provides an actively maintained CTMS/PRS/CDMS foundation . **LibreClinica** and **OpenClinica** deliver EDC/CDM capabilities . **clinicedc** offers modular Django packages for custom site workflows . However, commercial platforms (Florence, RealTime-CTMS, Clinical Conductor) provide deeper site enablement features — eRegulatory binders, sponsor connectivity, financial management, and multi-sponsor operations — that open-source alternatives cannot match without significant institutional investment.



---



**Made for research coordinators, site administrators, clinical trial managers, and academic medical center IT teams.**

Let's make clinical trial site management more open, transparent, and site-centric.
