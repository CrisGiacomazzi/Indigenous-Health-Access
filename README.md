# Indigenous-Health-Access
_In progress_

<img width="960" alt="Screen Shot 2025-01-26 at 1 34 13 PM" src="https://github.com/user-attachments/assets/a0018c57-7b9d-4b79-8421-6beb08799552" />

Figure 1. Planning the project steps


# Business Problem 
_Improving Indigenous Access to Healthcare: A Business Challenge_
Indigenous communities in Canada face significant barriers to accessing primary healthcare, creating systemic challenges that not only impact individual well-being but also drive up government healthcare costs. A systematic review by Barbo et al. (2024) highlighted that Indigenous populations prioritize healthcare that is safe, accessible, and respectful. Despite these priorities, discrimination and racism within the healthcare system remain pervasive, resulting in unmet healthcare needs, poorer health outcomes, and increased reliance on costly emergency and acute care services. The “Health Care Access and Experiences among Indigenous People” report (2024), which surveyed 6,206 individuals, further revealed systemic gaps in accessibility, cultural safety, and equitable treatment. Addressing these issues is crucial not only to improve healthcare outcomes for Indigenous populations but also to reduce the significant financial burden on government resources caused by inefficiencies and systemic barriers.

# Indigenous reason for not receive health care service (%)

<img width="664" alt="Screen Shot 2025-01-26 at 3 36 12 PM" src="https://github.com/user-attachments/assets/9ed137ff-2785-4518-a729-3bbf77316e60" />

Figure 2. Percentage of Indigenous people who consider the cultural and communication problem a reason for not receiving health services. Image made by the author using Tableau (2024).

# Hypothesis

| Area target                | H0            | H1            |
| -------------              | ------------- | -------------
| Racism and discrimination  | Increasing health literacy scores for caregivers and community authorities does not decrease the racism and discrimination complaints in the healthcare system  | Increasing health literacy scores for caregivers and community authorities decreases racism and discrimination complaints in the healthcare system |
| Lack of availableculturally appropriate healthcare services  |Increasing health literacy scores for caregivers and community authorities does not decrease the lack of available culturally appropriate healthcare services|Increasing health literacy scores for caregivers and community authorities decreases the lack of available culturally appropriate healthcare services|
| Lack of use own traditional healing methods ceremonies or medicines |Increasing health literacy scores for caregivers and community authorities does not increase the use own traditional healing methods ceremonies or medicines| Increasing health literacy scores for caregivers and community authorities increases the use own traditional healing methods ceremonies or medicines|
| Government costs |Increasing health literacy scores for caregivers and community authorities does not decrease government costs|Increasing health literacy scores for caregivers and community authorities decreases government costs| 

# Project Plan
To ensure the feasibility of the project, a pilot program will be developed.
* Program Duration: The project is designed as a one-year initiative to ensure a thorough and measurable impact within the target communities.
* Sample: A carefully selected sample size will be utilized to ensure the validity and reliability of the findings and outcomes.
* Priority Area: The primary focus of the project will be on enhancing health literacy within Indigenous communities, addressing a critical barrier to healthcare access.
* Hypothesis Testing: The project will involve testing specific hypotheses to evaluate the effectiveness of proposed interventions and strategies.


# Definitions
_Indigenous Health Centers: Financial and Systemic Challenges_
* In Canada, Aboriginal Health Access Centres (AHACs) are community-led organizations that provide primary healthcare services to First Nations, Métis, and Inuit populations. These centers aim **to reduce the physical distance** between Indigenous communities and the healthcare system, helping to address disparities in access to care. Notable examples, such as the First Nations Health Authority in British Columbia, highlight this transition towards Indigenous-led healthcare delivery (Toronto Central Healthline, n.d.)
* However, the construction and operation of these health centers come with **significant financial costs**. High construction and maintenance expenses are often compounded by systemic challenges, including **persistent cultural and communication barriers** that hinder effective service delivery. The government has made efforts to fund healthcare infrastructure in remote areas, but these costs remain a burden on public finances. As highlighted in several reports, such as those from The Globe and Mail and the Canadian government, addressing these financial and systemic challenges is critical for improving healthcare access and equity for Indigenous populations (The Globe and Mail, 2024; Indigenous Services Canada, 2024).
* Given these ongoing issues, it is essential **to implement prompt and strategic changes in healthcare practices**, organizational structures, and policy development to ensure the long-term sustainability of Indigenous health centers and improve healthcare outcomes for these communities.

