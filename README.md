# Telecom Customer Churn Attrition Prediction

![Screenshot 2024-09-15 101758](https://github.com/user-attachments/assets/b0b6dfaf-2cff-473d-a3e3-9c01c67e584b)


In today's competitive telecom industry, retaining customers is more important than ever. Customer churn, or when users leave for another provider, can significantly impact a company's bottom line. This project focuses on building a predictive model to help identify which customers are likely to leave based on their usage patterns, behavior, and other factors. By understanding these patterns, companies can act early to keep customers happy and reduce churn.

This repository includes everything needed to analyze customer churn, from the dataset to the code used for predictions. It also offers insights into key factors driving customer attrition and suggests strategies to help telecom companies improve customer retention. 

---

## Table of Contents
- [Problem Statement](#problem-statement)
- [Methodology](#methodology)
- [Data Insights](#data-insights)
- [Power BI Visuals](#power-bi-visuals)
- [Key Findings](#key-findings)
- [References](#references)
- [Usage Instructions](#usage-instructions)

---

## Problem Statement

In the dynamic landscape of the telecommunications industry, customers wield the power to choose from a plethora of service providers for their communication and internet needs. Customer satisfaction plays a pivotal role as users often form opinions about an entire company based on a single interaction. The ubiquitous nature of communication services, intertwined with our daily lives, underscores the significance of understanding and mitigating customer churn.

Churn rate, a key metric representing the number of customers who terminate or do not renew their subscriptions, directly impacts revenue. Given the high costs associated with acquiring new customers, an in-depth churn analysis is imperative. Insights derived from this analysis empower companies to formulate strategic approaches, target specific segments, enhance service quality, and ultimately foster trust with their customers. Building predictive models and generating comprehensive reports through churn analysis thus becomes instrumental in driving sustainable growth.

---

## Methodology

1. **Data Collection and Preparation:**
   - Curated a comprehensive dataset comprising customer demographics, service usage details, contract specifics, and billing preferences.
   - Employed rigorous data cleaning and preprocessing techniques to ensure data integrity and consistency.

2. **Exploratory Data Analysis (EDA):**
   - Conducted in-depth EDA to uncover hidden patterns, correlations, and anomalies within the dataset.
   - Visualized key metrics such as customer segmentation by contract type and churn propensity across different customer segments using tools like Power BI for interactive visualizations.

3. **Predictive Modeling:**
   - Developed and fine-tuned machine learning models including Logistic Regression, Random Forest, and Gradient Boosting.
   - Evaluated model performance based on metrics such as accuracy, precision, recall, and ROC-AUC score to select the optimal model for churn prediction.

4. **Power BI for Visual Insights:**
   - Implemented Power BI to create interactive dashboards and visualizations that provide intuitive insights into churn patterns.
   - Visualized model predictions, feature importance, and customer segmentation to facilitate strategic decision-making and operational planning.
---

## Data Insights


Explore profound insights and analytics gleaned from our extensive dataset. Uncover a deeper understanding of customer behaviors, patterns in service usage, and the pivotal factors that influence churn dynamics.


| Feature                                      | Visualization                                                                                       |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------|
| Categorical Features                         | ![Categorical Features](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/ce2e270e-2118-41b5-8207-1fccd2e98982)   |
| Churn Target Variable                        | ![Churn Target Variable](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/681e2805-d61e-4d56-be55-fa0495a5bfd5)  |
| Customer Information                         | ![Customer Information](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/234d902f-f514-4d2f-b28a-6d5813c67909)   |
| Distribution Analysis                        | ![Distribution Analysis](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/e72dbd50-9c94-4c44-bf89-1b3baa090a64)   |
| Mean Tenure                                  | ![Mean Tenure](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/0f8feb7e-d723-4061-beb6-62275d6a54b9)         |
| Churn Tenure Analysis                        | ![Screenshot](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/5942dbb4-47c7-467e-a075-14dc47ca7572)          |


---

## Power BI Visuals

Explore interactive Power BI visualizations designed to enhance data exploration and decision-making. Visualize customer churn trends, contract preferences, and revenue impact through intuitive and actionable dashboards.

| Overview and Key Metrics | Attrition Insights |
|---------------|-------------|
| ![Overview](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/18855f1b-fefe-4317-bede-fb8219d67e9f) | ![detailed_insights](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction/assets/143819712/7c068b03-4cdb-4659-b3e3-c15dc481cd59) |
| Gain a high-level view of customer churn trends, contract preferences, and revenue impact. This interactive dashboard provides insights into overall churn metrics and key business indicators. | Explore detailed analytics on customer segments, service usage patterns, and churn predictors. This visualization offers a deeper dive into specific data points and trends influencing churn decisions. |



---

## Key Findings

### Strategic Insights

- **Customer Segmentation:** Identify high-risk customer segments prone to churn.
- **Service Optimization:** Evaluate the impact of service features and contract terms on customer retention.
- **Financial Impact:** Quantify revenue loss due to churn and explore strategies for revenue recovery.


---

## References

- [Average Customer Acquisition Cost by Industry](https://hockeystack.com/blog/average-customer-acquisition-cost-by-industry/)
- [Subscriber Acquisition Cost Examples](https://www.klipfolio.com/resources/kpi-examples/call-center/subscriber-acquisition-cost)
- [Understanding Customer Churn Rate](https://www.zendesk.com/in/blog/customer-churn-rate/#georedirect)
- [Churn Prevention Strategies](https://www.profitwell.com/customer-churn/churn-prevention)

---

## Usage Instructions

### Getting Started

- **Clone the Repository**

  ```` 
   git clone https://github.com/adityakapole/Telecom-Customer-Churn-Prediction.git
   cd Telecom-Customer-Churn-Prediction
   ````

- Install the project dependencies by running the following command

   ```
   pip install -r requirements.txt
   ```

- Navigate through the project's directories and files to get acquainted with its structure.


- **Dataset Handling:**

   - Load the dataset using Python, R, or your preferred data analysis tool.
   - Explore and preprocess data to prepare for churn prediction modeling.

- **Model Development:**

   - Train and evaluate machine learning models to predict customer churn.
   - Fine-tune models based on performance metrics to optimize predictions.

---

## Running the Project

- **Start the Application:** Execute the following command to run the project.

   ```bash
   python app.py
   ```

**After you have successfully installed and launched the project, you can utilize it to forecast customer churn. Follow these steps to begin:**

- **Access the Web Interface:** Open your web browser and navigate to:

   ```
   http://127.0.0.1:5000/
   ```

**Upon accessing the interface, you'll encounter a user-friendly web application. Take time to familiarize yourself with its features and explore the various options available for predicting outcomes.**


| Details | Prediction |
|---------|---------|
| ![Image 1](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction-ML-PowerBI/assets/143819712/9666462b-b639-4ba4-8739-ad43b9ae80f5) | ![Image 2](https://github.com/virajbhutada/Telecom-Customer-Churn-Prediction-ML-PowerBI/assets/143819712/25373380-8e11-4b4e-9673-651b0dd90f90) |



- **Input Customer Data:** Refer to the on-screen instructions for guidance on entering customer data into the system. Once entered, explore the prediction feature to forecast churn outcomes based on the data provided.
  
- **Analyze Results:** Review the prediction outcomes to gather insights and formulate strategies, such as designing targeted promotions, and effectively applying the project to specific scenarios, such as implementing enticing customer offers.
  
---

Experience the deployed [version](https://coral-maurita-35.tiiny.site) of the Telecom Churn Prediction project!


### Dataset Usage:

1. Load the dataset using your preferred programming environment (e.g., Python with Pandas).
2. Explore and analyze the dataset attributes and patterns.
3. Utilize the dataset for Telco Customer Churn Classification analysis.

Feel free to adapt the above steps based on your specific use case and programming environment.

---
##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Conclusion
By leveraging comprehensive churn analysis, robust predictive models, and interactive Power BI visualizations, the telecommunications company can proactively identify at-risk customers, understand churn drivers, and enhance service offerings. This approach fosters customer retention, reduces acquisition costs, and supports sustainable growth. Ultimately, the integration of predictive insights into strategic decision-making enables companies to maintain a competitive edge in a dynamic industry.
