
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


3.2 Does birthdate bias really exist in the NHL League?

	Variable selection: nhl_roster.csv, nhl_player_births.csv
	Inspired by Malcolm Gladwell's observations in "Outliers," where he notes a higher prevalence of first-quarter births in Canadian Junior Hockey, we aim to investigate whether a similar trend exists in the NHL. This inquiry involves two key steps: Firstly, we'll analyze the distribution of birthdates among individual NHL players to discern any discernible patterns or trends. Secondly, we'll delve deeper into the distribution of birthdates within each NHL team to identify potential clustering or disparities. By completing these steps, we can conclusively determine whether Gladwell's thesis holds true within the context of the NHL.
