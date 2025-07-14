# Living HHS Open Data Plan

__Version 1.0__\
__Updated July 15, 2025__

Copyright Information\
&copy; 2025 Department of Health and Human Services (HHS). All rights reserved.

This document is published under the authority of Title II of the Foundations for Evidence-Based Policymaking Act of 2018 (OPEN Government Data Act)[^1]. 
Citation of this document is encouraged, provided proper attribution is given to HHS. For inquiries or feedback, please contact: [cdo@hhs.gov](mailto:cdo@hhs.gov)

[^1]:Foundations for Evidence-Based Policymaking Act of 2018. Public Law No: 115-435.  https://www.congress.gov/bill/115th-congress/house-bill/4174

__Public contributions to iterations of the Living HHS Open Data Plan are encouraged via GitHub.__

__ACKNOWLEDGEMENTS__\
Over 30 individuals contributed as co-authors and editors to this Living Open Data Plan, which the HHS Data Governance Board (DGB) approved with concurrence 
from all Operating Divisions and Staff Divisions in June 2025. Special thanks to co-authors, editors, and contributors:
<table>
	<tr>
		<td><b>Allen, Jelena</b> (CBHSQ/SAMHSA/HHS)</td>
		<td><b>Kleinstreuer, Nicole</b> (OD/NIH/HHS)</td>
	</tr>
	<tr>
		<td><b>Beach, Thomas</b> (ODAR/FDA/HHS)</td>
		<td><b>Layden, Jennifer</b> (OD/CDC/HHS)</td>
	<tr>
		<td><b>Blase, Alec</b> (ASTP/OS/HHS)</td>
		<td><b>Mandel, Grace</b> (OD/CDC/HHS)</td>
	<tr>
		<td><b>Broussard, Cheryl</b> (OD/CDC/HHS)</td>
		<td><b>Minor, Clark</b> (IOS/HHS)</td>
	<tr>
		<td><b>Callahan, Kenneth</b> (IOS/HHS)</td>
		<td><b>Mohan, Chandra</b> (OMTO/SAMHSA/HHS)</td>
	<tr>
		<td><b>Caponiti, Anthony</b> (ASTP/OS/HHS)</td>
		<td><b>Morris, Christopher</b> (KME/ACF/HHS)</td>
	<tr>
		<td><b>Carrazana, Dorn</b> (CDRH/FDA/HHS)</td>
		<td><b>Ogilvie, Jessica</b> (OD/CDC/HHS)</td>
	<tr>
		<td><b>Cono, Joanne</b> (OD/CDC/HHS)</td>
		<td><b>Pishko, Gregory</b> (ODAR/FDA/HHS)</td>
	<tr>
		<td><b>Decausemaker, Remy</b> (DSAC/CMS/HHS)</td>
		<td><b>Posnack, Steve</b> (ASTP/OS/HHS)</td>
	<tr>
		<td><b>Dillion, Christopher</b> (NCATS/NIH/HHS)</td>
		<td><b>Ramanathan Holiday, Tara</b> (OD/CDC/HHS)</td>
	<tr>
		<td><b>German, Claire</b> (ASTP/OS/HHS)</td>
		<td><b>Ritchey, Matthew</b> (OD/CDC/HHS)</td>
	<tr>
		<td><b>Gleason, Amy</b> (OD/CMS/HHS)</td>
		<td><b>Snyder, John</b> (HRSA/HHS)</td>
	<tr>
		<td><b>Gregurick, Susan</b> (OD/NIH/HHS)</td>
		<td><b>Supplee, Lauren</b> (KMA/ACF/HHS)</td>
	<tr>
		<td><b>Honey, Kristen</b> (ASTP/OS/HHS)</td>
		<td><b>Thomson, Alastair</b> (TIO/ARPA-H/HHS)</td>
	<tr>
		<td><b>Isaacman-Beck, Jesse</b> (ASTP/OS/HHS)</td>
		<td><b>Thornbrugh, Mitchell</b> (IHS/HHS)</td>
	<tr>
		<td><b>Jani, Pooja</b> (CDRH/FDA/HHS)</td>
		<td><b>Trotter, Fred</b> (OD/CMS/HHS)</td>
	<tr>
		<td><b>Juluru, Krishna</b> (CDRH/FDA/HHS)</td>
		<td><b>Vigneshwaran, Shanthi</b> (ODAR/FDA/HHS)</td>
	<tr>
		<td><b>Keane, Thomas</b> (ASTP/OS/HHS)</td>
		<td><b>Walsh, Jeremy</b> (OC/FDA/HHS)</td>
	<tr>
		<td><b>Kessler, Natalie</b> (OD/CDC/HHS)</td>
		<td><b>Ware, Deanna</b> (OA/HRSA/HHS)</td>
	<tr>
		<td><b>Kirilusha, Anthony</b> (OD/NIH/HHS)</td>
	</tr>
