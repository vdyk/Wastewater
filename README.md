# Wastewater Analysis Project

![This is an image](Project_Mgmt/wastewater.jpg)

## SCENARIO
Wastewater analysis is a rapidly developing scientific discipline with the potential for monitoring illicit drug use. The European Monitoring Centre for Drugs and Drug Addiction (EMCDDA) works closely with the Sewage analysis group (SCORE) which has been collecting data indicating the amount of drug residues in wastewater in major European cities since 2011. In this open source data project we explore geographical and temporal trends in illicit drug use covering cannabis, cocaine, amphetamine, methamphetamine and MDMA (ecstasy) and examine the relationship between drug usage and wealth (GDP per Capita).

## PROJECT DATASET
- 2 Datasets including information about measured values indicating the amount of drug residues between 2011-2021 and one about the sites (wastewater treatment centers) where the measurements have been conducted. Datasets accessed from the [European data portal](https://data.europa.eu/data/datasets/drugs-in-municipal-wastewater-in-selected-european-cities?locale=en)
- A customised dataset including GDP per Capita for the examined years and selected European countries, which have cities participating in the wastewater analysis study.  Dataset accessed from the [World Bank Databank](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD)

## TOOLS USED
- Python/ Pandas for data cleaning and manipulation
-	Python / Matplotlib, Seaborn, Folium for data visualisations
- Python / Scikit-learn for regression analysis and clustering
- Python / Statsmodels for time series analysis
-	IDE: MS Visual Studio Code
- Tableau for final presentation

## TASKS PERFORMED
- [x] Loaded the 3 datasets into VS Code 
- [x] Performed data cleaning, consistency checks and merged the 3 datasets
- [x] Explored relationships among variables (correlation matrix, scatterplots, pairplot, categorical plot)
- [x] Created a choropleth map for a selected year and metabolite
- [x] Performed regression analysis: GDP per Capita vs. Daily mean of drug residue in wastewater
- [x] Performed clustering : looking for meaningful subgroups in the dataset
- [x] Conducted time series analysis for a a selected year and metabolite
- [x] Created visualizations in Tableau to make insights easier consumable for the presentation???s audience. Link to the [Storyboard](https://public.tableau.com/views/DrugsinmunicipalwastewaterinselectedEuropeancities/STORY?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) . 
- [x] Key aspects presented:
   - Which illicit drugs are the most used in which area of Europe? 
   - What temporal trends can be observed? 
   - How did the pandemic affect the drug use in 2020-2021 when social events and interactions were strongly limited? 
   - Is there a connection between illicit drug use and country???s wealth (GDP per capita)? 
