# PowerBI_Data_Analysis_Exp_Imp
Analysis of export and import data for products classified under NCM 61, conducted from 2019 to 2021 across Brazil.

## About

- For this activity, I extracted data from the Federal Government portal available [here](https://dados.gov.br/dataset/estatisticos-do-comercio-exterior-brasileiro-de-bens/resource/d45d96ff-41e1-4c5e-bddd-5b633e1926a4?inner_span=True) and imported it into Power BI, where I created two dashboards (one for exports and another for imports) and conducted some analysis.
- The export and import spreadsheets available at the link are in .csv format and contain data from 1997 to 2022 for all product classifications (NCM).
- Additionally, spreadsheets for country codes and transport modes were also imported.
- The analyses derived from the dashboards are documented in "Analise_Exp_Imp_Brasil_NCM61.pdf," and the dashboards are in .pdf format.

## Technology

  - Power BI
  
## Steps
  
- [x] Loading the complete export and import .csv tables into Power BI;
- [x] Importing two additional correlation and classification tables for the "Country Code" and "Transport Mode Code" columns;
- [x] Establishing relationships between the three tables (Import/Export, Country Classification, Transport Mode Code);
- [x] Filtering the "YEAR" column for 2019 to 2021;
- [x] Filtering the "NCM" column for strings starting with 61 (the analysis was focused solely on NCM 61);
- [x] Developing the dashboards;
- [x] Analyzing and drawing conclusions from the dashboards.

<details>
  <summary><h2>Analysis and Final Conclusions</h2></summary>

# EXPORTS

## Exports by Year:
- A total of 80,066 exports were made during the analyzed period, totaling a value of US$ 260.84 million.
- In 2019, there were 26,673 exports, in 2020, 23,137, and in 2021, 30,256 exports.
- The number of exports in 2021 is higher compared to 2019, which is a positive sign. The year 2020 shows the lowest number among the three years, likely due to the pandemic.

## Exports by Country:
- The top 10 countries to which Brazil exports the most have remained unchanged since 2019. The rankings are as follows: Paraguay, United States, Uruguay, Bolivia, Chile, Portugal, Japan, Costa Rica, Argentina, and Ecuador, in that order.
- However, in 2021, the United States nearly caught up with Paraguay, almost tying in the number of exports (Paraguay with 3,495 and the United States with 3,477). Therefore, it is expected that the United States will surpass Paraguay for the top position in 2022.
- Additionally, the top 3, 4, and 5 positions, occupied by Uruguay, Bolivia, and Chile, respectively, previously showed a clear gap in the number of exports. In 2021, this gap became minimal. Bolivia and Chile now show similar export figures.

## Exports by Month:
- December is the month with the highest number of exports, followed by June throughout the analyzed period.
- January is the month with the lowest number of exports, followed by February.
- From March to April, the number of exports begins to reach the annual average.

## Transport Modes:
- The most commonly used transport mode is air freight, followed by road and sea transport.
- Air transport is predominantly used for exports to the United States, Chile, Portugal, Japan, Costa Rica, and Ecuador.
- For Paraguay, Uruguay, and Argentina, most exports are made by road transport.
- For Bolivia, transport is divided between air and road, but road transport is more frequent.
- Sea transport, the third most used method, is most frequent for exports to Costa Rica.

# IMPORTS

## Imports by Year:
- A total of 68,960 imports were made during the analyzed period, totaling a value of US$ 2.09 billion.
- In 2019, there were 26,917 imports, in 2020, 19,679, and in 2021, 22,364 imports.
- The number of imports in 2021 is lower than in 2019, showing a significant drop. A decline was also observed in 2020, similar to exports, but a slight increase was noted the following year.

## Imports by Country:
- The top 10 countries from which Brazil imports the most have also remained unchanged since 2019. The leading country is China, followed by Italy and Vietnam in second and third place, respectively.
- The trend is expected to continue in the same order, as these countries show a steady growth over the years.

## Imports by Month:
- February is the month with the highest number of imports, followed by March.
- April is the month with the lowest number of imports, followed by June.
- April, May, June, July, October, November, and December all show imports below the annual average, considering the entire period.

## Transport Modes:
- The most commonly used transport mode for imports is sea freight, followed by air and fictitious entry/exit.
- Sea transport is the most frequent for imports from China, Vietnam, Bangladesh, Cambodia, and Sri Lanka. Other countries tend to use air transport more.
</details>
