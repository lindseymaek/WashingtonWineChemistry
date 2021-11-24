# WashingtonWineChemistry

WaWineChem.txt is a dataset of Washington State wine chemistry data curated from self-published winery sources. Wineries commonly publish information about available vintages in the form of "technical sheets" for the interested consumer. When this project was started in Fall 2020, a centralized location for these publicly-available Washington wine data did not exist. Vintage compositional data is useful for tracking trends in the wine industry. 

The dataset by column:
1) identifier - number indicating position in the dataset
2) variety - red varieties only. Single varieties have at least 80/% of the specified variety. Blends may be specified (example, Bordeaux or Rhone) if they contain at least 80/% of these varieties. In all other cases wines are referred to only as "Red Blends."
3) winery - Beginning with the data collection year 2021, wineries randomly selected from those listed on the Washington Wine Commission website at the time of data collection for that year until 20 wineries were collected for which data could be found.
4) AVA - American Viticultural Area. Only Eastern Washington AVAs as were recognized at the time of the wine bottlings are reported and may not be as specific as is currently recognized.
5) vintage - year of harvest and production. Multi-vintage products will not be included in this dataset.
6) pH - reported as listed by the winery. 
7) titratableAcidity - reported in grams per Liter as listed by the winery. The standard in the United States is to use tartaric acid equivalents and a titration endpoint of pH 8.2. The particulars of this measurement practice regarding these data have not been verified with any winery, nor are the significant figures necessarily appropriately reported.
8) ethanol - ethanol concentration represented in %v/v as reported by the winery
9) wineID - memo containing other identifying information about the wine such as the product name
10) collectionYear - year of the data collection. It is the objective of WashingtonWineChemistry repository that data will be added on a yearly basis and will consider a moving range of 4 vintage years (The 2020 collection year examines 2015-2018, the 2021 collection year examines 2016-2019 and so on). If a randomly selected winery is already present in the dataset, only new wines will be included
11) sourceDomain - original website of the winery reporting the data. Furthermore, the web pages or technical sheets, where available are also available for viewing under source files folder.


Disclaimer: These data are provided as a resource to persons interested in working with basic Washington wine compositional data, but I cannot accept liability for any incorrect claims made as drawn from these data as I do not claim that any of these data are my own. Sources are provided, but may require that the user is age 21 to enter the websites. For this reason, the winery's pdf resources, when available are also provided.

