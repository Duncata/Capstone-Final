 
### What is U.S. electricity generation by energy source?

In 2018, about 4,178 billion kilowatthours (kWh) (or 4.18 trillion kWh) of electricity were generated at utility-scale electricity generation facilities in the United States.1 About 63% of this electricity generation was from fossil fuels (coal, natural gas, petroleum, and other gases). About 20% was from nuclear energy, and about 17% was from renewable energy sources. The U.S. Energy Information Administration estimates that an additional 30 billion kWh of electricity generation was from small-scale solar photovoltaic systems in 2018.

The World Energy Outlook 2018 examines future patterns of a changing global energy system at a time of increasing uncertainties and finds that major transformations are underway for the global energy sector, from growing electrification to the expansion of renewables, upheavals in oil production and globalisation of natural gas markets. Across all regions and fuels, policy choices made by governments will determine the shape of the energy system of the future.

WEO 2018 details global energy trends and what possible impact they will have on supply and demand, carbon emissions, air pollution, and energy access. Its scenario-based analysis outlines different possible futures for the energy system, contrasting the path taken by current and planned policies with those that can meet long-term climate goals under the Paris Agreement, reduce air pollution, and ensure universal energy access.

### GOALS:
The goal of this project is to build a Time Series model that can predict the monthly value of Revenue in Dollars, Power Demand in MWH, Number of Customers and Cost per KWH for U.S in the next 20 years.

### HOW DOES THIS PROJECT HELP?
Power Plants, Electrical Companies, Government Agencies and Local Power Producers can utilize this model to predict and monitor power demand and supply in real time to be able to lay out plans in advance to meet the said Electrical Power supply and demand. This will also help to foresee the said increasing changing global energy system uncertainties.

### ABOUT THE DATA:
I got the data from the US Energy Information Administration(EIA). The URL to access the data “https://www.eia.gov/electricity/data.php” The data is the monthly revenue, energy consumption in mwh, Number of customers and price per kwh from 1990 to present. Each data for Residential, Commercial and Industrial is collected separately from all the US State and join them together in one data reference to time intervals. This is one of the challenges in joining all the data and put them together in accordance to the date it was collected. Cleaning the data is one I expected to be a challenge too.

We Got 28 Columns For Revenue, Power Consumptions MWH, Number of Customers and Price in KWH in every sectors like Residential, Commercial, Industrial in every State. We get the total and average to come out for the following dataset that we can used in the time series.

* date - year, month and day data collected.
* tot_thous_dlrs - Total Power Revenue in thousand Dollars
* tot_mwh - Total Power Consumption in Mega Watt Hour
* tot_count - Total Number of Customers
* tot_cents_kwh - Average Price in Kilo Watt Hour

# SLIDES

![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20201502.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20201547.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20201617.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20201650.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20201734.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20201905.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20201954.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20202035.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20202138.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20202435.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20202510.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20202605.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20202856.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20202935.png)
![](Electrical%20Prediction%20Pictures/Annotation%202019-11-26%20203040.png)