</table>

___Note:__ This living plan is not intended to be comprehensive of all data-related work being done at HHS. This information is additive to currently active work 
and intend to further boost HHS' progress in leveraging data in support of its mission. Given the multi-year time frame of this plan, efforts are subject to 
review and possible change to maintain alignment with the President’s Management Agenda, HHS Secretary Priorities, and HHS Data Vision._

---
## Message from the HHS Chief Data Officer—People First, Data Always!

Fifteen years ago, HHS led the federal Open Data movement and launched HealthData.gov, the home of HHS Open Data. With the publication of this Open Data Plan and 
a refreshed HealthData.gov launched in July 2025, HHS has refocused its efforts on open data and delivered on three milestones.
1.	HHS Open Data Plan (this document)
2.	HHS Metadata Standard (version 1.0)
3.	HHS Data Inventory (version 1.0 metadata catalog of public and non-public data assets).

American taxpayers fund HHS data and information, making it essential that these resources are democratized—easily discoverable, machine-readable, and freely accessible 
to all. All Americans have a right to the information that underpins the Department’s operations, federally funded research, and broader “open” initiatives including 
partnerships, citizen science, crowdsourcing, prizes, and innovation challenges fueled by HHS Open Data. With the maturation of multiple open communities, HHS is poised 
in 2025 to link synergistic ecosystems for increased impact. 
-	Open Data: [Data.gov](https://data.gov/) and [HealthData.gov](https://healthdata.gov/)
-	Open Government: [Open.USA.gov](https://www.gsa.gov/governmentwide-initiatives/us-open-government)
-	Open Innovation: [Challenge.gov](https://challenge.gov/)
-	Open Science: [Science.gov](https://www.science.gov/)
-	Open Source Code: [Code.gov](https://code.gov/) and [HHS GitHub repo](https://github.com/HHS)

HHS will improve its ability to transform raw data into actionable insights that guide decisions across all levels of the Department. To support this, the HHS Chief Data 
Officer (CDO) collaborated with data leaders to define shared values for navigating future challenges and change. While the HHS workforce, interagency partners, and 
external collaborators may differ on data priorities or interpretations, we can all unite around values that drive progress and collaboration with a “sharing by default” 
culture and “open by default” data ethos.

Core values underpin the HHS Open Data community, underlying every aspect of this plan.\
__1.	TRANSPARENCY:__ Radical openness by default.\
__2.	PURPOSE:__ Data that serves the public good.\
__3.	RELENTLESS OPTIMIZATION:__ Adapt, refine, and improve using agile methods, two-way feedback, a growth mindset, and accountability.\
__4.	EXCELLENCE:__ Real-world evidence drives impact.\
__5.	RESPECT:__ People and patients as equal partners.\
__6.	INTEGRITY:__ Find the truth. Tell the truth.

Thank you to everyone who has contributed to the HHS Open Data ecosystem—a community of solvers, collaboratively co-creating a more transparent, accountable, and responsive HHS. Today, we have incredible opportunity to responsibly share data, eliminate silos, modernize government, and drive progress through partnerships and emerging technologies like Artificial Intelligence (AI). All are welcome—join us! People first, data always!

<p align="right">&mdash; <a href="https://www.healthit.gov/leadership/kristen-honey">Kristen Honey, PhD, PMP</a>, HHS Chief Data Officer, <a href="https://cdo.hhs.gov/s/">HHS Office of the Chief Data Officer</a></p>
