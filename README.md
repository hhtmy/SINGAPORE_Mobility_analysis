COVID AND GEO-SPATIAL ANALYSIS OF SINGAPORE 



Human Mobility Data Analysis

This repository contains analyses of human mobility data, specifically focusing on intra and inter-city/district traveling. The data is categorized into two subsets:

Intra City/District Traveling: Traveling within the city.
Inter City/District Traveling: Traveling outside the city within a distance range of 2 to 50 kilometers.

Analysis
Intra and Inter City Traveling Data with Date and Time
I conducted an analysis over a three-month period (March to June 2020) to understand the relationship between total people traveled, netflow, and distance traveled. Key analyses include:

Utilizing the Density-Based Spatial Clustering Algorithm (DBSCAN) on the 'length_km' and 'count' columns.
Examining the Pearson correlation coefficient and p-value for insights into the relationship between distance traveled and total netflow.
Intra and Inter City Traveling Data with Date and Without Time
I categorized the data with and without time to assess variations in mobility throughout the day.

Key Findings
DBSCAN Clustering Analysis:

<img width="490" alt="image" src="https://github.com/hhtmy/SINGAPORE_Mobility_analysis/assets/126352630/4180ac33-5935-459a-a8f5-1e27d398ca48">

Identified weak negative correlation (-0.12) between distance traveled and total people.
Statistically significant correlation (p-value: 1.4e-03) suggests non-random correlation.

KMeans Clustering Analysis:

<img width="476" alt="image" src="https://github.com/hhtmy/SINGAPORE_Mobility_analysis/assets/126352630/98feb241-ff0b-4c76-817f-f86a9e0a1ba0">

Revealed five clusters representing different travel behavior patterns throughout the weeks.
Conclusion
This analysis provides valuable insights into mobility patterns, helping identify peak and low travel weeks. Further analyses will be conducted for different COVID wave durations to enhance our understanding of the correlation between COVID and mobility.

COVID_AND_MOBILITY_ANALYSIS - Graphs illustrating COVID-19 data analysis in Singapore using Tableau data visualization. This repository contains analyses and graphs related to the COVID-19 waves.

<img width="518" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/08ad79cf-b713-44fb-9947-42211fd5f1a4">

<img width="483" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/ca684692-c16f-4960-8afa-1215680bd074">

<img width="469" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/b3e6f68a-4d60-4ed4-8af7-e46825e9ca36">

<img width="486" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/37e17b1f-d7af-4b4b-b5da-84a6d151f51f">

<img width="467" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/79de1506-2724-4470-baa5-bdc53e2a1719">

<img width="484" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/536ac198-a29c-40c1-a6e8-15d12748e906">

<img width="466" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/b60f93bb-da24-4610-8680-88352acbc1b4">

<img width="478" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/b37c42db-a6d2-438f-bba9-69268a60321f">

<img width="482" alt="image" src="https://github.com/hhtmy/COVID_AND_MOBILITY_ANALYSIS/assets/126352630/7791a36a-d207-4ba8-8383-3f28906e271f">

Density map of Singapore's COVID-19 cases based on months, including spatial distribution information.

<img width="392" alt="image" src="https://github.com/hhtmy/SINGAPORE_Mobility_analysis/assets/126352630/5e71c68b-b002-481c-b98b-3bc6ec94ce36">







