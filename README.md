# Ait_664

I have loaded the data of New York using the pip and using kagglehub library to directly import data into collab.

This data set presents different aspects about the given properties at New York such as the numerical attributes like the price range the numbers of bed and bath then the area size and lot size also has categorical data representing the type of property and the broker. Enduring, there are no missing values within those three sets, making it easier to work with for analysis.

The code sets up a data analysis funnel for housing price prediction and housing categorization by using a New York housing data set. The basic data preprocessing is done first: loading required libraries, replacing missing values in numeric columns with median and performing one-hot encoding on categorical variables. The dataset includes feature and targets for both regression and classification problems. For regression, the target variable is the house price, after using train and test split a `LinearRegression` model is trained and evaluated based on the Mean Absolute Error, Mean Squared Error, & R-squared etc, the performance is great with nearly negligible error rates.

In the classification task, the output shape is the price category of the houses. The features are again subjected to one-hot encoding process and the dataset formulated for use in the classification model is again divided into training and testing datasets. To predict price categories there is applied a `RandomForestClassifier` on the training set. The code offered a good framework for both tasks, but additional assessment of classification performance via accuracy, as well as confusion matrices could provide an additional precision regarding the effectiveness of the model. More holistically, the study affords a window on how preprocessing, modeling, and evaluation should be approached when constructing housing data for predictive analysis.

In this analysis, I applied two machine learning techniques to a New York housing dataset to understand price patterns.

Classification with Random Forest: I classified house prices into "High" and "Low" categories. After cleaning and splitting the data, the Random Forest model achieved nearly perfect accuracy, meaning it’s excellent at distinguishing between high and low price houses.

Clustering with K-means: I used K-means clustering to find natural groupings in the data based on Price and Number of Bedrooms. The plot showed most houses cluster around lower prices with fewer bedrooms, while some outliers represent high-priced luxury homes.

In summary, the Random Forest model provides accurate price categorization, and K-means clustering reveals distinct market segments, giving valuable insights into price trends in the real estate market.
