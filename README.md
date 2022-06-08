# Instructions

## Submission

On clicking the exam link a new repository has been created for you in the exam classroom. You should now clone this repository into a new RStudio project then **commit and push** to GitHub as usual. 

GitHub takes a snapshot of your **local git** repository at the deadline so **commit and push often**, as you should do in all spatial data science projects. The deadline is based on your last commit, but we expect the repository to be pushed to GitHub very soon after. 

## Before you begin: 

* Go to the top of the `exam_response.Rmd` RMarkdown document and edit the name and student number fields (at the top of the `.Rmd`).

* Complete the originality declaration

## Task

You have six hours to complete this open book exam. You must select and undertake **only one** of the research questions below. Links to the data for each question have been provided and you are free to source additional data for extension analysis, but everything you need is provided.

* You must write your response in the `exam_response.Rmd`, under the originality declaration.

* You may use any resource to assist you but the work must be your own and you are required to sign a originality statement within the exam. 

* Questions about the exam must be asked on the open Slack GIS channel. 

* You can use RStudio visual markdown editor if you wish.

* If you copy a section of code from an online source please provide a relevant link or acknowledgment.

Marks are awarded as per the marking scheme. It's important to note there is no 'right' answer, even if your findings are inconclusive or not as expected, you are awarded marks for how you approach the problem.  

## Within your work you must:

* Provide an initial project scope in bullet point form. Your project scope should include:

    * If you intend to propose a variation of the original question (e.g. selecting a specific year of data to analyse), this must be based on appropriate reasoning and clearly stated.
  * A brief evaluation of your main research dataset(s) as well as an assessment of any data processing tasks that will be required or additional data that might be required to complete your analysis.
  * A brief explanation of the data wangling and analysis you intend to undertake, prior to starting the analysis. This may include research questions or hypotheses you identify as relevant. 
  * You may also wish to identify any constraints (around the data you have been instructed to analyse) or obvious omissions from the set task that could limit what will be produced in this short project. These could relate to spatial or temporal limitations in the dataset, what you decide is reasonable to analyse or anything else that is relevant. 

* Produce a well commented and fully explained RMarkdown document that attempts to answer the research question.

* Create at least one graphical output and at least one mapped output.

* Critically reflect on the results you have produced. 

## Tips:

* In the time you have, prioritise good solid analysis over innovative analysis that uses advanced techniques.

* Structure your RMarkdown document with titles and subtitles. 

* Comment and explain your working throughout.

* State assumptions and describe limitations.

* In most questions some administrative boundary data has been provided, use this to assist guiding recommendations and outputs.

* Provide critical commentary about the data you are using and the analysis you are undertaking throughout.

* Plan your time. We suggest 1 hour for data exploration, 2-3 hours for analysis, 1 hour for visualisations, 1 hour for interpretation and reflection. 

# Exam Questions

## New York Stop, Question and Frisk

The New York Police Department are conducting a review of their stop, question and frisk (SQF) policy. You have been enlisted as a consultant and tasked to conduct an analysis of their data from 2020.

You should use appropriate data processing and analysis methods to produce an overview report which summarises the patterns revealed in the data in this year. It is expected that at least some of the methods you use will relate to the spatial dimensions of the data.

Your report should include a brief introduction including relevant contextual information at the beginning and a critical review of your findings at the end. You must include at least one map. 

### Data

* 2020 stop, question and frisk data from the New York Police Department. X and Y values are given in the New York-Long Island State Plane Coordinate System (EPSG 2908) - https://www1.nyc.gov/site/nypd/stats/reports-analysis/stopfrisk.page 

* New York Police districts - https://data.cityofnewyork.us/Public-Safety/Police-Precincts/78dh-3ptz 

## Obesity and Diet in London

The Greater London Authority wants to better understand the relationship between obesity and diet in the city. You have been enlisted as a consultant and tasked to conduct an analysis of obesity and grocery purchasing habits.

You should use appropriate data processing and analysis methods to produce an overview report which summarises the patterns revealed in the data. It is expected that at least some of the methods you use will relate to the spatial dimensions of the data.

Your report should include a brief introduction including relevant contextual information at the beginning and a critical review of your findings at the end. You must include at least one map.

MSOA is the recommended spatial scale, but it is possible to conduct analysis at other spatial scales.  

### Data

* Tesco supermarket grocery data (limited to certain months from 2015) - https://figshare.com/articles/dataset/Area-level_grocery_purchases/7796666?backTo=/collections/Tesco_Grocery_1_0/4769354

* London Statistical GIS boundaries - https://data.london.gov.uk/dataset/statistical-gis-boundary-files-london

* Complete MSOA level obesity data can be found in the MSOA atlas - https://data.london.gov.uk/dataset/msoa-atlas 

* Obesity data at various spatial aggregations, 2013-14 - https://figshare.com/articles/dataset/Validation_data_obesity_diabetes_/7796672?backTo=/collections/Tesco_Grocery_1_0/4769354


## Melbourne Urban Forest Strategy 

The City of Melbourne has a comprehensive urban forest strategy that monitors the health, diversity and status of trees throughout the city whilst also identifying locations for future planting. Trees are an important part of urban temperature mitigation strategies, something highly relevant to the proposed expansion of the city and pressure it may put on tree removal.

You have been enlisted as a consultant and tasked to conduct an analysis which investigates the relationship between tree canopy coverage and temperature in Melbourne City at an appropriate level of spatial granularity.

You should use appropriate data processing and analysis methods to produce an overview report which summarises the patterns revealed in the data. It is expected that at least some of the methods you use will relate to the spatial dimensions of the data.

Your report should include a brief introduction including relevant contextual information at the beginning and a critical review of your findings at the end. You must include at least one map.

In the Australian census SA1s are the smallest spatial unit of released census data, which are aggregated into SA2s that depict interacting communities and SA3s that represent regions. 

### Data

* December 2019 Tree canopy spatial data for Melbourne City - https://data.melbourne.vic.gov.au/Environment/Tree-canopies-2019/tq3k-d7n7

* February 2020 Landsat 8 image (Landsat Collection 2 Level-1) covering the study area with minimal could cover - https://earthexplorer.usgs.gov/

* Statistical Area level 3 data for Australia - https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.001July%202016?OpenDocument

* Statistical Area level 1 data for Australia - https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1270.0.55.001July%202016?OpenDocument

