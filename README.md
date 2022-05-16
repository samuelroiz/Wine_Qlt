## About the project
<p> The main focus is to build a machine learning model that attempts to predict whether a wine will become high quality or not for the wine quality data. Wine quality is determined by a group opinion of wine experts using their smell, taste, and brain to lend wine reviews to the market buy and sell notes backing the wine on a secondary market. Wine quality data offer their previous data through Kaggle and API. Utilized the given data from Kaggle and API to create machine learning models to classify the wine quality levels. The model to focus on is the Logistic Regression model. </p>

### What is Wine Quality?
<p> Wine quality is determined by a group opinion of wine experts using their smell, taste, and brain. Everyone has different due to their preference and taste buds and because everyone is different, quality scores are reviewed by a group of experienced tasters. The age of wine determines the wine quality as older wine intends to have a higher wine status. In a study, wine can age sufficiently due to acidity, tannin, alcohol level, and residual sugar. </p>

### What is Acidity, Tannin, Alcohol level, and Residual sugar?
<p>Acidity is an acid substance found in wine, soil, or water. Acidity changes over the course when age due to acids dissolving and flattening. Wine with low acidity cannot age in the long run. Tannin is found in red wine and sometimes white whine. Tannin is an acid substance adding a bitter taste. Similar to acidity, higher tannin ages in the long run and drives the wine quality vastly. Alcohol level or percentages is a portion of alcohol in your body from drinking alcoholic drinks. Higher alcohol percentages intend to destroy the wine aging as lower alcohol levels age broadly. Residual sugar comes from an essential element found in wine. Higher sugar content found in wine intends to age significantly than other less sugar wine.   </p>

### What is fixed, volatile, citric, chloride, and sulfur dioxide? 
<p> Wine has many acids as the data contains fixed acidity, volatile acidity, and citric acid. Fixed acidity is an acid found in wine used for sour flavor and fights against microbial infection. The volatile acidity is a process that converts wine to vinegar used for tasting. Citric acid is an organic mixture found in wine to add flavor. The wine has multiple organic compounds such as chloride, free sulfur dioxide, and total sulfur dioxide. Chloride is an organic mixture element to help diminish acid groups. It also supports balancing the pH to keep the acid levels in equilibrium. Sulfur dioxide is essential in wine as it prevents spoilage and oxidation. When wine or any fruit container is opened and left out in the open for too long, the wine or fruit turns brown. That is the function of oxidation. Free sulfur dioxide (FS02) is a measurement of sulfur dioxide in the wine that has not responded yet. Sulfur dioxide contains spoilage and oxidation as it is necessary to have some free sulfur dioxide to protect the wine. Once the wine is open, the FS02 is gone. Total sulfur dioxide (TSO2) is similar to chloride as a chemical balance. If the total sulfur dioxide is high, the wine is much more stable as sulfur dioxide easier to balance. TSO2 is a measure of free sulfur dioxide (FSO2) since if the wine has low or high free sulfur dioxide, then total sulfur dioxide can give the context of how much sulfur dioxide is in the wine.   </p>

### What is density? 
<p> Density in the wine means the mass per volume as the water has a density of 0.997 gram cubic centimeters, but wine has a density of 1.080 to 1.090-gram cubic centimeters. The wine juice density founded to have eight to ten percent denser than water. Once the wine juice merges alcohol and sugar, the density of wine intends to be around 0.996 gram cubic centimeters. pH is a measurement of the acidity and base of water ranging from 0 to 14. The levels are zero is acid, seven is neutral, and fourteen is base. pH level lower than seven is more acidity as higher is more base. In wine, the pH is three to four due to fixed acidity, volatile acidity, citric acid, and other added substances. pH plays an essential role in wine to support balancing and prevent too much acid.   </p>

## About the Data

![Type of Wine Count](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Info_Data/count_type_of_wine.png)

<p> In the following image, there is 24.6 percent of red wine and 75.4 percentage of white wine. This is important information because if the model wants to predict the type of wine, then the percentage of types must be converted to fifty-fifty. If not converted, then the model will have outliers and bias feedback since white win is favored. </p>

<p></p>

## Model Steps

## Predict Wine Type

### Step 1 to 3 
![Step 1 to 3](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_1_to_3.png)

### Step 4

![Step 4](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_4.png)

![Step 4 Part 1](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_4_part_1.png)

#### Important note:
<p><b> The 'X' is assigned as all of the columns except the "type" column since the "type" column is assigned to 'y' as the target for the model. The model will have one target column and the rest of the columns will be the data to support the model predictions. This applies to all of the codes. </b> </p>

![Step 4 Part 2](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_4_part_2.png)

<p> The following image displays the steps of SMOTE, train, split, and test code. All models must use the SMOTE, train, split, and test because it allows the AI to determine the data to get the best results for the model. Almost professional fields such as engineering, data analysis, actuaries, and others use SMOTE, train, split, or test for their models to get their best interest. </p>

