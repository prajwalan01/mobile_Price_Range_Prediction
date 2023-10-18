# mobile_Price_Range_Prediction

# ABSTRACT

During the purchase of mobile phones, various features like memory, display, battery, camera, etc., are considered. People fail to make correct decisions, due to the non-availability of necessary resources to cross-validate the price. To address this issue, a machine learning model is developed using the data related to the key features of the mobile phone. The developed model is then used to predict the price range of the new mobile phone. Three machine learning algorithms namely Support Vector Machine (SVM), Random Forest Classifier (RFC), Logistic Regression are used to train the model and predict the output as low, medium, high, or very high. The dataset used in this study is taken from Kaggle platform. In order to improve the classification accuracy, Chi-Squared based feature selection method is used. Among 21 features available in the dataset, only top 10 features namely RAM, pixel height, battery power, pixel width, mobile weight, internal memory, screen width, talk time, front camera and screen height are selected and used to train the model. Before applying feature selection, the accuracy obtained using SVM, RFC and Logistic Regression is 95%, 83% and 76% respectively. After feature selection, the accuracy of SVM, RFC and Logistic Regression improved to 97%, 87% and 81% respectively. From the experiments conducted, it is found that SVM gave superior performance when compared to other two classifiers.

Mobile phones come in all sorts of prices, features, specifications, and all. Price estimation and prediction is an important part of consumer strategy. Deciding on the correct price of a product is very important for the market success of a product. A new product that has to be launched, must have the correct price so that consumers find it appropriate to buy the product.

The Problem The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.

# Attribute Information:

Battery_power - Total energy a battery can store in one time measured in mAh Blue - Has bluetooth or not Clock_speed - speed at which microprocessor executes instructions Dual_sim - Has dual sim support or not Fc - Front Camera mega pixels Four_g - Has 4G or not Int_memory - Internal Memory in Gigabytes M_dep - Mobile Depth in cm Mobile_wt - Weight of mobile phone N_cores - Number of cores of processor Pc - Primary Camera mega pixels Px_height - Pixel Resolution Height Px_width - Pixel Resolution Width Ram - Random Access Memory in Mega Bytes Sc_h - Screen Height of mobile in cm Sc_w - Screen Width of mobile in cm Talk_time - longest time that a single battery charge will last when you are Three_g - Has 3G or not Touch_screen - Has touch screen or not Wifi - Has wifi or not Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost). Thus our target variable has 4 categories so basically it is a Multiclass classification problem.

# Conclusion

In this article, we looked at classification. Classifiers represent the intersection of advanced machine theory and practical application. These algorithms are more than just a sorting mechanism for organising unlabeled data instances into distinct groupings. Classifiers include a unique set of dynamic rules that include an interpretation mechanism for dealing with ambiguous or unknown values, all of which are suited to the kind of inputs being analysed. Most classifiers also utilise probability estimates, which enable end-users to adjust data categorization using utility functions.

From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar.

half the devices have Bluetooth, and half don’t.

there is a gradual increase in battery as the price range increases

Ram has continuous increase with price range while moving from Low cost to Very high cost.

costly phones are lighter.

RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.

form all the above experiments we can conclude that XGboosting and linear regression with using hyperparameters we got the best results
