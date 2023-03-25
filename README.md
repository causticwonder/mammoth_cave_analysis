# mammoth_cave_analysis

My analysis compares the annual visitation numbers for Mammoth Cave National Park to the average annual gas prices. I want to see if there's a correlation between park visitors and gas prices. Do more people visit the park when gas prices are lower?

I pulled the Mammoth Cave dataset from the irma.nps.gov data statistics site: https://irma.nps.gov/Stats/SSRSReports/Park%20Specific%20Reports/Annual%20Park%20Recreation%20Visitation%20(1904%20-%20Last%20Calendar%20Year)?Park=MACA

I had to download the file to an excel format and save locally. 

The gas price dataset came from: https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=PET&s=EMM_EPM0_PTE_NUS_DPG&f=A

Also downloaded and saved locally. 

Feature 1: Downloaded 2 data sets, Mammoth Cave visitors data and Average Gas Prices data. 

Feature 2: Clean amd merge data using pandas df and merge functions. 

Feature 3: Create Tableau dashboard to show analysis.

Feature 4: Markdown cells and Readme file. Analysis of project/thought process. 

The analysis showed that there is a significant corrlation between average gas prices and visitors to the park. Lower gas prices bring more visitors, with one exception. The year 2020 was a low price/low visit year. I think that year was a big un-fun for everyone. Social Distancing took a toll on the parks visitor numbers, despite gas prices being at a low level. 

I created a Tableau dashboard to showcase this correlation, which can be found here: https://public.tableau.com/app/profile/tanya.fowler/viz/VisitorstoMammothCavebyGasPrices/VisitvsPriceLineChart?publish=yes
