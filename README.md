# DATASET OVERVIEW
Who eats and who supplies the food we grow in Africa?

The project focuses on finding insights, patterns and trends through visualizations on food Production and Supply data in Africa.

Do all African countries have equal access to food items as regards to food supply?

Do all African countries equally produce the food we eat in Africa?

Were there food Surpluses which eventually led to food shortages in Africa?

In this project, we will be analyzing two different datasets namely food production and food supply datasets. 
These two datasets have information about food production and food supply in 45 African countries between (2004 - 2013) respectively and it was sourced from FAO (Food and Agriculture Organization of United Nations)'s website.

Later on in the project, we will carry out a hypothesis testing where we compared the growth of certain food produce with the population growth of the African countries.

The population dataset that we will use is the population data gotten from the World Bank Open Data Portal. 
The data holds the population data of 267 countries from 1960 to 2021 and we will extract the population data for the African countries we were working with in the Food Production and Supply dataset. 
With this data, we will be able to carry out some hypothesis testing.

# Metadata
## Food Production Data
The first dataset that we wil analyze is the Food Production dataset. This dataset has 23110 rows and four columns. The columns include:

* Country: The name of the African Country

* Item: The particular food item produced

* Year: The year in which a particular food item was produced

* Value: The measured value of the produced food item in Kiloton

## Food Supply Data
The second dataset that we will analyze is the Food Supply dataset. This dataset has 450 rows and three columns. The columns include:

* Country: The name of the country

* Year: The particular year a food item was supplied

* Value: The measured value of the food item in kcal/person/day

## Population Data
The third dataset which we will also analyze and then use for our hypothesis testing would be the World Bank Population Data. We will use this dataset together with extracted food production data of certain food items, and we will carry out a hypothesis testing stating that the production of these food items increased with increase in population. This dataset initially consists of 266 rows and 67 columns and after extracting the data we needed for the African countries we were working with, we finally had 40 rows and 11 columns. The columns include:

* Country Name: The name of the African Country

* 2004: the population of the country in 2004

* 2005: the population of the country in 2005

* 2006: the population of the country in 2006

* 2007: the population of the country in 2007

* 2008: the population of the country in 2008

* 2009: the population of the country in 2009

* 2010: the population of the country in 2010

* 2011: the population of the country in 2011

* 2012: the population of the country in 2012

* 2013: the population of the country in 2013

# Findings/Conclusion
* Food production in Africa experienced an upward trend over the years.

* Between 2004 and 2013, Nigeria, Egypt, and South Africa emerged as the leading food-producing nations in Africa, generating 1,628,030 kt, 877,498 kt, and 597,592 kt of food items, respectively. Notably, many other countries fell short of producing even half of Nigeria's output.

* The most cultivated food items included Cassava, Sugar Cane, Maize and its derivatives, Yam, Vegetables, and Milk (excluding butter). Conversely, the least produced items comprised Cloves, Pepper, Molluscs, Fish, Liver oil, and aquatic animals.

* Nigeria is the top cassava producing country with a total of 452,881 kiloton followed by Ghana with total cassava production of 121,026 and Angola with 121,026.
  
* Algeria is the top producing oats product with a total of 849 kilotons, followed by Ethiopia with 443 kilotons and then South Africa with a total of 406 kilotons.

* South Africa is the top Maize producing country from 2004 to 2013 having a total production of 107,343 kt followed by Nigeria with total of 76,898 kt, Egypt 70,993 kt.

* Egypt is the top rice producing country having a total production of 40,370 kiloton followed by Nigeria with 26,964 kiloton and Madagascar with 26,118 kiloton.

* A total of 39 countries consistently demonstrated substantial food production levels from 2004 to 2013, including Algeria, Angola, Benin, Burkina Faso, Cameroon, Central African Republic, Chad, Congo, Cote d'Ivoire, Egypt, Ethiopia, Gabon, Ghana, Guinea, Guinea-Bissau, Kenya, Liberia, Madagascar, Malawi, Mali, Mauritania, Mauritius, Morocco, Mozambique, Namibia, Niger, Nigeria, Rwanda, Senegal, Sierra Leone, South Africa, Sudan, Swaziland, Togo, Tunisia, Uganda, the United Republic of Tanzania, Zambia, and Zimbabwe.

* The overall food supply in Africa increased over the years.

* Egypt, Tunisia, and Morocco boasted the highest food supplies between 2004 and 2013, challenging the assumption that being the largest food producer necessarily correlates with the highest food supply.

* Nigeria consistently emerged as the top Cassava and products producer, averaging 45,288 kt of Cassava. While Ghana, Angola, and Mozambique were also Cassava-producing countries, their output did not reach half of Nigeria's production.

* Nigeria led in beverage production, followed by Burkina Faso and Uganda, although their production was less than half of Nigeria's.

* Interestingly, the highest food-producing countries experienced food surpluses that went underutilized, contributing to food shortages.

* In the detection of an outlier country in 2012, Egypt stood out with a significantly larger supply of food accessible for consumption.

* Hypothesis testing results indicate a strong linear correlation between rice and cassava production and the increase in the African population.