#### How does SMOTE work and what is it doing to the data? 

<p> Synthetic Minority Oversampling Technique, or SMOTE for short. SMOTE permits users to solve data sets with irregular data to oversample the examples in the minority class. For example, if you have 90 red motorcars and 10 white automobiles. There are 90% more red cars than white cars if this data is applied to a model to predict a red or white car. The feedback of the model will be biased since there are more additional red cars in the data set. The synthetic minority oversampling technique can aid balance the class distribution but does not provide any additional information to the model. In the following example, SMOTE is applied then the data set will have fifty red and white autos. Now, the algorithm will not have biased feedback. Almost professional fields such as engineering, data analysis, actuaries, and others use SMOTEfor their models to get their best interest. </p>

#### How does train and test work and what is it doing to the data?

<p>Train data helps the model prediction and develops an algorithm of 70% or more of the data. Big data sets use the training method to get the best results. Testing helps the model to check the prediction rate by taking a small portion of the data and testing the model whether it works efficiently.  </p>

### Step 5

![Step 5](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5.png)

![Linear Regression Example](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5_part_1_example.png)

#### For knowledge review, what is Linear Regression? 
<p> Linear regression is used to model and predict a relationship. Predicts a dependent variable, given values from an independent variable. There are two basic types. The Simple linear regression and multiple linear regression. Both types predict an independent variable using the linear equation. </p>

<p>The basic linear regression has a dependent variable labeled as 'y', 'm' is the slope, 'x' is the independent variable, and 'b' is the y-intercept. The greek linear regression has a dependent variable labeled as 'y', 'B_1' is the slope, 'x' is the independent variable, and 'B_0' is the y-intercept. The multivariate linear regression has a dependent variable labeled as 'y', 'B_n' is the slope, 'x_n' is the independent variable, and 'B_0' is the y-intercept. </p>

![Linear Regression Example Formula](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5_part_1_example_2.png)

![Linear Regression Example Formula](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5_part_1_example_3.png)

![Linear Regression Example Formula](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5_part_1_example_4.png)

#### How does Logistic Regression work and what is it doing to the data?
<p>Logistic regression is a classification algorithm used to predict a discrete set of classes or categories. Unlike linear regression, which outputs continuous numerical values (for example, age), logistic regression applies an activation function, such as the sigmoid function, to return a probability value of 0 or 1. This can then be mapped to a discrete class like “Sad” or “Happy". Unlike linear regression, logistic regression has complex different formula. The formula is logit(p) = ln(p/(1-p)) = b_0 + b_1 * X_1 + b_2 * X_ 2 + b_3 * X_3… + b_k * X_k. The p equals the probability of the occurrence of the component, x_k is the set of input characteristics of x, and b_k is the parameter values to be calculated in the logistic regression instructions. The main formula in logistic regression is a equation from the Sigmoid function is given as y=1/(1+e^x), but can be written as y=1/(1+e^-(b_0 + b_1 * x). Keep in mind, that this is the simple logistic regression formula. </p>

![Step 5 Part 1](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5_part_1.png)

![Step 5 Part 2](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5_part_2.png)

#### How does RFE work and what is it doing to the data?

<p> Recursive Feature Elimination, or RFE for short. RFE helps select those columns in a training dataset to determine their relevance in predicting the target variable. It will print true or false as true tells the column is beneficial to the target as false is nonrelevant to the target. The next image is an example and the outcome of RFE in this model as you can see all of the columns are printed as true. This tells the model that all of the columns are beneficial to the target. </p>

![Step 5 Part 4,5, and 6](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_5_part_4_and_5_and_6.png)

### Step 6

![Step 6](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_6.png)

![Step 6 Part 1](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_6_part_1.png)

### Step 7

#### What is the ROC curve and what is it doing to the data?

<p>Receiver Operating Characteristic, or for short ROC curve. ROC curve is a useful tool when predicting the probability of a binary outcome. It plots the false alarm rate versus the hit rate. False-positive rate (x-axis) vs. the true positive rate (y-axis) for different candidates' threshold values between 0.0 and 1.0. The true positive rate is also known as sensitivity and the false-negative rate as specificity. Either in general or for different thresholds curves of different models can be directly compared. The area under the curve, referred to as AUC can be used as a summary of the model skill. The shape of the curve conveys useful information, such as the expected false positive rate, and the false-negative rate.  </p>

![Step 6](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/step_7.png)

<p> The outcome of the ROC curve is .98 for predicting the wine type as it represents the model is successful. Since the ROC curve is .98, the formula will predict if it is red or white with a two percent chance of an error. </p>

## Predict Wine Quality greater than or equal to 8

![Step 6](https://raw.githubusercontent.com/samuelroiz/Wine_Qlt/main/Images/Presentation/target_wine_quality_outcome.png)


