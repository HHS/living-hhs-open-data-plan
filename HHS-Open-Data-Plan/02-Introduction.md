# Living HHS Open Data Plan

**Version 1.0**  
**Updated July 22, 2025**  

U.S. Department of Health and Human Services (HHS), Office of the Chief Data Officer (OCDO).  

This multi-year Living Plan details how HHS intends to use data in service to its mission to enhance the health and well-being of all Americans. As part of this document, HHS explains the reasons why the Living HHS Open Data Plan exists and the rules it must follow for implementation success, while sharing credit with the HHS team that worked hard to create it.  

**Recommended citation:** HHS OCDO. 2025. Living HHS Open Data Plan, version 1.0. <https://github.com/HHS/living-hhs-open-data-plan>.  

The Living HHS Open Data Plan responds to Office of Management and Budget (OMB) guidance on implementation of the Open, Public, Electronic, and Necessary (OPEN) Government Data Act, also known as Title II of the Foundations for Evidence-Based Policymaking Act (Evidence Act) of 2018[^1]. OMB Memorandum M-25-05, “[Phase 2 Implementation of the Foundations for Evidence-Based Policymaking Act of 2018: Open Data Access and Management](https://www.whitehouse.gov/wp-content/uploads/2025/01/M-25-05-Phase-2-Implementation-of-the-Foundations-for-Evidence-Based-Policymaking-Act-of-2018-Open-Government-Data-Access-and-Management-Guidance.pdf),” outlines a systematic approach to open data that will better facilitate data access, subject to appropriate safeguards for privacy, confidentiality, and security. This document addresses requirements in the OPEN Government Data Act related to agency data being open by default, maintenance of agency comprehensive data inventories, dissemination of agency data via the Federal Data Catalog, maintenance of agency open data plans, and agency engagement with the public[^2].  

[^1]: Foundations for Evidence-Based Policymaking Act of 2018. Public Law No: 115-435. <https://www.congress.gov/bill/115th-congress/house-bill/4174>
[^2]: <https://www.cdo.gov/phase-2-of-foundations-for-evidence-based-policymaking-act>

This work also advances HHS implementation of the Source code Harmonization And Reuse in Information Technology Act (SHARE IT Act)[^3] of 2024, mandating Open Source and reuse of existing code. As a 2025 pilot between HHS and the Centers for Medicare & Medicaid Services (CMS), the HHS OCDO[^4] and Open Source Program Office[^5] of the Digital Service at CMS[^6] jointly developed the open-source version of the Living HHS Open Data Plan[^7] for efficiency through technology, transparency for the public, and data-driven delivery as a unified HHS.  

[^3]: <https://www.congress.gov/bill/118th-congress/house-bill/9566>
[^4]: <https://cdo.hhs.gov>
[^5]: <https://www.cms.gov/digital-service/open-source-program-office>
[^6]: <https://www.cms.gov/digital-service>
[^7]: <https://github.com/HHS/living-hhs-open-data-plan>

**HHS encourages public engagement and input on the Living HHS Open Data Plan via GitHub:** <https://github.com/HHS/living-hhs-open-data-plan>  

Alternately, for inquiries and feedback, please contact: [cdo@hhs.gov](mailto:cdo@hhs.gov)  

---

**ACKNOWLEDGEMENTS**  
Over 30 individuals contributed as co-authors, editors, and contributors to this Living Open Data Plan, which the HHS Data Governance Board (DGB) approved and received concurrence from all HHS Divisions in July 2025. Special thanks to core co-authors and contributors:

| **Contributors**                     | **Contributors**                      |
|--------------------------------------|---------------------------------------|
| **Allen, Jelena** (CBHSQ/SAMHSA/HHS) | **Kleinstreuer, Nicole** (OD/NIH/HHS) |
| **Beach, Thomas** (ODAR/FDA/HHS) | **Layden, Jennifer** (OD/CDC/HHS) |
| **Blase, Alec** (ASTP/OS/HHS) | **Mandel, Grace** (OD/CDC/HHS) |
| **Broussard, Cheryl** (OD/CDC/HHS) | **Minor, Clark** (IOS/HHS) |
| **Callahan, Kenneth** (IOS/HHS) | **Mohan, Chandra** (OMTO/SAMHSA/HHS) |
| **Caponiti, Anthony** (ASTP/OS/HHS) | **Morris, Christopher** (KME/ACF/HHS) |
| **Carrazana, Dorn** (CDRH/FDA/HHS) | **Ogilvie, Jessica** (OD/CDC/HHS) |
| **Cono, Joanne** (OD/CDC/HHS) | **Pishko, Gregory** (ODAR/FDA/HHS) |
| **DeCausemaker, Remy** (DSAC/CMS/HHS) | **Posnack, Steve** (ASTP/OS/HHS) |
| **Dillion, Christopher** (NCATS/NIH/HHS) | **Ramanathan Holiday, Tara** (OD/CDC/HHS) |
| **German, Claire** (ASTP/OS/HHS) | **Ritchey, Matthew** (OD/CDC/HHS) |
| **Gleason, Amy** (OD/CMS/HHS) | **Snyder, John** (HRSA/HHS) |
| **Gregurick, Susan** (OD/NIH/HHS) | **Supplee, Lauren** (KMA/ACF/HHS) |
| **Honey, Kristen** (ASTP/OS/HHS) | **Thomson, Alastair** (TIO/ARPA-H/HHS) |
| **Isaacman-Beck, Jesse** (ASTP/OS/HHS) | **Thornbrugh, Mitchell** (IHS/HHS) |
| **Jani, Pooja** (CDRH/FDA/HHS) | **Trotter, Fred** (OD/CMS/HHS) |
| **Juluru, Krishna** (CDRH/FDA/HHS) | **Vigneshwaran, Shanthi** (ODAR/FDA/HHS) |
| **Keane, Thomas** (ASTP/OS/HHS) | **Walsh, Jeremy** (OC/FDA/HHS) |
| **Kessler, Natalie** (OD/CDC/HHS) | **Ware, Deanna** (OA/HRSA/HHS) |
| **Kirilusha, Anthony** (OD/NIH/HHS) |  |

Submitted to OMB by **Kristen Honey**, HHS Chief Data Officer, with HHS concurrence including reviews by:  
**Peter Bowman-Davis**, Chief AI Officer and ASTP Counselor (IOS/HHS)  
**Kenneth Callahan**, HHS Senior Advisor for Policy and Implementation (IOS/HHS)


_**Note:** This Living HHS Open Data Plan is not intended to be comprehensive of all data-related work being done at HHS. This information is additive to currently active work and intend to further boost HHS's progress in leveraging data in support of its mission. Given the multi-year time frame of this Living Plan, efforts are subject to review and possible change to maintain alignment with the President’s Management Agenda, HHS Secretary Priorities, and the interagency Federal CDO Council[^8]._

[^8]: <https://www.cdo.gov>

---
## Message from the HHS Chief Data Officer—People First, Data Always!

Fifteen years ago, HHS led the federal Open Data movement and launched [HealthData.gov](https://healthdata.gov/), the home of HHS Open Data. Now in 2025, HHS has renewed focus on Open Data and released the [Living HHS Open Data Plan on GitHub](https://github.com/HHS/living-hhs-open-data-plan)[^9] with [HealthData.gov](https://healthdata.gov/) refresh, including three Evidence Act milestones:  

[^9]: <https://github.com/HHS/living-hhs-open-data-plan>

1. [HHS Open Data Plan](https://healthdata.gov/HHS/HHS-Open-Data-Plan/m9xc-txya) (version 1.0, discoverable as a new HealthData.gov data asset)  
2. [HHS Metadata Standard](https://healthdata.gov/HHS/HHS-Data-Inventory/kaw8-4tez) (version 1.0)  
3. [HHS Data Inventory](https://healthdata.gov/HHS/HHS-Data-Inventory/kaw8-4tez) (version 1.0, metadata catalog of public and non-public data assets)  

American taxpayers fund HHS data and information, making it essential that certain resources are democratized—easily discoverable, machine-readable, and freely accessible to all. All Americans have a right to their personal health data and certain information that underpins the Department’s operations, federally funded research, and broader “open” initiatives—including partnerships, citizen science, crowdsourcing, prizes, and innovation challenges fueled by HHS Open Data. With the maturation of multiple open communities, HHS is poised to link synergistic ecosystems for impact.  
 
* Open Data: [Data.gov](https://data.gov/) and [HealthData.gov](https://healthdata.gov/)  
* Open Government: [Open.USA.gov](https://www.gsa.gov/governmentwide-initiatives/us-open-government)  
* Open Innovation: [Challenge.gov](https://challenge.gov/)  
* Open Science: [Science.gov](https://www.science.gov/)  
* Open Source Code: [Code.gov](https://code.gov/) and [HHS GitHub](https://github.com/HHS)

HHS embraces continuous improvements to increase its ability to transform raw data into actionable insights that guide decisions across all levels of the Department. To support this, the HHS Chief Data Officer (CDO), HHS Chief Technology Officer (CTO), Chief Information Officer (CIO), Chief Artificial Intelligence Officer (CAIO), and data leaders within HHS defined shared values for HHS Open Data. Common values aid in navigating change and challenges. The HHS workforce, interagency partners, and external collaborators may differ on data priorities or interpretations, yet we can all unite around values that drive progress and collaboration with a “sharing by default” culture and “open by default” data ethos, to the extent permitted by law for ethical modernization.

Core values underpin the HHS Open Data community, underlying every aspect of this plan.  
1. **TRANSPARENCY:** Openness by default.  
2. **PURPOSE:** Data must serve the public good.  
3. **RELENTLESS OPTIMIZATION:** Adapt, refine, and improve using agile methods, two-way feedback, a growth mindset, and accountability.  
4. **EXCELLENCE:** Real-world evidence with standards driving impact.  
5. **RESPECT:** People and patients as equal partners.  
6. **INTEGRITY:** Find the truth. Tell the truth.

Thank you to everyone who has contributed to the HHS Open Data ecosystem—a community of solvers, collaboratively co-creating a more transparent, accountable, and responsive HHS. We have incredible opportunity to responsibly share data, eliminate silos, modernize government, and drive progress through partnerships and emerging technologies like Artificial Intelligence (AI). All are welcome—join us! People first, data always!


&mdash; [Kristen Honey, PhD, PMP](https://www.healthit.gov/leadership/kristen-honey), HHS Chief Data Officer, [HHS Office of the Chief Data Officer](https://cdo.hhs.gov/s/)[^10]

[^10]: <https://cdo.hhs.gov>

[Back to Table of Contents](#table-of-contents)
