__AGRICULTURAL PRODUCTION OPTIMIZATION ENGINE__

### 1. _ABSTRACT:_

- As an agricultural country, India’s economy is predominantly depended over production of yield from agriculture.

- About half of the population of India depends on agriculture for its livelihood, but its contribution towards the GDP of India is
only 14 per cent. 

- The early methods used by farmers are not sufficient enough to full fill today’s requirement, thus new methods are invented which in return brings employment  for  people.
- Machine  learning  Technology  in  agriculture  has helped humans a lot such as identifying particular climate for particular crop similarly, it’s soil type, pH value and water supply to the crop.
- The project consists of implementing a new method for different crop at similar time for larger productivity by predicting it accurately.
- In this project we are Building a Predictive Model so as to suggest the most suitable crops to grow based on the available Climate and Soil conditions.


### _2.INTRODUCTION:_

- As we all know that agriculture depends largely on the nature of the soil and the climate condition and many a times,we face unpredictable changes in climate like, non seasonal rainfall or heat waves or fluctuation in humidity levels,ect and all such events cause a great loss
to our farmers and farming, because of which they are not able to utilize their agricultural land to it's fullest.



### _3. OBJECTIVES:_

1. To use machine learning technique to predict crop yield.
2. To provide easy to use user interface and optimize agricultural production.
3. To increase the accuracy of crop yield prediction.
4. To analyze different parameters for predicting a crop.

### _4. TOOLS USED:_
Python & Jupyter Notebook Libraries used: Numpy, Pandas, Seaborn, Matplotlib, ipywidgets and sklearn. Machine Learning Algorithms used: Clustering Analysis and Logistic Regression.

### _5.LITERATURE SURVEY:_

- The main aim of us is to build a user-friendly system based on soil parameters. We have done data pre-processing by data cleaning, data integration, data
transformation, data reduction. Data is taken from multiple resources. The five algorithms we have used are Support Vector Machine,
Bagged Tree, Naive Bayes, and Artificial Neural Network.

- The project proposes a model which can predict the crop based on the soil nutrient values (NPK values) and pH given as the input. The authors
discussed the main objective of this work was finding the desired data models that give high accuracy and high generality in terms
of the yield forecasting capabilities.

- In this the linear regression, decision tree regression, and K-Nearest Neighbors were used to forecast the crop yield per
acre. We have utilized diverse relapse strategies like straight relapse, choice tree relapse, K-closest Regression, Support vector
Regression.

- The proposed Crop Selection Method classified crops as seasonal crops, whole year crops, short time plantation crops, long time plantation crops.

- The datasets have been collected and refined based on commonality uses such as location, crop, Area, soil type, temperature, humidity etc.

- Crops based on multiple factors such as Nitrogen, Phosphorus and Potassium nutrients in soil and weather components which include temperature and rainfall is a new innovation
system to this existing world. The proposed system precisely predicts the advanced profitable crop to the farmer.

### _6.PROPOSED SYSTEM:_

- The system aims to help farmers to cultivate proper crop for better yield production. To be precise and accurate in predicting
crops, the project analyzes the nutrients present in the soil and the crop productivity based on location. 

### _7.FUTURE SCOPE:_

- The future work aimed at the analysis of the entire set of data and will be devoted to suitable strategies for improving the efficiency of the proposed algorithm. Use of such kind of approach to forecasting is not restricted
to agriculture alone. We can also consider economic aspect of farmer to recommend the farmer’s most
profitable crop.

### _8.OVERVIEW ON DATASET:_

-The dataset contains columns such as Nitrogen, Phosphorus, Potassium, Temperature, Humidity, Rainfall. The system predicts best crop considering above parameters.
8.1.2) KNN algorithm: Crop Prediction Module
1) Input: Nitrogen, Phosphorous, Potassium, Temperature, Humidity, Rainfall, PH value
2) Output: Crop name
3) Use Label Encoder to assign number to crop name.
4) Input Nitrogen, Phosphorous, Potassium, Temperature, Humidity, Rainfall, PH value.
5) Choose value of K and train the data.
6) Test the data.
7) Convert data entered by user in an array.
8) Use predict function to get results.
9) Convert numeric value associated with crop name to name of crop.
10) Print result

















