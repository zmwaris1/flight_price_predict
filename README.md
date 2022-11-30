# Flight Fare Prediction model
This is a machine learning the model for flight fare prediction for four metro cities of India.<br>

# Motivation
Getting an insight over the price of flight that one may take in the future is a good way to plan accordingly so one does not end up paying more than they need to. This application is to serve the same purpose. It uses dataset from kaggle which contains different airline prices on the basis of different variables like source, destination, number of stops etc. This ML App was trained using those features using various regressions models and finally RandomForest regressor was chosen as the final model with highest R2 score of .81. After training the model it was integrated with Flask framework and made a frontend using Jinja for a btter user experience. As processed with the model the app is able to predict accurately.

# Tools
This code is written in Google Colab. It has all the libraries required in doing machine learning projects. And the best part is it does not use up your system memory but works on virtual servers. And it is free if you are using it only for yourself.

# Tools Used
<img src="https://github.com/zmwaris1/logos/blob/main/png-clipart-scikit-learn-python-scikit-logo-brand-learning-text-computer.png" alt="sickit-learn" height="40" style="vertical-align:top; margin:4px"><img src="https://github.com/zmwaris1/logos/blob/main/tutorial_matplotlib.png" alt="matplotlib" height="40" style="vertical-align:top; margin:4px">
<img src="https://github.com/zmwaris1/logos/blob/main/Pandas_logo.svg.png" alt="Pandas" height="40" style="vertical-align:top; margin:4px">
<img src="https://github.com/zmwaris1/logos/blob/main/105040771-43887300-5a88-11eb-9f01-bee100b9ef22.png" alt="Numpy" height="40" style="vertical-align:top; margin:4px">

## Demo video
https://user-images.githubusercontent.com/99170634/203472570-8ea97eb2-8f2d-4932-8f59-56b5afa1fbf5.mp4

### Due to termination of Heroku free services the app won't load.

You can use this app using:<br>
`git clone https://github.com/zmwaris1/flight_price_predict.git`<br>
in your local system. Go the project directory open terminal and type **python app.py.**