<img width="600" alt="Screen Shot 2025-01-26 at 3 38 14 PM" src="https://github.com/user-attachments/assets/17f6ee19-274e-4785-8e63-ac279972bdb4" />

Figure 3. Number of Indigenous Health Centers in Canada by NCCIH (2024)


_The Truth and Reconciliation Commission of Canada (TRC)_
* National organization created to address the legacy of residential schools and the broader history of systemic abuse, discrimination, and marginalization experienced by Indigenous peoples in Canada (Indigenous Services Canada, n. d. ).
* In 2022, a call for action to decrease health inequality was refreshed.
* This call for action emphasizes the need for **improved healthcare access and outcomes for Indigenous populations**.

_The Canadian Centre for Caregiving Excellence (CCCE)_
* Indigenous caregivers face unique challenges due to **historical and systemic issues**, which may be addressed through support services and research promoted by the CCCE.
* Integrating **culturally relevant caregiving strategies aligns with the TRC’s recommendations** for improving healthcare for Indigenous peoples.
* The CCCE’s efforts to enhance caregiving practices can involve **developing culturally competent models** that respect Indigenous healing practices and traditional caregiving roles.

_Indigenous Caregivers_
* Indigenous caregivers encounter **unique challenges** resulting from historical and systemic issues **that impact their ability to access healthcare and caregiving support**.
* Efforts should **focus on integrating culturally relevant caregiving models that respect Indigenous healing practices** and align with the Truth and Reconciliation Commission (TRC) recommendations for improving healthcare for Indigenous peoples (Canadian Caregiving Network, n.d.-b).

_Emergency room visits in Canada_
* The cost can vary significantly. Kingston Health Sciences Centre (2024) suggest an average cost of **$386** per visit for **general population**, others sources indicate that it could be much higher, potentially reaching over $1,000 depending on the services required.
* Studies show that Indigenous people, particularly those in urban areas, have higher rates of ER visits compared to the general population. This increased utilization naturally leads to higher overall costs for the healthcare system.
* Marchand et al (2024) show that Indigenous people, particularly those in urban areas, **have higher rates of ER visits compared to the general population**. This increased utilization naturally leads to higher overall costs for the healthcare system.
* In **remote Indigenous communities** comes with significant **logistical challenges and costs**, including transportation of patients and healthcare professionals, and maintaining healthcare facilities in remote areas (Reading & Wien, 2009).

_Health Literacy_
* In accordance with Lambert et al. (2014), **health professionals often demonstrate a limited understanding of health literacy and its implications for Indigenous patients**.
* This lack of comprehension, coupled with perceived barriers to enhancing health literacy, **significantly impedes the ability of healthcare providers to effectively support the development of health literacy skills among Indigenous patients**. Consequently, this gap in understanding may restrict patients' ability to fully grasp the nature of their illnesses and the necessary steps to manage their health conditions, further exacerbating the challenges in healthcare access and outcomes for Indigenous communities.
* Addressing this issue is crucial to improving health literacy and ultimately **enhancing the quality of care provided to Indigenous populations**.
* According to Speros (2005), **health literacy is a more significant predictor of health status** than socioeconomic status, age, or ethnic background.
* Indigenous populations generally exhibit **lower literacy levels**, with approximately 60% of adults and 88% of older adults lacking adequate health literacy (Chiarelli and Edwards, 2006).

# Dataset creation - Methodology
* Due to the lack of publicly available real-world data on Indigenous healthcare access, three datasets (CSV, XLS, and JSON) were created using Python and AI-powered tools, including DeepSeek. The data was generated based on extensive research, incorporating estimates from government reports, news articles, and scientific publications.
* Key variables, such as population proportions, healthcare costs, and Health Literacy Questionnaire (HLQ) evaluations, were informed by averages from publicly available health statistics.
* While synthetic data cannot fully capture real-world complexities, this portfolio project aims to simulate real-world challenges, analyze potential solutions, and model various healthcare scenarios to support Indigenous caregivers effectively.

## Dataset 1

Created a dataset in CSV format containing 260 observations and 4 columns, using the following rules:

<img width="675" alt="Screen Shot 2025-01-29 at 9 38 10 AM" src="https://github.com/user-attachments/assets/ed8130b7-de2b-4296-bbef-1bbf5e1e2061" />


## Dataset 2

