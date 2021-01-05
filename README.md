![Quake Slide](https://github.com/nickmangarella/Project-Quake/tree/quake/images/QuakeSlide.png)

Project Team:

- Jordan Gilmartin
- Lynell Robinson
- Min Xie
- Nick Mangarella
- Sushama Kunnath

In this project we explored earthquake data that was sourced from the United States Geological Survey (USGS) .  According to Wikipedia, "the USGS studies the landscape of the US, its natural resources, and the natural hazards that threaten it".[^1] 

Some questions we developed at the outset and were hoping that the data might be able to tell us were:

- Has the frequency of earthquakes increased over time?
- Has the severity (magnitude[^2]) of earthquakes increased over time?
- Has the intensity (MMI[^3]) of earthquakes increased over time?
- Is there a correlation between depth and magnitude?
- Is there a correlation between significance[^4] and magnitude?

To try and ensure we covered as much ground as possible, we pulled annual data going back to 1980 using one of the USGS' APIs.   

The resulting dataset was very large and there was also some info missing in prior decades so we wound up filtering based on earthquakes of magnitude greater than five.  

In terms of geography we focused initially on earthquakes across the entire globe and then further on in the project we narrowed our concentration to the US experience.  

Summary of the APIs / Tools that we used for this project:

- USGS API
- Google Maps API
- Jupyter Notebook
- Python
- Pandas
- Matplotlib

Some of the highlights of our charts / analysis:

- Quantity of Earthquakes Over Time - 1980 to 2020
- Magnitude by Decade
- 25 Largest Earthquakes by Magnitude
- Correlation of Magnitude vs Depth
- Correlation of Magnitude vs Significance
- Intensity Scale
- Top 10 Countries - Magnitude > 7
- Map of US Earthquakes Over Time
- US Earthquake Magnitudes - 1980 to 2020

We were able to observe the following:

There is a large correlation between magnitude and significance.  

There is very little correlation between magnitude and depth.  

Most of the larger earthquakes appear to take place in Western US / Eastern Asia.  

Ultimately, while the data at face value appear to support the hypothesis that earthquakes are increasing over time, there is a technological growth component here that is beyond the scope of our research and which may partly or wholly invalidate that notion, i.e. the data do not control for advancements in seismic technology which may wind up accounting for most or all of the apparent increase in frequency of earthquakes over time. 





[^1]: https://en.wikipedia.org/wiki/United_States_Geological_Survey
[^2]: Magnitude is defined here  https://www.usgs.gov/natural-hazards/earthquake-hazards/science/earthquake-magnitude-energy-release-and-shaking-intensity?qt-science_center_objects=0#qt-science_center_objects
[^3]: MMI is defined here https://www.usgs.gov/natural-hazards/earthquake-hazards/science/earthquake-magnitude-energy-release-and-shaking-intensity?qt-science_center_objects=0#qt-science_center_objects
[^4]: Significance is defined here https://earthquake.usgs.gov/earthquakes/browse/significant.php
