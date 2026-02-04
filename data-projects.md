---
layout: default
title: Data Projects
---

[Home](index) \| [Assessment Information](assessment-information) \| [Refresher](refresher) \| [Blackboard Page](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/outline) \| [Blackboard Forum](https://www.ole.bris.ac.uk/ultra/courses/_264181_1/engagement) \| [Unit Catalogue](https://upc.bristol.ac.uk/unit-programme-catalogue/UnitDetails.jsa?ayrCode=25%2F26&unitCode=COMS30050)
<br/>
[Data Projects](data-projects) | Labs: [1](labs/1-data-ingress) | [2](labs/2-data-privacy-ethics) | [3](labs/3-graph-database) | 4 | 5

---
# Data Projects

## Project 1. Analysing Social Media Impact on Public Discourse
This project aims to explore the role of social media in shaping public discourse and influencing societal trends. With billions of users worldwide, platforms such as Bluesky, Twitter, Facebook, and Reddit facilitate real-time communication and information sharing, impacting how individuals engage with topics such as politics, health, and social movements. Collecting and analysing data from these platforms, enables investigating trends in discussions, user engagement, and the influence of significant events on public opinion. The project will involve data collection from social media platforms using APIs or web scraping techniques, utilise natural language processing (NLP) and statistical methods to analyse trends, sentiment, and user interactions, and create visualisation to uncover insights into the complexities of social media's impact on public opinion, communication strategies, and societal change.

- Bluesky Social dataset: <https://zenodo.org/records/14669616> (updated)
- Dataset on Covid-19 tweets: <https://globalaffects.org/covid-news/>
- Dataset on US election tweets: <https://www.kaggle.com/manchunhui/us-election-2020-tweets> 

## Project 2. Analysing UNICEF Data (e.g., Gender Equality, Child Nutrition)
UNICEF (<https://data.unicef.org/>) offers a comprehensive collection of datasets that are vital for understanding various aspects of children's and women's rights and well-being. These datasets cover a range of critical topics, including education, gender equality, HIV/AIDS, mortality, child nutrition, poverty, and child protection.

For instance, those related to nutrition and gender can be found by exploring these sites:

- Child nutrition: <https://data.unicef.org/topic/nutrition/child-nutrition/>
- Gender: <https://data.unicef.org/topic/gender/overview/>  
- Datasets: <https://data.unicef.org/resources/resource-type/datasets/> 

By exploring these datasets, you can create visualisations and predictive models to tell compelling stories about these important issues, potentially linking them with other relevant UNICEF datasets to provide a more comprehensive understanding of children's and women's lives.

## Project 3. Early Prediction of Sepsis from Clinical Data 
Sepsis is a life-threatening condition that occurs when the body's response to infection causes tissue damage, organ failure, or death. In the U.S., nearly 1.7 million people develop sepsis and 270,000 people die from sepsis each year; over one third of people who die in U.S. hospitals have sepsis (CDC). Internationally, an estimated 30 million people develop sepsis and 6 million people die from sepsis each year; an estimated 4.2 million newborns and children are affected (WHO). Early detection and antibiotic treatment of sepsis are critical for improving sepsis outcomes, where each hour of delayed treatment has been associated with roughly an 4-8% increase in mortality (Kumar et al., 2006; Seymour et al., 2017). To help address this problem, clinicians have proposed new definitions for sepsis (Singer et al., 2016), but the fundamental need to detect and treat sepsis early still remains, and basic questions about the limits of early detection remain unanswered. 

This formed the 2019 Physionet Computing in Cardiology Challenge. The goal of this project is the early detection of sepsis using physiological data, which can be found, together with more background information, here https://physionet.org/content/challenge-2019/1.0.0/  

- Dataset: <https://archive.physionet.org/users/shared/challenge-2019/>


## Project 4. Activity Recognition with Multimodal Sensor Data 
The task of this project is to predict the activities of residents within a smart home based only on observed sensor data. Sensor data are obtained from the following three sensing modalities: a wrist-worn accelerometer, video + depth (RGB-D), and passive environmental presence sensors.

Data, metadata, and other information can all be found at this server: <https://data.bris.ac.uk/data/dataset/8gccwpx47rav19vk8x4xapcog>  


## Project 5. European Productivity  
The EU Open Data portal maintains many datasets related to social and economic trends across the EU. 

For example, the data on labour productivity per hour worked, or economic sentiment: 
- <https://ec.europa.eu/eurostat/web/products-datasets/-/tesem160> 
- <https://ec.europa.eu/eurostat/web/products-datasets/-/teibs010>

Your task is to analyse trends in this data and relationships between outcomes, potentially making use of other EU Open Data portal datasets that may help you enrich your analysis (such as that for education, or COVID-related data).


## Project 6. European Social Survey (ESS) Data
The European Social Survey (ESS) (<https://www.europeansocialsurvey.org/>) is cross-national survey that measures attitudes, beliefs, and behaviour patterns of people across Europe. It is funded by its participating countries in Europe and was awarded European Research Infrastructure Consortium (ERIC) status in 2013, by the European Commission. ESS' data portal provides freely accessible data on topics such as democracy, media consumption, immigration, social trust, well-being, health, and political engagement, collective from representative samples in participating counties. As an example, a project could be on analysis of political attitudes, social trust over time, clustering countries based on well-being indicators, or predictive modelling of voting behaviour, applying statistical methods, machine learning, and data visualisation techniques.

Data is available free of charge for non-commercial use, and each country has a minimum sample size of 1500 participants.  Their data portal has some nice interactive elements that can be used (https://www.europeansocialsurvey.org/data-portal), which may be used to find a specific topic of interest quickly.

## Project 7. NFL Big Data Bowl
NFL is the most popular sport in the US. This dataset is from NFL Big Data Bowl 2025. The data provides location information for each special teams player, wherever they are on the field, and includes their speed, acceleration, and direction.  In this project, you will apply your data science learning to better understand these plays.

More details about the dataset is here:
<https://www.kaggle.com/competitions/nfl-big-data-bowl-2025/overview>

You could download the dataset using Kaggle's API.

## Project 8. NYC Taxi and Limousine Commission (TLC) Trip Record Data
The NYC Taxi and Limousine Commission (TLC) Trip Record Data is a public dataset that provides detailed information about taxi and for-hire vehicle trips in New York City, including pickup and drop-off locations, timestamps, trip distances, and fare amounts. Data science projects using this dataset could include trip pattern analysis to create heatmaps of popular locations, developing machine learning models to predict taxi fares, and analysing trip durations to identify traffic congestion patterns. Additionally, researchers could assess the environmental impact of taxi operations, explore customer behaviour through payment methods and trip durations, and investigate how major events affect taxi demand in specific areas. These projects can yield valuable insights into urban transportation dynamics and support informed decision-making for city planners and taxi operators.

- Dataset: [TLC Trip Record Data - TLC](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- Example project: <https://toddwschneider.com/posts/analyzing-1-1-billion-nyc-taxi-and-uber-trips-with-a-vengeance/>


## Project 9. Explaining Privacy Decisions  
Social networks enable users to share text and image content with others via online interactions and thus help users maintain their social relationships. Whereas users conveniently share content online they often misjudge harms associated with sharing the content.   
This project involves (1) analysing an image dataset containing 22k images annotated with 68 privacy attributes, and (2) developing a privacy explanation framework. The explanations framework will include developing an image analysis module to identify personal information attributes such as skin colour, gender, or presence or absence of credit card number in an image and generating recommendations based on the identified attributes whether an image should or should not be shared online.   

- Dataset: <https://github.com/tribhuvanesh/vpa>   
 
## Project 10. Smart Home Product Usecase Dataset  
In this project, you will work with a smarthome dataset that includes 1823 smart home usecase scenarios produced by 323 Amazon MTurk workers working alone or in teams of four. A subset of these usecase scenarios are rated for creativity --- novel and usefulness. The dataset includes the workers' demographics and personality traits measured using the DISC personality model survey instrument.   

- Dataset: <https://zenodo.org/record/4308066#.YB_48uqnxKs>   

Whereas it is easy to collect scenarios via crowdsourcing, collecting scenarios that are creative is non-trivial. Manually rating the scenarios for creativity is also challenging. How could we predict novelty and usefulness of a scenario? Crowd workers work on their tasks independently and thus many scenarios they produce are identical. How could we group similar scenarios and summarize the scenarios produced? Could we cluster scenario or leverage topic-models? How could we stimulate crowd workers to produce scenarios that are creative and different from the ones proposed earlier?  
 
## Project 11. Open Source Intelligence (OSINT) Projects
In this task you will gather and analyse data from Open Source Intelligence (OSINT) practitioners who build and analyse open source data sets in order to address issues around humanitarian disasters and human security (e.g., weapons tracking, war, terrorism and oppression). Possible project ideas might include building an advanced visualization portal for navigating and making sense of a complex data set (e.g., a data portal for representing how national spending on weapons has changed over time or for tracking arms trades between countries, or for visualizing destroyed villages in Myanmar), linking open source datasets to contextual information in order to improve sense making (e.g., connecting data on weapons trafficking to data on military conflict or relating national military spending to spending on aid or other sectors), or developing machine learning models to identify and verify trends in the data or automate data extraction (e.g., training neural networks to detect burned villages from satellite images; NLP models trained to automatically extract military expenditure information from open data sources).

### Example OSINT practitioner #1: SIPRI (<https://www.sipri.org/databases>)
_Tracking international arms deals and military spending_

- Sample datasets: <https://www.sipri.org/databases/milex>

### Example OSINT practitioner #2: Centre for Information Resilience (<https://www.info-res.org>)
**_Detecting of destroyed areas in Myanmar, Rakhine State_ (The Ocelli Project <https://ocelli.c4ads.org/>)**
Rakhine manually observed and documented apparent village destruction in Rakhine State between 2016 and 2020 using publicly available satellite imagery. This analysis demonstrates the scale, pace, and geographic range of the systematic displacement and genocide of the Rohingya ethnic minority. It represents the most comprehensive available mapping of forced displacement in Rakhine State.

- Sample dataset: <https://docs.google.com/spreadsheets/d/1lhrInkY5qS6lahY9caSsD8osraUsAYFUd9tI_6PfCl8/edit?usp=sharing>

**_Mapping of ongoing burning of villages in Myanmar (Sep 2021 - Present)_**
Myanmar Witness uses satellite imagery, verified footage and NASA FIRMS data to document and investigate where buildings and villages have been destroyed by fire in possible human rights incidents.

- The dataset is the data behind this map showing where and when each of those events occurred and linking to the relevant media where verified and safe to do so: <https://www.myanmarwitness.org/fire-map>

**_Monitoring of the conflict in Ukraine_**
The project Eyes on Russia of the Centre of Information Resilience collects, verifies, analyses, archives and shares information about conflict events by scanning a range of social media platforms in Ukrainian, Russian and English. Data is collected on civilian casualties, damage to health, educational, transport, utilities and other forms of infrastructure, and the activities of the Russian military and local allies.

- The dataset: Archived videos, photos, satellite imagery or other media related to events resulting from Russia's invasion of Ukraine that have been geolocated and analysed by the Open Source community and reviewed by CIR. Entries that do not risk any individuals or Ukrainian positions are published on the Eyes on Russia map: <https://eyesonrussia.org/>

## Project 12. Exploring Timeseries Atmospheric Data from the Met Office
This dataset contains hourly atmospheric data for 12 locations for 38 years, as produced by the ERA5 model. The group working on this project can initially examine the data and find ways to visualise it (from simple timeseries plots to something like this), as well as examining the relationships between different variables (temperature, precipitation, and wind). Further, they could then use statistical or ML models to attempt any of the following:

1. For a given time, predict one of the atmospheric variables, when given all the other variables (such as with a neural network or random forest)
2. Given past values of a variable, predict future values (such as with a recurring neural network)
3. Given current conditions in all but one location, attempt to approximate conditions in the remaining location

- Dataset: <https://zenodo.org/records/10624903>
(Problem Owner: Theo Xirouchaki, Met Office)

## Project 13. Exploring Bristol Open Data

Bristol City Council provides an open data portal (<https://opendata.bristol.gov.uk/>) with datasets describing transport, air quality, housing, crime, population, and environmental conditions in the city.

In this project, students will select one or more Bristol datasets and analyse urban patterns over time or across neighbourhoods. Possible topics include traffic and air pollution, spatial patterns in crime, access to services, or relationships between housing and deprivation.

- Data portal: <https://opendata.bristol.gov.uk/>

## Project 14. Analysing Air Quality Using OpenAQ Data

OpenAQ provides open, real-time and historical air quality measurements from monitoring stations across the world. In this project, students will analyse pollution levels (e.g. PM2.5, NO2, O3) over time and across locations to identify long-term trends, seasonal patterns, and extreme pollution events. 
A potential project using the OpenAQ data will involve cleaning time-series data and producing visualisations and predictive models to understand how air quality varies spatially and temporally.

- Data portal: <https://openaq.org/>

## Project 15. Analysing Cost of Living and Inflation Using ONS Data

The UK Office for National Statistics (ONS) publishes regularly updated datasets on prices, household expenditure, and inflation across regions and product categories. As a potential project using the ONS data, students will explore how the cost of living has changed over time and how inflation differs between regions or types of goods. The analysis will combine data cleaning, exploratory analysis, and visualisation, with use of statistical or machine learning methods to model trends and identify groups most affected by rising prices.

- Data portal: <https://www.ons.gov.uk/economy/inflationandpriceindices>