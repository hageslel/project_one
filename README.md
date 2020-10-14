Crude Oil Production & GDP Impact on Global Warming
Global warming is the long-term heating of Earth’s climate system observed since the pre-industrial period due to human activities, primarily fossil fuel burning, which increases heat-trapping greenhouse gas levels in Earth’s atmosphere. The term is frequently used interchangeably with the term climate change, though the latter refers to both human- and naturally produced warming and the effects it has on our planet. It is most commonly measured as the average increase in Earth’s global surface temperature. Climate change is a long-term change in the average weather patterns that have come to define Earth’s local, regional and global climates. These changes have a broad range of observed effects that are synonymous with the term. Climate data records provide evidence of climate change key indicators, such as global land and ocean temperature increases; rising sea levels; ice loss at Earth’s poles and in mountain glaciers; frequency and severity changes in extreme weather such as hurricanes, heatwaves, wildfires, droughts, floods and precipitation

Project Overview:
The main purposed of the project is to identify the factors like Crude Oil production and GDP growth of the world is impacting the Global temperature and which in turn causes melting of earth glacier’s (Arctic & Antarctic).

Data sources:
World GDP Data(https://databank.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG/1ff4a498/Popular-Indicators#) World Glacier Data(https://www.epa.gov/climate-indicators/climate-change-indicators-glaciers https://www.epa.gov/climate-indicators/climate-change-indicators-arctic-sea-ice https://nsidc.org/data/glacier_inventory/query.html https://www.epa.gov/climate-indicators/climate-change-indicators-antarctic-sea-ice) Crude Oil Production(https://www.indexmundi.com/energy/?product=oil&graph=production) Global Temperature(https://data.giss.nasa.gov/gistemp/)

Key Highlights:
Data upload:
Used following pandas methods to read the data from various data sources:

read_excel
read_csv
read_html
Data Cleaning & Analysis
Used Transpose(T) method to convert rows to columns
Used column rename function.
Used drop function to drop columns.
Used pct_change(fill_method='ffill') function while calculating percentage change.
Used dropna function to drop null.
Used load_dotenv() and getenv() to access API.
Used Monte Carlo's simulation to predict temprature raise for next 10 years.
Used Monte Carlo's simulation to predict glacier loss for next 10 years(both Arctic and Antarctic).
Used concat() to combine various datasets like World GDP, Crude Oil Production, World Temperature, Arctic glacier data and Antarctic glacier data.
Used corr() function to calculate correlation between various dataframes.
Types of Plot:
Used plot() to plot some dataset.
Used hvplot() to plot graph for datasets.
Used heatmap to plot the correlations.
Used altair to plot map and graph.
New packages:
Imported altair,math & vega_datasets for this project.
