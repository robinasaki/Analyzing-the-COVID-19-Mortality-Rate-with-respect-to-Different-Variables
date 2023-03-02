# Analyzing-the-COVID-19-Mortality-Rate-with-respect-to-Different-Variables
### Examine the relation between the COVID-19 mortality rate and confirmation count, death count, countries and their individual wealth, omicron proportion
-----
*Chenxu Robin Mao | robin.mao@mail.utoronto.ca | project 2 version*

## Summary

To date, the COVID-19 epidemic is still a major global concern. With recent data shows the COVID-19 confirmation toll reaching 671M with the total death toll of 6.83M $^{(1)}$. Different governmental institutions around the globe have brought up various policies to ensure public health; however, the distortion brought by the virus is irreversible. Thus, with the data provided by Johns Hopkins University, the World Bank and Kaggle, this report is going to investigate the relations between the COVID-19 mortality rate and certain variables, including COVID-19 confirmation count, death count, countries and their individual wealth and omicron proportion (terms will be formally defined later).

Throughout this report, the y variable will be the COVID-19 mortality rate. As being infected by COVID-19 is not as terrible as getting lethal result. Instead of mortality count, mortality rate is chosen as count is not as representative in terms of variables such as *countries* there exist different population base; as well as mortality rate will be a more challenging topic as it requires more intra-dataset calculations.

The choice of x variables includes confirmation count, death count, countries, omicron proportion. They will vary among the topics and will be introduced in detail and defined in each section. The goal of this report is to find factors that will create significant impacts on the y variable, and analyse their relation if so, or, rephrased as a research question, **"What factors will create significant impacts on the COVID-19 mortality rate?"**

To ensure precision and integrity, more detailed summaries are broken down and given in the beginning of each section with definition, including *how they are related to the research question, why they are important for the analysis, etc.* 

##### Data source

> COVID-19 Global Confirmation/Death: *https://github.com/CSSEGISandData/COVID-19*

> Global Population: *https://data.worldbank.org/indicator/SP.POP.TOTL*

> COVID-19 Variants: *https://www.kaggle.com/datasets/gpreda/covid19-variants*

> GDP per Capita: *https://data.worldbank.org/indicator/NY.GDP.PCAP.CD*

> GDP: *https://data.worldbank.org/indicator/NY.GDP.MKTP.CD*

> Dictatorship Index: *https://www.kaggle.com/datasets/mathurinache/democracy-dictatorship-index*

> Country Code: *https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes*

> Literacy Rate: *https://data.worldbank.org/indicator/SE.ADT.LITR.ZS*
<br>

*last updated 2023-03-02*
