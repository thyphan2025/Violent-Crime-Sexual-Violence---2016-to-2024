# VIOLENT CRIME AND SEXUAL VIOLENCE FROM 2016 TO 2024

## Introduction

The tables on violent and sexual crime include national figures on offences for and
victims of selected crimes recorded by the police or other law enforcement agencies.
These data are submitted by Member States through the United Nations Survey of
Crime Trends and Operations of Criminal Justice Systems (UN-CTS) or other means.

The project focuses on analyzing total victims of violent and sexual crimes happened in various countries such as Columbia, Brazil, United States, etc. 
from 2016 to 2024. The goal is to explore total victims per region, subregion, country and category from 2016 to 2024 and how number of victims changed through 2016 to 2024.

## Research Questions

1. How many victims of violent and sexual crimes per region, country and category from 2016 and 2024?
2. How violent and sexual crimes changed over the years of 2016 to 2024?
3. What are top ten countries with the highest victims and top six categories over the years?

## Libraries Used
pandas - data manipulation and analysis

seaborn - statistical data visualization

matplotlib - plotting and charting

## Data Source

Office on Drugs and Crime - Data Portal

[Sexual Violence and Crime](https://data.unodc.org/datareport/violent-offences)

## Project Files
* **README.md**  - project description and report
* **Violence Crime and Sexual Violence.ipynb** - Python Notebook
* **data_cts_violent_and_sexual_crime.xlsx** - excel file

## Method for Data Analysis

- Data cleaning and preprocessing were then performed using Pandas in Python, checking for null values and preparing data for exploratory analysis.
- Univariate analysis - such as calculating total victims per region, subregion, and category.
- Bivariate analysis - such as exploring total victims per category and per region and total victims per category and per country.
- Univariate analysis - such as identifying top ten countries with highest victims, exploring top three countries with highest victims.
_ Bivariate analysis - such as animated visualization of top ten countries and top five categories with total victims changed over years.

 ## Results

 ### Visualization of Total Victims By Region

<img width="1206" height="673" alt="image" src="https://github.com/user-attachments/assets/86453fa7-66d9-42d5-bfd2-a65e9de6fc6b" />

The bar plot display total victims for all regions such as Americas, Europe, Africa, Asia and Oceania. Americas has total of 41,302,150 victims from 2016 to 2024. Followed by Europe and Asia, there are total victims of 21,969,689 and 3,361,460 from 2016 to 2024, respectively. 
Oceania has total victims of 1,513,113 from 2016 to 2024.

### Visualization of Total Victims by Subregion

<img width="339" height="429" alt="image" src="https://github.com/user-attachments/assets/a8d9985b-6c79-4429-91f8-00a89bc256f3" />
<img width="1298" height="669" alt="image" src="https://github.com/user-attachments/assets/729f3dce-786f-4ec7-a847-24dd06987a36" />

Taking one step further, I look into the bar plot of total victims in subregions such as Latin America and Caribean, Northern America, Western Europe, Northern Europe, Southern Europe, Sub-Saharan Africa and more.  Latin America and Caribbean is leading the bar chart, 28,196,742, approximately two times more than the second, Northern America, 13,105,408.
As we can see, the Americas region leads the bar chart because of Latin America and Caribean subregion.

### Visualization of Total Victims per each Category

<img width="470" height="288" alt="image" src="https://github.com/user-attachments/assets/277c1870-4294-42cb-b55d-7957fbddbfa3" />
<img width="1312" height="670" alt="image" src="https://github.com/user-attachments/assets/48ee0b4d-ff5e-4003-b33b-e0303380ca9c" />

According to [Data UNODC - Metadata Information](https://data.unodc.org/sites/dataportal.unodc.org/files/2026-07/metadata_violent_and_sexual_crime.pdf), Serious assault defines as intentional or reckless application of serious physical force on the body, which results in serious bodily injury. 
Serious assault with total victims of 28,341,950, the category with the highest victims, is over 8 millions more than Robbery, 20,469,770, the second in the bar chart.
Besides Robbery and Serious Assault, which are the first and the second in the bar chart, Sexual violence is 6,918,919 total victims, which is approximately three times less than the second category and four times less than the first category in the bar chart.

### Visualization of Total Victims by Category per Region (Top 10)

<img width="475" height="301" alt="image" src="https://github.com/user-attachments/assets/6fb98884-edf1-4936-a63a-40f30ff3ae91" />
<img width="1284" height="668" alt="image" src="https://github.com/user-attachments/assets/1d8bdbfd-875d-413c-bb4e-1624aac6917f" />

The bar chart displays total victims for top 10 categories with responding regions. Robbery in Americas is leading the bar chart ( Latin Americas and Caribean and United States) with 16,057,550 victims. Serious assault in Americas with 15,411,881 total victims is the second leading in the bar chart.

### Visualization of Total Victims per Country (Top 10)

<img width="354" height="291" alt="image" src="https://github.com/user-attachments/assets/4a50c435-25ea-4245-91ce-24f4adb1087d" />
<img width="1297" height="670" alt="image" src="https://github.com/user-attachments/assets/11372e15-7c8b-4d22-b381-fa882c4dfe20" />

The previous bar chart showed us total victims in regions and categories. To take one step further, we will look into top ten countries with highest total victims.
The bar chart displays total victims for top 10 countries. Brazil is leading the chart with the highest total victims, 15,894,035. Followed by United States and United Kingdom, there are 10,490,901 and 6,192,831 total victims. France, the fourth on the bar chart, 5,939,318, which is 1 million less than United Kingdom.

### Visualization of Total Victims per Category in Brazil

<img width="476" height="281" alt="image" src="https://github.com/user-attachments/assets/7ab0e342-687b-4fd9-84d9-3b48ea4509eb" />
<img width="1297" height="671" alt="image" src="https://github.com/user-attachments/assets/0e49d2ad-b3c0-4f21-acae-be2b224db9cd" />

For further details, we explore the bar chart displaying total victims for each category in Brazil. Robbery dominates the chart for categories in Brazil, which also be the reason for Brazil with its highest total victims. Robbery is three times more than the second category, Serious assault.

### Visualization of Total Victims per Category in United States

<img width="867" height="541" alt="image" src="https://github.com/user-attachments/assets/7eaff4f9-72f9-4f04-bf54-a76547276128" />

For further details, we explore the bar chart displaying total victims for each category in United States. Serious assault dominates the chart for categories in the United States, which is three times more than Robbery, the second category.

### Visualization of Total Victims per Category in United Kingdom

<img width="1093" height="688" alt="image" src="https://github.com/user-attachments/assets/a96de852-aae7-4807-bac2-9f99ed4ee204" />

The bar chart display total victims for each category in United Kingdom. Serious assault dominates the chart, which three times more than the second category, Sexual violence. 

### Visualization of Total Victims per Category in France

<img width="1272" height="721" alt="image" src="https://github.com/user-attachments/assets/36d7d3ef-0e6c-4526-b9c0-01d56e052beb" />

The bar chart display total victims for each category in France. Serious assault dominates the chart, which is three times more than second category, Acts intended to induce fear or emotional distress. Acts intended to induce fear or emotional distress defines as fear or emotional distress caused by
a person’s behavior or act.

### Visualization of Total Victims per Category per Country (Top 10)

<img width="503" height="294" alt="image" src="https://github.com/user-attachments/assets/c35de08c-277d-4c5f-94c7-a36f7d150287" />
<img width="1280" height="676" alt="image" src="https://github.com/user-attachments/assets/25ba7e29-d49f-403f-9bdf-2f13c8eab7d7" />

The bar chart display total victims for top 10 categories with responding countries. Robbery in Brazil, the leading category in the bar chart, 10,528,538, is three times more than the second in the bar chart, Serious assault in United States, 6,980,921.
Followed the second in the bar chart, Serious assault in Brazil is 3,818,908, three times less than Serious assault in United States. Brazil dominates the bar chart with highest total victims in Robbery and Serious Assault, which is a serious concern in this country that requires immediate actions to prevent further issues.

### Animation of Top 10 Countries over Years

You can use the Jupyter notebook to view the animated visualization of top 10 countries from 2016 to 2024, which changed across years. 

<img width="1441" height="477" alt="image" src="https://github.com/user-attachments/assets/7b96a104-a6a5-42c3-937b-f1a3826dda2c" />

### Animation of Top 5 Categories with highest Total Victims over Years

You can use the Jupyter Notebook to view the animated visualization of top 5 categories from 2016 to 2024, which changed across years.

<img width="1421" height="478" alt="image" src="https://github.com/user-attachments/assets/d12fdc8e-d002-4462-9d30-e4426915db6f" />















