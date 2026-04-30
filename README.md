### New Carwash Location

Author: Charandeep Tatlah

#### Executive summary
I will use Machine Learning techniques to determine where is the optimal geographical location in Calgary, Alberta, to open a new car wash business to maximize demand and profits?

#### Rationale
Solving this question helps understand and perfect my skills using ML to reduces the financial risk of a decision where to open a new business. Its combing theory with practical application of ML in the real world with real effects of if a venture will be profitable or a failed one.

#### Research Question
Where is the optimal geographical location in Calgary, Alberta to open a new car wash business.

The output should be an understanding of where in Calgary represent high-potential locations. I would create a ranked list of the top specific neighborhoods/streets/areas based on success score, high traffic, high income, and low competition where to open a new car wash.

#### Data Sources
I researched online how Starbucks used AI/ML to expand into Hyderabad. I found they used The Atlas Program which is the "secret sauce" of how Starbucks determines where to open stores. Its a system that relies on Esri for geo-spatial data along with analytics to finalize store location. Data they look at:
- traffic patterns
- population density
- income levels / demographics
- nearby competitor presence
- proximity to other Starbucks locations

I will use AI tools to generate car wash data that would be similar to real world data that the Atlas Program uses (data mentioned above)

#### Methodology
I will integrated three distinct data layers to create a Master Business Case Dataset:

Demand dataset: 70 major intersections with AADT (Average Annual Daily Traffic) and Road Classifications.
Competition dataset: 85 existing car wash locations with wash types and customer ratings.
Demographic dataset: 100 community profiles including Median Income, Household Age, and Apartment Density.
I will apply a Spatial Nearest-Neighbor Join to link these layers.

Then using Decision Trees I will find optimal locations in Calgary that fit the business logic.

#### Results
This project utilized Exploratory Data Analysis and Machine Learning to identify high potential locations for a new car wash business in Calgary by integrating traffic, competition, and demographic data. By engineering a custom Demand Index and a Gold Mine metric and looking at High Income Earners we created a list of underserved, high volume locations. The final GridSearchCV-tuned Decision Tree validated the findings by a rule-based framework. The top 5 locations highlighted are:

1. 121 Dr & Deerfoot Trail NE
2. 78 St & Deerfoot Trail SW
3. Edmonton Trail & 32 Ave NE
4. 26 Ave SW & Crowchild Trail SW
5. 126 St & Macleod Trail NW

#### Next steps
Since we have a curated list of optimal locations will need to physically verify the site location. 

#### Outline of project

- https://github.com/ctatlah/ai-carwash/blob/main/carwash.ipynb


##### Contact and Further Information
tatlah.c@gmail.com
