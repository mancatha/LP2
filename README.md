# LP2
Classification Project
# Introduction 
Customer attrition is one of the biggest expenditure of any organization. Customer churn, otherwise known as customer attrition or customer turnover, is the percentage of customers that stopped using your company's product or service within a specified period. 


## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| LP2  | Medium |  [https://medium.com/@benmanks2015/telecommunication-company-churn-analysis-classification-model-5acdd06b2e10](/) | [Best Article Machine learning](/) |
| LP2  | Power Bi|  [https://app.powerbi.com/links/BSY3mgTpUV?ctid=4487b52f-f118-4830-b49d-3c298cb71075 HYPERLINK "https://app.powerbi.com/links/BSY3mgTpUV?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkShare"& HYPERLINK "https://app.powerbi.com/links/BSY3mgTpUV?ctid=4487b52f-f118-4830-b49d-3c298cb71075&pbi_source=linkShare"pbi_source=linkShare](/) | [Interative Power BI](/) |

## Project Description
- In this project, we aim to find the likelihood of a customer leaving the organization, the key indicators of churn as well as the retention strategies that can be implemented to avert this problem.

### Univariate Analysis 

![Alt text](images/churn.png)

![Alt text](images/gender.png)

![Alt text](images/internet.png)

![Alt text](images/payment.png)

![Alt text](images/totalcharges.png)

### Multivariate Analysis 

![Alt text](images/mul.png)

## Hypothesis development 

✨ NULL: Contract type does not influence customer churn

✨ ALTERNATE: Contract type affects customer churn

based on chi-square test, we observe that the p-value is less than alpha, hence we reject Ho and conclude that is there is a statistical significance association between Churn and Contract.

## Business questions
1. How does gender impact customer churn? 

![Alt text](images/q1.png)

2. Does the presence of a partner or dependents influence customer churn? 

![Alt text](images/q2.png)

3. How does the length of tenure affect churn rates? 

![Alt text](images/q3.png)

4. What role do additional services (e.g., online security, tech support, streaming TV, etc.) play in reducing customer churn? 

![Alt text](images/q4.png)

5. Is there a correlation between the contract term (month-to-month, one year, two years) and churn rates? 

![Alt text](images/q5.png)

## Setup
1. **Clone the repository:**

   git clone https://github.com/your-username/Telco-Churn-Analysis.git

2. Navigate to the project directory:
    cd Telco-Churn-Analysis

3. Install required dependencies:
    pip install -r requirements.txt

4. Download the dataset:
    Download the Telco Churn dataset from the datasets folder and place it in the data directory. 

5. Run the analysis:
    Depending on your preferred IDE or notebook environment, open and run the provided Jupyter Notebook or Python scripts. 

6. Evaluate models:
    After training and tuning models, evaluate them using the evaluation dataset. You can use the provided evaluation script or notebook.

7. Export the best model:
    If desired, export the best trained model using the provided export script.

## App Execution
To use the exported best model for predictions:
1. Load the exported model:
In your Python script or notebook, load the saved model using pickle:
import pickle

with open('export/customer_churn_model.pkl', 'rb') as f:
    best_model = pickle.load(f)

2. Make predictions:
Use the loaded model to make predictions on new data:
new_data = ...  # Prepare your new data
predictions = best_model.predict(new_data)

## Appreciation
-   I highly recommend Azubi Africa for their comprehensive and effective programs. Read More articles about https://medium.com/@azubiafrica and take a few minutes to visit this link to learn more about Azubi Africa life-changing https://bit.ly/41CGCwK

-  **Tags**

https://bit.ly/3ARq742

## Author
`Benedicta Mankata`

`Data Analyst`

`Azubi Africa` 