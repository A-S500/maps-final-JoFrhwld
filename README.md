README
================

## Maps Block Project

**Due Date: April 5**

For the maps block project, you need to make a map! Your map should
utilize at least two different geographic data sets. Potential data
sources are:

-   The US census (via `{tigris}`

-   The Lexington Data Hub
    (<https://data-lfucg.hub.arcgis.com/search?collection=Dataset>

-   Open streetmaps data (via `{osmdata}` or `{osrm}`

-   Geocoded data using `{tidygeocoder}`

-   Or, *any other data source you find*.

## Your report should include:

-   At least one map.

-   A description of your data sources.

-   A discussion of what you chose to map and why.

-   A discussion of any analysis plans or challenges you had.

## Some ideas:

### Street pength per council district

According to the [Lexington pavement management
website](https://www.lexingtonky.gov/pavement-management-plan) (emphasis
added)

> Local or neighborhood streets typically receive 42% of the paving
> budget each fiscal year. *The money is split among Lexington's 12
> council districts*. The proportion of funding is determined by the
> percent of local road lane miles within each district with an overall
> condition index of less than 60 based on data.  
>
> *Individual councilmembers work with EQPW staff to make decisions
> about the maintenance of local roads* using available data and
> opportunities for economies of scale. Like high-traffic roads, the
> total funding allocated for neighborhood streets can be revised based
> on new insights from updated data, total budget levels, etc.

Make a map of [Neighborhood
Roads](https://data-lfucg.hub.arcgis.com/datasets/b0388c01870149c3987790659ac0b37f_0/about)
by [Council
District](https://data-lfucg.hub.arcgis.com/datasets/5bab826b97c84d229f7abf0bc947981c_0/about),
and calculate the total length by district.

### Running Across Campus

UK has a 10 minute buffer between adjacent class times. Make a map of
routes between various campus buildings, and report the longest walking
time and the shortest walking times.

### Bikes and Speed Limits

The [Lexington bicycle
network](https://data-lfucg.hub.arcgis.com/datasets/9abe890a42b84cc383756be74db2cfcd_0/about)
has many routes that are “Sharrows”. Combining this data with the
[Streets
data](https://data-lfucg.hub.arcgis.com/datasets/b0388c01870149c3987790659ac0b37f_0/about),
figure out the average speed limit along Sharrow routes.

### Landmarks Per Council District

The census has landmark data `tigris::landmarks()`. Which council
district has the most landmarks by area.
