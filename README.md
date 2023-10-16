# JP-Morgan: ML for option pricing and Heston calibration

# Description
In the first part of this project, our team introduce several machine learning model including Random
Forest, XGBoost, Cat Boost, Light GBM and ANN to generate option price. In doing so, we
have outlined our data generation process, the corresponding introductions of the different
machine learning models and compare their capability with respect to MAE. The result on
training set shows that The ANN model displays a superior predictive power for option pricing
when compared to other widely-used tree models. In the next part of the project, our team try to
calibrate the Heston model used to price the option price in the previous section , in this part we
also use ANN, Light GBM and XGBoost for the pricers of Heston parameters and compare the
MAE of different models. While we find that the calibrated heston parameters deviate greatly
from the initial value, so machine learning pricers may not good enough for the pricing. For
further studies, we will try to find the better model/feature for the calibration and test its
performance using the real-world market data.


# Contents

Jupyter Notebook:

This file contains all the codes which were created and used for this project/paper.

Final Presentation:

This is the presentation my team and I presented in the Practicum Competition organized by the Financial Engineering Department at UIUC.

