# Predicting Housing Prices With Random Forest 

### Motivation : 
This was a simple project I did in preparation for an Interview.  The purpose is not to show a complex analysis, but rather demonstrate some of the skills up my sleeve.

### Summary : 
For this I use the San Luis Obipso houses dataset (https://wiki.csc.calpoly.edu/datasets/wiki/Houses), which has very basic properties compared to ames housing.  Here are the features in question:
<br>

 - **MLS**: Multiple listing service number for the house (unique ID).
 - **Location**: city/town where the house is located. Most locations are in San Luis Obispo county and northern Santa Barbara county (Santa Maria-Orcutt, Lompoc, Guadelupe, Los Alamos), but there some out of area locations as well.
 - **Price**: the most recent listing price of the house (in dollars).
 - **Bedrooms**: number of bedrooms.
 - **Bathrooms**: number of bathrooms.
 - **Size**: size of the house in square feet.
 - **Price/SQ.ft**: price of the house per square foot.
 - **Status**: type of sale. Thee types are represented in the dataset: Short Sale, Foreclosure and Regular.
 <br>
 
 In addition to these, I use a little Web Scraping to fetch population densities from each area.  
 <br>
 Using a Random Forest Regressor, we predict housing prices on a Testing set with a score of $R^2 = 0.947$, which is pretty good for a sample project!
 <br>
 
 ### Key Concepts : 
- Data Manipulation (via pandas)
- Exploratory Data Analysis / Statistics
- Visualizations
- Sci-Kit Learn
- Machine Learning 
- Web scraping 
