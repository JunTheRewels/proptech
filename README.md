# proptech

This file serves to aggregate, analyze, and vizualize housing unit sale price per square foot (hereafter referred to as "sale price") and gross rent (hereafter referred to as rent) in San Francisco, 2010-2016. Its purpose is to inform the viability of implementing a "proptech" one-click service for people to buy properties and then rent them.

It begins by importing from a csv database containing SF housing data and plotting the number of housing units over the measurement period.

Next it calculates the average sale price and rent for each of the years and shows it in a line plot.

It then breaks this data down by neighborhood and plots it with a dropdown widget for neighborhood selection.

Finally, it combines this data with a neighborhood location dataframe imported from a csv database and uses these sets to create an interactive scatter mapbox plot, indicating rent with size and sale price with color.

The data aggregation and visualization in this file allows effectively communicates the potential profitability of this initiative, as well as potentially optimal neighborhoods for rollout.
