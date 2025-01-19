![image](https://github.com/user-attachments/assets/01b37c52-e189-41f8-879d-fb267a370cfe)### Telecom Customer Churn Analysis

---

#### **Project Overview**
This project focuses on analyzing customer churn in the telecom industry. The goal is to identify key factors influencing churn and to provide actionable insights for improving customer retention. The analysis leverages demographic, service usage, and account data, with a particular focus on payment methods, contract types, tenure, and other contributing factors.

---

#### **Objective**
The primary objective of this project is to explore customer churn patterns and determine:
- Factors strongly associated with customer churn.
- Key strategies to improve retention and reduce churn rates.

---

#### **Key Insights**
1. **Contract Type and Churn**  
   - Customers on **month-to-month contracts** exhibit the highest churn rate (42%), compared to **yearly contracts (11%)** and **two-year contracts (3%)**.  
   - **Recommendation:** Promote long-term contracts by offering incentives to encourage customers to shift from month-to-month plans.
   - ![image](https://github.com/user-attachments/assets/196c0867-c765-482c-87df-53c9832ab167)

2. **Payment Methods and Churn**  
   - Customers using **electronic checks** have the highest churn rate (45%), compared to **credit cards**, **bank transfers**, or **mailed checks** (15-18%).  
   - **Recommendation:** Encourage customers to switch from electronic checks to more reliable and secure payment methods.
   - ![image](https://github.com/user-attachments/assets/ddd85070-42c8-423a-af01-979371f2aa24)

3. **Churn by Tenure**  
   - Customers with **tenure less than one year** have a 50% churn rate, decreasing to 15% after three years.  
   - **Recommendation:** Focus on engaging customers early, especially within the first year, to improve retention.

4. **Internet Service Type**  
   - Customers with **Fiber Optic services** have a churn rate of 30%, compared to **DSL services (20%)**.  
   - **Recommendation:** Investigate potential dissatisfaction with fiber optic services, such as speed or reliability, and address customer concerns.

5. **Senior Citizens and Churn**  
   - Senior citizens (aged 65+) have a **41% churn rate**, higher than non-senior citizens (26%).  
   - **Recommendation:** Implement special programs or personalized assistance for senior customers to improve their satisfaction and retention.
   ![image](https://github.com/user-attachments/assets/31530dac-5af1-4825-aa7d-91abda5da38d)
   ![image](https://github.com/user-attachments/assets/da25a521-06dc-4c0a-81cc-13fe3669c2bc)

---

#### **Visualizations**
- **Bar Charts and Line Graphs:**  
   - Churn by **contract type**, **payment method**, **tenure**, and **internet service type** is visualized to highlight trends and disparities.  
   - The analysis reveals that longer tenure and more secure payment methods decrease churn.

- **Percentage Distributions:**  
   - Payment Methods: 45% churn for electronic check users, 15% for credit card users.  
   - Contract Types: 42% churn for month-to-month contracts, 11% for yearly contracts, and 3% for two-year contracts.  
   - Tenure: 50% churn in the first year, dropping to 15% after three years.

![image](https://github.com/user-attachments/assets/54481624-4472-48f8-8578-510b61fb97fc)

---

#### **Recommendations**
1. **Promote Long-Term Contracts:**  
   - Offer discounts or loyalty rewards to encourage customers to switch to one-year or two-year contracts.

2. **Address Payment Method Concerns:**  
   - Create campaigns to educate customers on the benefits of switching from electronic checks to secure payment methods like credit cards or bank transfers.

3. **Focus on Early Customer Engagement:**  
   - Enhance customer experience and satisfaction during the critical first year of service with tailored offers or support.

4. **Special Programs for Senior Citizens:**  
   - Provide personalized assistance, discounts, or senior-friendly services to reduce churn in the senior demographic.

5. **Improve Fiber Optic Service Satisfaction:**  
   - Conduct surveys or feedback sessions to address issues with fiber optic services, such as reliability or speed.

---

#### **Project Files**
- **`Telecom-Customer-Churn-Analysis/Customer Churn(Raw Data)`**: Contains the dataset used for the analysis.
- **`Telecom-Customer-Churn-Analysis/Python based analysis`**: Jupyter notebooks with data preprocessing, analysis, and visualization code.
- **`Telecom-Customer-Churn-Analysis/Customer Churn Analysis Report`**: Exported reports based on the data visualization and extracted insights.
- **`README.md`**: Overview and summary of the project (this file).

---

#### **Future Enhancements**
- Implement machine learning models to predict customer churn and identify high-risk customers.
- Explore additional demographic and behavioral factors influencing churn.
- Design and evaluate retention strategies based on customer segmentation.

---

#### **How to Use**
1. Clone the repository:  
   ```bash
   git clone https://github.com/username/telecom-customer-churn.git
   ```
2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the analysis notebook:  
   ```bash
   jupyter notebook notebooks/customer_churn_analysis.ipynb
   ```
4. Explore the visualizations and insights in the `charts/` folder.

---

#### **License**
This project is licensed under the MIT License. Feel free to use and adapt the analysis for your needs.
