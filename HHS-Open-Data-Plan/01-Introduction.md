# Living HHS Open Data Plan

**Version 1.0**
**Updated July 15, 2025**

Copyright Information
&copy; 2025 Department of Health and Human Services (HHS). All rights reserved.

This document is published under the authority of Title II of the Foundations for Evidence-Based Policymaking Act of 2018 (OPEN Government Data Act)[^1]. 
Citation of this document is encouraged, provided proper attribution is given to HHS. For inquiries or feedback, please contact: [cdo@hhs.gov](mailto:cdo@hhs.gov)

[^1]:Foundations for Evidence-Based Policymaking Act of 2018. Public Law No: 115-435.  https://www.congress.gov/bill/115th-congress/house-bill/4174

**Public contributions to iterations of the Living HHS Open Data Plan are encouraged via GitHub.**

**ACKNOWLEDGEMENTS**
Over 30 individuals contributed as co-authors and editors to this Living Open Data Plan, which the HHS Data Governance Board (DGB) approved with concurrence 
from all Operating Divisions and Staff Divisions in June 2025. Special thanks to co-authors, editors, and contributors:
<table>
  <tr>
    <td>**Allen, Jelena** (CBHSQ/SAMHSA/HHS)</td>
    <td>**Kleinstreuer, Nicole** (OD/NIH/HHS)</td>
  </tr>
    <tr>
        <td>**Beach, Thomas** (ODAR/FDA/HHS)</td>
        <td>**Layden, Jennifer** (OD/CDC/HHS)</td>
    <tr>
        <td>**Blase, Alec** (ASTP/OS/HHS)</td>
        <td>**Mandel, Grace** (OD/CDC/HHS)</td>
    <tr>
        <td>**Broussard, Cheryl** (OD/CDC/HHS)</td>
        <td>**Minor, Clark** (IOS/HHS)</td>
    <tr>
        <td>**Callahan, Kenneth** (IOS/HHS)</td>
        <td>**Mohan, Chandra** (OMTO/SAMHSA/HHS)</td>
    <tr>
        <td>**Caponiti, Anthony** (ASTP/OS/HHS)</td>
        <td>**Morris, Christopher** (KME/ACF/HHS)</td>
    <tr>
        <td>**Carrazana, Dorn** (CDRH/FDA/HHS)</td>
        <td>**Ogilvie, Jessica** (OD/CDC/HHS)</td>
    <tr>
        <td>**Cono, Joanne** (OD/CDC/HHS)</td>
        <td>**Pishko, Gregory** (ODAR/FDA/HHS)</td>
    <tr>
        <td>**Decausemaker, Remy** (DSAC/CMS/HHS)</td>
        <td>**Posnack, Steve** (ASTP/OS/HHS)</td>
    <tr>
        <td>**Dillion, Christopher** (NCATS/NIH/HHS)</td>
        <td>**Ramanathan Holiday, Tara** (OD/CDC/HHS)</td>
    <tr>
        <td>**German, Claire** (ASTP/OS/HHS)</td>
        <td>**Ritchey, Matthew** (OD/CDC/HHS)</td>
    <tr>
        <td>**Gleason, Amy** (OD/CMS/HHS)</td>
        <td>**Snyder, John** (HRSA/HHS)</td>
    <tr>
        <td>**Gregurick, Susan** (OD/NIH/HHS)</td>
        <td>**Supplee, Lauren** (KMA/ACF/HHS)</td>
    <tr>
        <td>**Honey, Kristen** (ASTP/OS/HHS)</td>
        <td>**Thomson, Alastair** (TIO/ARPA-H/HHS)</td>
    <tr>
        <td>**Isaacman-Beck, Jesse** (ASTP/OS/HHS)</td>
        <td>**Thornbrugh, Mitchell** (IHS/HHS)</td>
    <tr>
        <td>**Jani, Pooja** (CDRH/FDA/HHS)</td>
        <td>**Trotter, Fred** (OD/CMS/HHS)</td>
    <tr>
        <td>**Juluru, Krishna** (CDRH/FDA/HHS)</td>
        <td>**Vigneshwaran, Shanthi** (ODAR/FDA/HHS)</td>
    <tr>
        <td>**Keane, Thomas** (ASTP/OS/HHS)</td>
        <td>**Walsh, Jeremy** (OC/FDA/HHS)</td>
    <tr>
        <td>**Kessler, Natalie** (OD/CDC/HHS)</td>
        <td>**Ware, Deanna** (OA/HRSA/HHS)</td>
    <tr>
        <td>**Kirilusha, Anthony** (OD/NIH/HHS)</td>
    </tr>
