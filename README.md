# Campaign-for-Selling-Personal-Loans

# Dataset:

Here we have used 5000 customers bank data in csv format

dataset include following features

1. ID: Customer ID
2. Age: Customer's age in completed years
3. Experience: Number of years of professional experience
4. Income: Annual income of the customer 
5. ZIPCode: Home Address ZIP code.
6. Family: Family size of the customer
7. CCAvg: spending on credit cards per month 
8. Education: Education Level. 
      * 1: Undergrad 
      * 2: Graduate
      * 3: Advanced/Professional
9. Mortgage: Mortgage Value of house mortgage if any. 
10. PersonalLoan: Did this customer accept the personal loan offered in the last campaign?
11. SecuritiesAccount: Does the customer have a securities account with the bank?
12. CDAccount: Does the customer have a certificate of deposit (CD) account with the bank?
13. Online: Does the customer use internet banking facilities?
14. CreditCard: Does the customer uses a credit card issued by UniversalBank?

# Results of different algorithms
<table>
<tr>
<th>Model</th>
<th>Optimal Hyper Parameter</th>
<th>AUC</th>
<th>Testing Accuracy</th>
</tr>
<tr>
<td>Logistic Regression</td>
<td>0.0001</td>
<td>0.9295501718881753</td>
<td>91.92</td>
</tr>
<tr>
<td>Decision Tree</td>
<td>5</td>
<td>0.9640737497567621</td>
<td>98.24 </td>
</tr>
<tr>
<td>KNN Brute Force</td>
<td>63</td>
<td>0.9640737497567621</td>
<td>91.28</td>
</tr>
<tr>
<td>KNN KD tree</td>
<td>33</td>
<td>0.9640737497567621</td>
<td>91.44</td>
</tr>
<tr>
<td>Multi Nomial Bayes</td>
<td>1000</td>
<td>0.8045096322241682</td>
<td>79.92</td>
</tr>
<tr>
<td>Random Forest</td>
<td>500</td>
<td>0.9762680806901473</td>
<td>98.32</td>
</tr>
<tr>
<td>Support Vector Machine</td>
<td>1000</td>
<td>0.7744616332619835</td>
<td>91.52</td>
</tr>
<tr>
<td>Gradient Boosting</td>
<td>5</td>
<td>0.9810598689758059</td>
<td>98.16</td>
</tr>
</table>