Created a dataset in XLS format containing 260 observations and 7 columns, using the following rules:

<img width="516" alt="Screen Shot 2025-01-29 at 10 01 37 AM" src="https://github.com/user-attachments/assets/8a19a131-edd1-4b6d-bc8c-f70937b585fd" />

Footnote: the data here was based on Statistics Canada (2024).

## Dataset 3




# References

Barbo, G., & Alam, S. (2024). Evidence synthesis – Indigenous people’s experiences of primary health care in Canada: A qualitative systematic review. *HPCDP Journal.* https://doi.org/10.24095/hpcdp.44.4.01

Canadian Caregiving Coalition. (n.d.-a). _Home. Canadian Caregiving Coalition_. Retrieved January 26, 2025, from https://canadiancaregiving.org 

Canadian Caregiving Network. (n.d.-b). Canadian caregiving network. Canadian Caregiving Network. Retrieved January 26, 2025, from https://canadiancaregiving.org/

Chiarelli, L., & Edwards, P. (2006). Building healthy public policy. _Canadian journal of public health = Revue canadienne de sante publique_, 97 Suppl 2, S37–S42.

First Nations Health Authority. (n.d.). _Our history, our health. First Nations Health Authority_. Retrieved from https://www.fnha.ca/wellness/wellness-for-first-nations/our-history-our-health?utm_source=chatgpt.com

Indigenous Services Canada. (2024, December 19). *Health services and programs for First Nations and Inuit communities.* Government of Canada. Retrieved from https://www.sac-isc.gc.ca/eng/1526995988708/1526996020578

Indigenous Services Canada. (n.d.)._Indigenous peoples and communities: Health and wellness_. Government of Canada. Retrieved January 26, 2025, from https://www.rcaanc-cirnac.gc.ca/eng/1450124405592/1529106060525

Indigenous Services Canada. (June 13, 2024). _Indigenous health care in Canada_. Government of Canada. Retrieved January 29, 2025, from https://www.rcaanc-cirnac.gc.ca/eng/1100100013785/1529102490303

Lambert, M., Luke, J., Downey, B., Crengle, S., Kelaher, M., Reid, S., & Smylie, J. (2014). Health literacy: health professionals' understandings and their perceptions of barriers that Indigenous patients encounter. _BMC health services research_, 14, 614. https://doi.org/10.1186/s12913-014-0614-1

Marchand, T., Squires, K., Daodu, O., & Brindle, M. E. (2024). Improving Indigenous health equity within the emergency department: a global review of interventions. CJEM, 26(7), 488–498. https://doi.org/10.1007/s43678-024-00687-3

Kingston Health Sciences Centre. (April 1, 2024). _Without Health Insurance Fees_. Retrieved from https://www.qch.on.ca/WithoutHealthInsuranceFees

Reading C.L., Wien F. Health Inequalities and Social Determinants of Aboriginal Peoples’ Health. National Collaborating Centre for Aboriginal Health; Prince George, BC, Canada: 2009

Rheault, H., Coyer, F., Jones, L., & Bonner, A. (2019). Health literacy in Indigenous people with chronic disease living in remote Australia. BMC health services research, 19(1), 523. https://doi.org/10.1186/s12913-019-4335-3 

Statistics Canada. (2024, November 4). _Health care access and experiences among Indigenous people, 2024_. Statistics Canada. Retrieved from https://www150.statcan.gc.ca/n1/daily-quotidien/241104/dq241104a-eng.htm

The Globe and Mail. (2024, November 4). *Ottawa funding First Nations hospital in northern Ontario*. The Globe and Mail. Retrieved from https://www.theglobeandmail.com/politics/article-ottawa-funding-first-nations-hospital-northern-ontario/

Toronto Central Healthline. (n.d.). _Community-led health programs and services for First Nations, Inuit, and Métis_. Retrieved January 26, 2025, from https://www.torontocentralhealthline.ca/listServices.aspx?id=10071#:~:text=health%20care%20organizations.-,Community%2Dled%20health%20programs%20and%20services%20for%20First%20Nations%2C%20Inuit,led%2C%20primary%20health%20care%20organizations

Webkamigad, S., Warry, W., Blind, M., & Jacklin, K. (2020). An Approach to Improve Dementia Health Literacy in Indigenous Communities._Journal of cross-cultural gerontology_, 35(1), 69–83. https://doi.org/10.1007/s10823-019-09388-2 
 