</table>

_**Note:** This living plan is not intended to be comprehensive of all data-related work being done at HHS. This information is additive to currently active work 
and intend to further boost HHS' progress in leveraging data in support of its mission. Given the multi-year time frame of this plan, efforts are subject to 
review and possible change to maintain alignment with the President’s Management Agenda, HHS Secretary Priorities, and HHS Data Vision._

---
## Message from the HHS Chief Data Officer—People First, Data Always!

Fifteen years ago, HHS led the federal Open Data movement and launched HealthData.gov, the home of HHS Open Data. With the publication of this Open Data Plan and 
a refreshed HealthData.gov launched in July 2025, HHS has refocused its efforts on open data and delivered on three milestones.
1. HHS Open Data Plan (this document)
2. HHS Metadata Standard (version 1.0)
3. HHS Data Inventory (version 1.0 metadata catalog of public and non-public data assets).

American taxpayers fund HHS data and information, making it essential that these resources are democratized—easily discoverable, machine-readable, and freely accessible 
to all. All Americans have a right to the information that underpins the Department’s operations, federally funded research, and broader “open” initiatives including 
partnerships, citizen science, crowdsourcing, prizes, and innovation challenges fueled by HHS Open Data. With the maturation of multiple open communities, HHS is poised 
in 2025 to link synergistic ecosystems for increased impact. 
- Open Data: [Data.gov](https://data.gov/) and [HealthData.gov](https://healthdata.gov/)
- Open Government: [Open.USA.gov](https://www.gsa.gov/governmentwide-initiatives/us-open-government)
- Open Innovation: [Challenge.gov](https://challenge.gov/)
- Open Science: [Science.gov](https://www.science.gov/)
- Open Source Code: [Code.gov](https://code.gov/) and [HHS GitHub repo](https://github.com/HHS)

HHS will improve its ability to transform raw data into actionable insights that guide decisions across all levels of the Department. To support this, the HHS Chief Data 
Officer (CDO) collaborated with data leaders to define shared values for navigating future challenges and change. While the HHS workforce, interagency partners, and 
external collaborators may differ on data priorities or interpretations, we can all unite around values that drive progress and collaboration with a “sharing by default” 
culture and “open by default” data ethos.

Core values underpin the HHS Open Data community, underlying every aspect of this plan.\
**1.    TRANSPARENCY:** Radical openness by default.\
**2.    PURPOSE:** Data that serves the public good.\
**3.    RELENTLESS OPTIMIZATION:** Adapt, refine, and improve using agile methods, two-way feedback, a growth mindset, and accountability.\
**4.    EXCELLENCE:** Real-world evidence drives impact.\
**5.    RESPECT:** People and patients as equal partners.\
**6.    INTEGRITY:** Find the truth. Tell the truth.

Thank you to everyone who has contributed to the HHS Open Data ecosystem—a community of solvers, collaboratively co-creating a more transparent, accountable, and responsive HHS. Today, we have incredible opportunity to responsibly share data, eliminate silos, modernize government, and drive progress through partnerships and emerging technologies like Artificial Intelligence (AI). All are welcome—join us! People first, data always!

<p align="right">&mdash; <a href="https://www.healthit.gov/leadership/kristen-honey">Kristen Honey, PhD, PMP</a>, HHS Chief Data Officer, <a href="https://cdo.hhs.gov/s/">HHS Office of the Chief Data Officer</a></p>
