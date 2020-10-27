# Team-Jet-Lag
## Domain of Interest
**Why are you interested in this field/domain?**

Coronavirus is a hot topic this year, people around the world are hugely affected by it. As international students, we are facing many difficulties due to coronavirus. It affected our lives in so many ways. And we believed that others have been through the same thing like us. Thus, we decided to engage in this field and create a website that could help people in this complex situation. We hope that our design could help people gain insights and reduce their stress, informing the public of the effect of COVID-19 on education, transportation, work, and need of personal protective equipment. We also want to go further by adding information about where you could get a covid test and which hospital you could go to for help.



**What other examples of data driven projects have you found related to this domain (share at least 3)?**

>An example for other data driven project related to this domain is the study of Covid's impact on education in terms of remote learning. This project was held by the United Nations International Children's Emergency Fund (UNICEF). It held out questionnaires to school officials and collected their responses related to school closures due to the pandemic. It explored the responses of different education level schools on remote studying policy. It also looked into the unequal gap for the possibility of conducting remote study due to technical issues and income level.

>One of the examples of data driven projects related to this domain is the study of the effect of COVID-19 on residential mobility. This project is created and published by the Bureau of Transportation Statistics (BTS), and it elaborates on the effect of COVID-19 brought to the national mobility and transportation system. This dataset includes the population staying at home, the population not staying at home, number of trips for those who travel, and the level of the region.

>I found the _Tracking PPE Distribution_ project from the _Washington State Coronavirus Response_ and _Cases and Deaths by Week of Illness Onset, County, and Age_ from the _Washington State Department of Health_ as examples of data-driven projects related to this domain.

>An example of a data driven project related to this domain is the study of the effect of covid on people’s work. The Bureau of Labor Statistics added questions to the Current Population Survey (CPS) to help gauge the effects of the coronavirus (COVID-19) pandemic on the labor market. This dataset included whether people tele worked or worked from home due to the pandemic; do they lose their job or their business because of the covid; are they getting paid and whether the pandemic prevented job-seeking activities.

**What data-driven questions do you hope to answer about this domain (share at least 3)?**

> We hope to find answers to the correlation between the opportunity of receiving medical treatment from hospitals and the identities of patients, including gender, age, and race and ethnicity.

>We hope to find out how COVID-19 affects resident's mobility at the state and national level.

>We hope to predict how much Personal Protective Equipments (PPEs) will be needed in the near future to prevent the spread of COVID-19.

>We hope to find out how the covid-19 influence people’s life including their work and standard of living. 

## Finding Data
**Where did you download the data (e.g., a web URL)?
How was the data collected or generated? Make sure to explain who collected the data (not necessarily the same people that host the data), and who or what the data is about?
How many observations (rows) are in your data?
How many features (columns) are in the data?
What questions (from above) can be answered using the data in this dataset?**

> This dataset of Covid surveillance is downloaded from the [_U.S. Government's open data_](https://catalog.data.gov/dataset/covid-19-case-surveillance-public-use-data). The original data was collected by the _Centers for Disease Control and Prevention (CDC)_, a national public health institute in the U.S. This dataset is monthly updated and consists _patient-level data_ including important dates and personal information about CDC reported Covid cases. There are _4,481,062 observations_ and _11 features_ in the dataset. This dataset records the dates of the initial report to CDC, date of first specimen collection, date of symptom onsite, status of the case (whether or not laboratory confirmed), gender, age group race and ethnicity , hospitalization status, ICU admission status, death status, and presence of underlying comorbidity or disease of the patient. This dataset answers all questions listed above.

>This datasets shows the national and state-level mobility change during the period of COVID-19, providing information such as the number of population staying at home, the number of population not staying at home, and their frequencies of travel. It’s published by the [_Bureau of Transportation Statistics (BTS)_](https://catalog.data.gov/dataset/trips-by-distance),  which utilizes the mobile device data panel from merged multiple data sources in each geographic area. This dataset includes _2,072,906 observations_ and _19 columns_. Based on the information from this dataset, we could analyze and track the population movements during this period as well as their degree of acceptance of government’s stay-at-home policy. Moreover, we could also gain insights of how the population movement influences the spread of COVID-19.

>This is a dataset of covid-19 cases and deaths by state over time in United States. It is published by [_Centers for Disease Control and Prevention_](https://catalog.data.gov/dataset/united-states-covid-19-cases-and-deaths-by-state-over-time), CDC reports aggregate counts of COVID-19 cases and death numbers daily online. Data on the COVID-19 website and CDC’s COVID Data Tracker are based on these most recent numbers reported by states, territories, and other jurisdictions. There are currently _1,6621 observations_ and _15 features_ in the dataset. From this dataset, you could track the most recent numbers of the Covid-19 cases and death numbers which is also categorized by state.

>I downloaded the data from [_Washington State Coronavirus Response Tracking PPE Distribution_](https://coronavirus.wa.gov/what-you-need-know/personal-protective-equipment/tracking-ppe-distribution) and [_Washington State Department of Health COVID-19 Data Dashboard_](https://www.doh.wa.gov/Emergencies/COVID19/DataDashboard). _Tracking PPE Distribution_ was collected and generated by the _Washington State Department of Enterprise Services_. _Cases and Deaths by Week of Illness Onset, County, and Age_ was collected and generated by the _Washington State Department of Health_. _Tracking PPE Distribution_ is about [_government purchases and distribution of gloves, gowns, masks and other personal protective equipment (PPE) in Washington during the COVID-19 pandemic. Information includes purchasing and distribution data, lists of vendors, and distribution by county, state agency or tribal nation._](https://data.wa.gov/Procurements-and-Contracts/Washington-State-Distribution-of-Personal-Protecti/u6t9-petu) _Cases and Deaths by Week of Illness Onset, County, and Age_ is about number of new COVID-19 cases and deaths by week of illness onset, county and age. There are 260 observations (rows) in _Tracking PPE Distribution_ and 1162 observations (rows) in _Cases and Deaths by Week of Illness Onset, County, and Age_. There are 3 features (columns) in _Tracking PPE Distribution_ and 10 features (columns) in _Cases and Deaths by Week of Illness Onset, County, and Age_. The numbers of Personal Protective Equipments needed in the near future to help the Washington state residents and manufacturers can be forecasted using the data in this dataset. To predict PPE needs, previous PPE distributions and the previous number of COVID-19 cases can be leveraged.
