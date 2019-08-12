# King County Housing Data Analysis

Using data describing conditions, sizes, locations, &c., of houses in King County, can we build a model to optimize the price of a house?

# Files
**column_names.md**: A not-so-accurate description of the features in the dataset.
**kc_house_data.csv**: The data set.
**index.ipynb**: A Jupyter Notebook with my code and analysis.
**nontechnical_slidweshow.pdf**: A slide deck to present findings and recommendations to prospective home buyers and sellers.
****:

# The data
The data set had features for 21000 properties in King County in the American state of Washington. My exploratory data analysis revealed collinearity among many of the features. I dropped many of them and hung onto just a few measures of the size and quality of houses and zip codes. 

# Methods
Iterative modeling revealed that up to half of the relationship between a house's price and its features was due to its zip code. Zip code is notorious for its use in misuse in housing price analysis. Here the effect was vivid. The zip codes with the strongest relationship to price were Seattle's richest and poorest neighborhoods. When I originally did this analysis I wasn't aware of the potentially socially problemaitc implications of using zip code in analysis so I cheerfully included them to increase the R^2 score of my model.

# Recommendations
My Jupyter Notebook and slide deck contain recommendations for buyers and sellers. It all comes down to 'location, location, location,' or more precisely 'zip code, zip code, zip code.'