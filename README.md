# Airbnb User Destination

<code><img width="100%" src="https://github.com/lucasquemelli/airbnb/blob/main/images/airbnb.png"></code>

# 1. Business Problem

### Description

---

**Airbnb** is an American company which operates an online marketplace focused on short-term homestays and experiences. Its business model allows anyone to offer or book accommodation around the world.

**Purpose:** to predict which country a new user's first booking destination will be. This is a classification problem. 

**Strategy:** we used the CRISP-DS (Cross-Industry Process - Data Science) as the main project management methodology.

Dataset description and all files may be checked and downloaded through [Kaggle - Airbnb New User Bookings](https://www.kaggle.com/competitions/airbnb-recruiting-new-user-bookings/data).

# 2. Business Assumptions (Formulated Hypotheses)

The following hypotheses were formulated in order to be tested:

**H01.** To every destiny, users take 15 days, on median, to do the first booking, since their first activity.

**H02.** To every destiny, users take 3 days, on median, from first activity until create an account.

**H03.** The number of bookings to US increase 20% yearly during the summer.

**H04.** Female users booking are 10% higher to out of US than inside.

**H05.** Google Marketing channel represents 40% of the bookings to out of US.

**H06.** Country destination US represent more than 20% on every channel.

**H07.** The average age is 35 years old to every country destination.

**H08.** The users percentage who uses Airbnb in the English language to book is higher than 90% to every country destination.

**H09.** The number of bookings per year increases.

# 3. Solution Strategy

**Step 01 - Data Description:** cleaning data, changing data type, treating missing values, check balance of data, and descriptive statistics.

**Step 02 - Feature Engineering:** creating new features that may better explain the phenomenon.

**Step 03 - Feature Filtering and Selection:** rows filtering and columns selection.

**Step 04 - Balanced Dataset:** balance of the dataset.

**Step 05 - Exploratory Data Analysis (EDA):** univariate analysis, bivariate analysis (hypotheses test) and multivariate analysis.

**Step 06 - Data Preparation:** rescaling, encoding and transformation.

**Step 07 - Feature Selection:** removing high correlated features and using Boruta algorihtm with Random Forest Regressor to select the most relevant features.

**Step 08 - Machine Learning Modelling:** testing and comparing Machine Learning models.

# 4. Top 3 Data Insights

**H03.** The number of bookings to US increase 20% yearly during the summer.

**FALSE.** There was a higher increase up to 2013. However, in 2014 and 2015 there was a decrease.

**H05.** Google Marketing channel represents 40% of the bookings to out of US.

**FALSE.** The marketing channels mostly used from users who go outside US are basic and facebook. These channels represents almost 100% of our base.

**H07.** The average age is 35 years old to every country destination.

**TRUE.** The average and the median age are very close to 35 for every country destination.

# 5. Business Results

Random Forest predict country destination for Airbnb user with 99% of average accuracy. 

# 6. Conclusions

We used Artifical Neural Network (ANN) to predict Airbnb users country destination, yet due to the low number of rows, this model did not perform well. Thus, we used Random Forest Regressor and we achieved an average accuracy of 99%. 

# 7. Next Steps

Since we achieved an excellent performance with Random Forest Regressor, no further steps are necessary. Yet, we may try to improve the Neural Network performance by changing its configuration and testing it. 
