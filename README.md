# Prediction_of_AmountPaid_with_ML
### Overview
This project aims to predict the total bill amount for customers in a cafe based on various factors such as the amount paid for the bill, type of payment, customer age, and any additional information that can be useful. The dataset used for this project is fake, as it contains sensitive information such as passwords, card numbers, CVV numbers, blood type, etc, and cannot be used as valid information. By leveraging machine learning techniques, we can provide fake cafe owners with accurate predictions, helping them better manage their resources and plan for staffing and inventory.
The original dataset can be downloaded by using this link https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P12-FakeNames.zip

### Requirements

To run this project, we'll need:

Python 3<br>
Required libraries listed as follows: <br> Pandas, <br>Numpy, <br>Matplotlib, <br>Keras, <br>Scikit Learn, <br>TensorFlow Decision Forest

Visual Studio<br>
SQL<br>
Excel<br>
Tableau<br>
notepad++<br>
Input Data on cafe transactions (included in this repository as "FakeNames_DRV_20240131_final") 

### Usage

FakeNames_20240131_ML.ipynb: This script contains the main functionality for loading the data, preprocessing it, training the machine learning model, and making predictions. This module also provides functions for cleaning and preprocessing the raw transaction data. Contains the machine learning model used for predicting the bill amount. This script evaluates the performance of the trained model using various metrics such as RMSE, MAE, etc.

### Data

The data used in this project should contain information about cafe transactions, including:

RowNumber-Index,<br>
Number-Identification Number, <br>
Gender-Male, <br>
Female gender group, NameSet-Nationality,<br>
Title-Mr.,Mrs.,Ms., <br>
GivenName-Client's name, <br>
MiddleInitial-Middle name initial, <br>
Surname-Client's surname, <br>
AmountPaid-Bill paid, <br>
StreetAddress-Home address, <br>
City-City of the location of the cafe, <br>
State-State of the location of the cafe: Initials, <br>
StateFull- State of the location of the cafe: full name of the state, <br>
ZipCode- Zipcode of the location of the cafe, <br>
Country-Country name: Initials, <br>
CountryFull- Country name: full, <br>
Feedback-Feedback left by clients for service provided, <br>
EmailAddress-Client's email address, <br>
Username-username of a client if the order was done on the webpage, <br>
Password-password for login, <br>
BrowserUserAgent-Browser used by the client, <br>
TelephoneNumber-Cell phone number, <br>
TelephoneCountryCode-Telephone country code, <br>
MothersMaiden-Mother's maiden name, <br>
Birthday-The date of the birthday of a client, <br>
TropicalZodiac-Zodiac sign of a client, <br>
CCType-Credit card type, <br>
CCNumber-Credit card number, <br>
CVV2-credit card cvv code, <br>
CCExpires-credit card expiration date, <br>
NationalID-National identification number, <br>
UPS-uninterruptible power supply, <br>
WesternUnionMTCN-Western Union Money Transfer Control Number, <br>
MoneyGramMTCN-MoneyGram Money Transfer Control Number, <br>
Color-color of credit card, <br>
Occupation-Client's occupation, <br>
Company-Client's workplace, <br>
Vehicle-Client's vehicle, <br>
Domain-Domain used by company, <br>
BloodType-Client's blood type, <br>
Pounds-Client's weight in pounds, <br>
Kilograms-Client's weight in kilograms, <br>
FeetInches-Client's height in inches, <br>
Centimeters-Client's height in centimeters, <br>
A GUID-globally unique identifier, <br>
Latitude-Latitude of location, <br>
Longitude-Longitude of location

### Future Improvements
Adding incorporate additional features such as income group, customer preferences, set of food ordered, etc., can improve the model

### Contributors
Chynara Bektursunova, linkedin profile: https://www.linkedin.com/in/chynara-bektursunova-8a5872188/
Ruslan Kurmanov, linkedin profile: https://www.linkedin.com/in/ruslan-kurmanov-4b9358146/
