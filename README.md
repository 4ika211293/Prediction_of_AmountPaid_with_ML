# Prediction_of_AmountPaid_with_ML
### Overview
This project aims to predict the total bill amount for customers in a cafe based on various factors such as the amount paid for the bill, type of payment, customers age, and any additional information that can be useful. By leveraging machine learning techniques, we can provide cafe owners with accurate predictions, helping them better manage their resources and plan for staffing and inventory.
The original dataset can be dowloaded by using this link https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P12-FakeNames.zip

### Requirements

To run this project, we'll need:

Python 3
Required libraries listed as follow: Pandas, Numpy, Matplotlib, Keras, Scikit Learn, TensorFlow Decision Forest
Visual Studio
SQL
Excel
Tableau
notepad++
Input Data on cafe transactions (included in this repository as "FakeNames_DRV_20240131_final") 

### Usage

FakeNames_20240131_ML.ipynb: This script contains the main functionality for loading the data, preprocessing it, training the machine learning model, and making predictions. This module also provides functions for cleaning and preprocessing the raw transaction data. Contains the machine learning model used for predicting the bill amount. This script evaluates the performance of the trained model using various metrics such as RMSE, MAE, etc.

### Data

The data used in this project should contain information about cafe transactions, including:

RowNumber-Index, Number-Identification Number, Gender-Male, Female gender group, NameSet-Nationality, Title-Mr., Mrs.,Ms., GivenName-Client's name, MiddleInitial-Middle name initial, Surname-Client's surname, AmountPaid-Bill paid, StreetAddress-Home address, City-City of location of cafe, State-State of location of cafe: Initials, StateFull- State of location of cafe: full name of the state, ZipCode- Zipcode of location of cafe, Country-Country name: Initials, CountryFull- Country name: full, Feedback-Feedback left be clients for service provided, EmailAddress-Client's email adddress, Username-username of a client if order was done on the webpage, Password-password for log in, BrowserUserAgent-Browser used by client, TelephoneNumber-Cell phone number, TelephoneCountryCode-Telephone country code, MothersMaiden-Mother's maiden name, Birthday-The date of birthday of a client, TropicalZodiac-Zodiac sign of a client, CCType-Credit card type, CCNumber-Credit card number, CVV2-credit card cvv code, CCExpires-credit card expiration date, NationalID-National identification number, UPS-uninterruptible power supply, WesternUnionMTCN-Western Union Money Transfer Control Number, MoneyGramMTCN-MoneyGram Money Transfer Control Number, Color-color of credit card, Occupation-Client's occupation, Company-Client's workplace, Vehicle-Client's vehicle, Domain-Domain used by company, BloodType-Client's blood type, Pounds-Client's weight in pounds, Kilograms-Client's weight in kilograms, FeetInches-Client's height in inches, Centimeters-Client's height in centimeters, GUID-globally unique identifier, Latitude-Latitude of location, Longitude-Longitude of location

### Future Improvements
Adding incorporate additional features such as income group, customer preferences, set of food ordered etc., can improve the model

### Contributors
Chynara Bektursunova, linkedin profile: https://www.linkedin.com/in/chynara-bektursunova-8a5872188/
Ruslan Kurmanov, linkedin profile: https://www.linkedin.com/in/ruslan-kurmanov-4b9358146/
