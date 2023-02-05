# Jamie Walsh - Data Projects Portfolio


# [Project 1 - Car Pricing Modelling](https://github.com/j-ma-walsh/car_pricing_model)
### Creating a product which predicts the price of second-hand Nissan cars 

- Data from autotrader.co.uk was scraped for 6 different models of Nissan cars.
- Data was collated into a single dataframe and cleaned during exploratory analysis.
- Data for cars made between 2007 - 2020 was analysed.
- Correlations between columns of data were further explored.
- Linear Regression was selected as a suitable model for price prediction.
- Feature engineering was conducted in preparation for modelling.
- Linear regression modelling was performed using the statsmodels library.
- Final product was created as a function taking in user inputted information about a car to be sold. 
- The product output is an estimate of how much a car buying servie may pay for the car.
- The final RMSE for the model was £1781.

### Model Predicted Price against Real Price for Training Data
![](https://github.com/j-ma-walsh/car_pricing_model/blob/main/predicted_v_real_price.png)


# [Project 2 - Customer Churn Model](https://github.com/j-ma-walsh/customer_churn_model)
### Model to predict probability of customer churn

- Using the kaggle customer churn dataset (https://www.kaggle.com/datasets/blastchar/telco-customer-churn).
- Data was explored, cleaned and analysed.
- Descision tree, random forest and logistic regression models were run.
- Model test parameters were compared and a best model was selected.
- Using the selected model, churn probability for each customer was generated. 
- A top 500 customers most likely to churn list was exported.


# [Project 3 - Question Answer Usefulness Model](https://github.com/j-ma-walsh/QA_helpfulness_model)
#### Function to determine if an answer to a question is useful created using amazon product question answer data

- Amazon question/answer pair data was obtained.
- Natural language processing methods were applied to the text data to prepare it.
- Question and Answers were inspected to determine a number of factors which may dictate the degree of usefulness of an answer to a question.
- Code analysing data for each contributing factor was writen.
- The importance of each factor was varied using score weightings.
- The code was compiled into a final function which gives an overall usefulness score for a user inputted question and answer pair 


# [Project 4 - Patent Analysis Project](https://github.com/j-ma-walsh/patent_analysis_project)

- Google Patents dataset queries using Google Big Query utilising SQL through kaggle notebook 
- a sample was restricted to 1 million patent applications.
- data was restricted to one application per patent family (one datapoint for each inventive concept). 
- Data was taken from appicaitons between 2017 and 2021.
- The patent application data was cleaned, explored and analysed.
- Analysis was broken down into patents by territory, by applicant and by techology sector. 
- Visualisations were created using tableau.
- Aim of the project was to tell a story about the modern technology landscape using patent application data. 

### Top Corporations Globally by Patent Applications filed (from sample of 1m applicaitons from 2017-2021)
![alt text](https://github.com/j-ma-walsh/patent_analysis_project/blob/main/Tree%20Map%20of%20top%2050%20Corps%20-%20Labelled.png)

