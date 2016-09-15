# HousingClustersChi
## Housing Segmentation Clustering Study Chicago Area

### Abstract 
Clustering is not yet an exact science and requires a bit of “art”, in terms of domain knowledge and expertise, to help find an optimal number of clusters and validate results.   The partitioning around medoids algorithm is applied to a Chicago Housing dataset to study changes over time as inputs to find natural clusters.  The iterative process of deciding the optimal number of clusters and applying cluster labels is shown with visual examples.  Eight housing segments are discovered to exist when examining changes in socio economic data from year 2000 to 2013.  Clustering results are visualized as external validation of cluster labels.

### Goal and Motivation 
The purpose of finding a Chicago area regional housing segmentation model is to identify communities with common set of underlying housing market characteristics.  Knowledge gained from this study would inform housing policy decisions and discussions for regional planners on diverse topics like affordable housing, health of local housing markets, and positive and negative trends observed.
Past studies had focused on only Cook Country census tracts.  This study combines both suburban and urban tracts together purposely to see what naturally occurring housing segments would result from seven counties.
Data: Sources and Pre-Processing
Our dataset is comprised of over **100 attributes for 1,980 geographical tracts** in the Chicago area, compiled from the US Census Bureau for the years **2000** and **2013**.  The attributes contain socioeconomic data including demographics, housing tenure, household income, housing costs, education, population density, age of housing, and housing density.  There were also internally collected housing market activity data like foreclosures and cash transactions.  This dataset has been compiled by the **Institute for Housing Studies at DePaul ** for a funded study to find naturally occurring housing segments for seven counties.  The dataset was split into two subsets of features, one for 2013, and one for change over time from 2000 to 2013.  This paper will focus on the analysis of the change over time dataset which had a final tally of thirty seven variables.  Please see Appendix I for an overview of data cleaning steps with an attached list of data sources.

