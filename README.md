# Intern-Coding-Assignment
The coding assignment is designed for both data science and backend interns
- if you are interested in backend, please submit the problem statement 2
- if you are interested in data science, then submit both (we require data science folks to have knowledge of backend and data science to be effective in the role)

# Programming Language
- Please use python if you are applying for data science role
- If you are applying to backend role, then please check with your interviewer about the language that should be used. It is either Python or Java.

# Problem Statement 1:
You have been provided with a dataset containing information about housing prices in a particular city. The dataset includes features such as the number of bedrooms, square footage, location, and sale prices of houses. Your task is to build a regression model that can predict the sale price of a house based on the given features.

# Dataset:
The dataset is provided in a CSV file called "housing_data.csv" in the code repository. It contains the following columns:

Bedrooms: Number of bedrooms in the house
Bathrooms: Number of bathrooms in the house
SquareFootage: Total square footage of the house
Location: Categorical variable representing the neighborhood of the house
SalePrice: Sale price of the house in dollars
Your task:

- Load the dataset from the CSV file and perform any necessary data preprocessing steps.
- Split the data into training and testing sets - first 50 is the training data and remaining is test data
- Build a regression model using any machine learning algorithm of your choice.
- Train the model using the training data.
- Evaluate the performance of the model using appropriate evaluation metrics.
- Use the trained model to make predictions on the testing data.
- Calculate the root mean squared error (RMSE) between the predicted prices and the actual prices.
- Save the trained model to a file for future use.


Note: Feel free to use any libraries or packages you are comfortable with for data preprocessing, model building, and evaluation.

# Problem Statement 2:
You have been provided same data as above in JSON format in a file called "housing_data.json"

- You have to build a REST API that will take the json data as input and store in postgres database
- Write an API that will give following output when called
  - Average sale price of the house overall
  - Average sale price of the house per location
  - Max sale price
  - Min sale price
- All the above output has to be generated using SQL Queries vs calculations in python code

Note:
- Bonus points for handling error cases in the rest APIs
- Bonus points for good json format based response and using right HTTP response codes


# Submission:
Please submit your code as a git repository. Also, include the saved model file.
- Include the instructions to run the python program
