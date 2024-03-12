# DataVisualizationGroupC

1. Introduction


The dataset utilized in this analysis combines data from Statistics Canada, the NHL team list endpoint, and the NHL API. It is inspired by the blog "Are Birth Dates Still Destiny for Canadian NHL Players?" by JLaw. The dataset includes information about NHL players, such as their birthdates and nationality, obtained from the NHL API. 

2. Why we choose this data


Visualizations can enable us to compare different aspects of the NHL player data, such as birth date distributions across different nationalities, player demographics, performance metrics, etc. Additionally, our objective extends to uncovering any underlying or implicit factors that may significantly influence a player's likelihood of playing in the NHL league in Canada. Through comprehensive analysis and examination, we aim to delve into various facets of the player's background, height, weight, training, and perhaps even external variables such as socio-economic status, geographical location, or cultural influences. By exploring these potential factors, we endeavor to gain deeper insights into the complex dynamics at play within the Canadian NHL league, contributing to a more nuanced understanding of the pathways to professional hockey success in Canada.
3. Questions and plans for answering


3.1 How does players geographical location of the place of residence affects the player's career?
	Variable selection: Geographical location, age, career longevity, nationality,etc
	First, we merge the geographic data with the player dataset using the city names. Then we conduct spatial analysis to visualize the distribution of players' birthplaces and their proximity to NHL team locations. Analyze how the relationship between geographic location and career outcomes may have evolved over time.
	Geographic Heatmaps: Create heatmaps to visualize the concentration of NHL players' birthplaces and their proximity to team locations.


3.2 How do birth dates continue to impact the career trajectories of Canadian NHL players?
	Variable selection: data of birth 
	To address this, we'll begin by examining the distribution of births by month in the general population (We take this from: Canada Statistics). Following that, we'll conduct an analysis of the distribution of NHL player births by month. Subsequently, we'll merge these datasets and proceed with a combined analysis. Finally, we'll create a plot to visually represent the findings, allowing for a comprehensive understanding of the relationship between birth months and NHL player recruitment patterns.

