# The Effect of Layovers on Airline Itinerary Market Fare in the United States
In this project, I attempt to validate the common intuition that, when purchasing an specific airline itinerary, an itinerary with more layovers is cheaper than a direct flight. Using a multiple linear regression model which I created using stepwise selection with BIC for parsimony, including an outcome variable transformation and an interaction term, I conclude that this intuition is (mostly) correct. However, depending on the distance of the trip, direct flights are not always available, in which case the cheapest itinerary changes. However, direct flights are rarely the cheapest option.

The following graphs visualize the results, associating the distance of the itinerary with the market fare for itineraries with different numbers of layovers, after controlling for: the number of passengers who have purchased the itinerary, the first (or only) operating carrier in the itinerary, and the financial quarter during which the itinerary was purchased.

[Add graphs]

Itineraries_Pt._2.html is a complete writeup of the analysis and results. For the RMarkdown file, see Itineraries_Pt._2.Rmd. 

The dataset was too large to upload to GitHub, but can be downloaded from https://www.transtats.bts.gov/Fields.asp. 
