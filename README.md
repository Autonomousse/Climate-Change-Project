# Climate-Change-Project

## Articulation:

Originally, we chose to investigate whether rideshare services in the United States were affecting gas usages and ultimately harming the environment. Due to limitations in the data available, such as Uber data being privately held and energy consumption by zip code not being available, we changed the scope of our investigation.

Our new focus was on assessing whether or not energy consumption truly affects climate change and disaster impact based on various factors such as population density and transit usage.

## Cleanup and Exploration:

Data Sources:
* [OECD](http://www.oecd.org/)
* [GISS Surface Temperature (GISTEMP)](https://data.giss.nasa.gov/gistemp/)
* [Climate at a Glance (GCAG)](https://climateataglance.com/)
* [U.S. Energy Information Administration](https://www.eia.gov/)
* [EM-DAT, the International Disasters Database](https://www.emdat.be/)
* [The World Bank](https://www.worldbank.org/)

We took some time to source the data and observe it's structure and cleanliness. Afterwards, we imported it into Jupyter Notebook using Python and Pandas and began the cleaning process. This part proved to be time consuming and difficult as all of our data sources were formatted differently. Some other issues included naming differences for countries, empty cells (NaN), and different time ranges. Using Pandas to quickly locate and remove any NaN's made quick work of condensing the data into usable data sets.

Using Jupyter Notbeooks was essential as it allowed us to see our graphs and charts as we worked. It also allowed us to analyze our data as we progressed through and make comparisons quickly.

An interesting note to allow the average person to make sense of the units would be the following:
* 1 quadrillion BTU is enough power to run 17,584,264,210,333 light bulbs for 1 hour! Each household in the US would be able to have enough light bulbs for 3,039 years if they replaced an average of 45 light bulbs per household per year.

## Findings:

Below are a few of our findings, links to some written work and the powerpoint presentation are provided below:
* Increase in energy consumption seems to correlate with climate change.
* More research and information is needed to see if renewable energy sources are actually better for climate change.
* Population density and energy consumption don't always correlate in an upward trend.

[Written Analysis - Google Drive Link](https://drive.google.com/file/d/1yRqWjjVf9xezeBwVAIdEqTkBgqb49-EK/view?usp=sharing)

[Written Analysis - Word download from repository](/Analysis/Climate_Change_Major_Findings.docx)

[Powerpoint Presentation - Google Drive Link](https://docs.google.com/presentation/d/1bXYeMEF79kXsewjTNJ5lV4LHzCq3-SKhwvXft5UDpKg/edit#slide=id.g35f391192_00)

[Powerpoint Presentation - PPT download from repository](/Analysis/Climate_Change_Google_Presentation.pptx)

A formal presentation concluded this project.
