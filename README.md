# Group Project 2

## Team Name
21479 Group 6


## Team Members

- [Shaniya Scales](https://www.github.com/shaniyas)

- [Saniya Bedi](https://github.com/Saniya-Bedi)

- [Charlie Jones](https://github.com/jonescharlie)

## Data Set Description
The U.S. Food Imports data product is an annually published statistical summary of the value and volume of food imports coming into the United States.
U.S. consumers demand variety, quality, and convenience in the foods they consume. As U.S. consumers have become wealthier and more ethnically diverse, their food basket reflects a growing share of tropical products, spices, and imported gourmet products.
This data set provides import values of edible products (food and beverages) entering U.S. ports and the products’ origin of shipment. The data comes from the U.S. Department of Commerce, Bureau of the Census. The dataset includes 7 columns. The columns for category, commodity, subcategory, UOM (unit of measurement), and country are all string types, with country also having a geographic role. The columns for food value and year are numbers. Food and beverage import values are compiled by calendar year into food groups, corresponding to major commodities or level of processing. The Harmonized System (HS) codes and the corresponding commodities and food products are detailed in the data file. 25 years of annual data are included, enabling users to track long-term growth patterns.

## Question 1: Which regions export which commodities to the US?
<img width="1431" alt="Screenshot 2025-04-22 at 12 02 09 PM" src="https://github.com/user-attachments/assets/279c56a4-1435-4d5c-84fa-63a59dc2377e" />

**Data Manipulation:** 
The data included 61 countries. In order to put countries into their respective regions, we used a CASE WHEN statement in a calculated field, Region. For example, "CASE WHEN "Canada" THEN "North America". We also filtered out the countries that were uncategorized into a region (I.e. "Rest of World"). 

**Implications of Question 1:**
The implications of Question 2 highlight two major themes. First, there is clear regional specialization in food production across the world. Different regions focus on specific categories: South America is known for fruits and coffee, Asia specializes in grains, fish, and nuts, while Europe is prominent in beverages, dairy, and cocoa. Understanding these specialization patterns can help optimize trade partnerships and supply chain logistics by leveraging regional strengths. Second, the U.S. food system shows a strong dependency on global markets. Many products, such as vegetables, meats, and spices, are sourced internationally. This reliance means that disruptions in specific regions—whether from conflict, policy changes, or climate events—can significantly impact certain sectors of the U.S. food supply.

**How the data can be used:**
Policymakers can leverage these insights to identify critical supply chains and prioritize the development of strategic trade agreements or diversification initiatives. A thorough understanding of import concentration can also enhance efforts to monitor and mitigate food security risks. Importers and retailers may focus on strengthening supplier relationships in key production regions and utilize historical trends to forecast demand and optimize seasonal inventory planning. Additionally, researchers and economists can examine long-term shifts in U.S. food consumption patterns and investigate the correlations between cultural demographic changes and the growth of food imports.


## Question 2: How have imports changed in the last 20 years?
<img width="894" alt="Screenshot 2025-04-27 at 5 05 29 PM" src="https://github.com/user-attachments/assets/9b215237-b890-44db-bbf4-b6d10fed2212" />
<img width="892" alt="Screenshot 2025-04-27 at 5 05 45 PM" src="https://github.com/user-attachments/assets/3625b286-cd90-405f-96f3-1a245c8c7312" />


**Data Manipulation:** 
There were some uncategorized country fields: “World”, “World (quantity)”, and “Rest of World” that were filtered out. We also created a calculated field to change the food value from millions to billions, for clarity.

**Implications of Question 2:**


**How the data can be used:**




## Tableau Packaged Workbook
The packaged workbook for our project can be found in a seperate file in our repository.
