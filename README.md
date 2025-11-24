# bpp_module1_project

Repository for the bpp apprenticeship module 1 assessment.

## TODO

- Some really good hints from Topic 6 session. Checkout the notes.
  - Also some good ideas for analyses to do. Noted in **00_m1t6_Notes.md** and the "pan_course" **M1_hints&Tips.md**.
  - Probably want to refernce some of the articles in the **DESD_6_Links.txt**.

## Daily Setup

- Add topic folders
- Create notes .md
  - 00_m[module number]t[topic number]_notes.md
- Create experiment .md
  - 01_m[module number]t[topic number]_experiment.ipynb
- Copy over session material

## Datasets

Investigating crop yield and weather interaction.

- Crop yields from DEFRA.
- Weather data from Met Office.

### Crop yields

Crop yields are provided by year. There are a range of datasets available under the **Structure of the agricultural industry** collection. Each year has a number of datasets. I will be using the Farming **Farming Statistics – final crop areas, yields, livestock populations and agricultural workforce at 1 June 2021 - United Kingdom**

Datasets are presented by year. I could analyse a single year between regions. Or a single region between years.

Exploratory Data Analysis will help to refine the research question.

- Structure of the agricultural industry: <https://www.gov.uk/government/collections/structure-of-the-agricultural-industry#data-sets>
- Farming Statistics – final crop areas, yields, livestock populations and agricultural workforce at 1 June 2021 - United Kingdom <https://www.gov.uk/government/statistics/farming-statistics-final-crop-areas-yields-livestock-populations-and-agricultural-workforce-at-1-june-2021-uk>

Narrowed down to Ceral and oilseed-rape production (dataset):

- <https://www.gov.uk/government/statistics/cereal-and-oilseed-rape-production>

**N.B.** Further exploration of datasets on the DEFRA site will be necessary. This may possibly lead to just looking at one year but multiple regions. Could very well just look at average rainfall and/or temperature by region for one crop. Simple dataset. Do this first, then extend if there is time.

### Weather data

I want to inestigate the influence of weather on crop yields. Likely to focus on either rainfall or temperature, though both could be assessed.

Exploratory Data Analysis will help to refine the research question.

Weather data will be sourced from the MetOffice.

This looks like a promising resources:

- CEDA Archive <https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1/>

This was linked from <https://www.metoffice.gov.uk/research/climate/maps-and-data/data/index> as the MIDAS-Open dataset.

#### Data Gathering

First trial data sourced from:

- <https://www.metoffice.gov.uk/research/climate/maps-and-data/uk-and-regional-series>

Provided as .txt file through url:

- <https://www.metoffice.gov.uk/pub/data/weather/uk/climate/datasets/Rainfall/date/East_Anglia.txt>

Could potentially pull via URL, but probably take more time than just copying.

#### Data Wrangling

What data wrangling will be required? The process of transforming data into a format to be used for data analytics. To create a clean, reliable dataset that rpovides accuaate and actioanlble insights.

- Correcting errors.
- Handling missing values.
- Merging datasets.
- Data analysis.
