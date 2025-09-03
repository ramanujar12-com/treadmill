# Aerofit Treadmill Product Analysis



### **Project Overview**

This project analyzes the customer data of AeroFit, a leading fitness equipment brand, to understand the target audience for each of their three treadmill models: KP281, KP481, and KP781. By profiling the customers, the goal is to provide actionable recommendations for targeted marketing and business strategy.

***

### **Project Objective**

The main objective was to perform a comprehensive data analysis to identify the characteristics of the target audience for each of AeroFit's treadmill products. 
This analysis involved:

- Performing descriptive analytics to create a detailed customer profile for each product.
- Constructing contingency tables and computing probabilities to uncover relationships between customer characteristics and product choice.
- Providing actionable business insights and recommendations based on the findings.

***

### **Key Findings & Customer Profiles**

Our analysis of the dataset revealed distinct customer profiles for each treadmill model.

- **KP281:** The Entry-Level User
    - **Target Audience:** This model is popular among a younger, broader demographic, including both males and females.
    - **Characteristics:** Customers typically have lower incomes, with average planned usage of 2-3 times per week and self-rated fitness levels of 3. They are often beginners or                                   individuals with general wellness goals.
    - **Probability:** The KP281 is the most popular product, accounting for 44.4% of all purchases in the dataset.
- **KP481:** The Mid-Level User
    - **Target Audience:** Attracts a slightly older demographic than the KP281, with moderate incomes and a relatively even gender split.
    - **Characteristics:** Customers have moderate planned usage (around 3 times per week) and fitness levels of 3. They are generally individuals with some fitness experience looking                               for a step up from a basic model.
    - **Probability:** This model accounts for 33.3% of purchases.
- **KP781:** The Advanced User
    - **Target Audience:** Appeals to a highly engaged, fitness-focused demographic.
    - **Characteristics:** Customers are often older, highly educated, and have significantly higher incomes. They report high planned usage (4-5 times per week) and excellent fitness                               levels (rated 5). This group is predominantly male.
    - **Probability:** This is the least purchased model (22.2%), but it attracts a highly valuable, high-spending customer segment.

### **Recommendations:**

Based on the customer profiles, here are the strategic recommendations for AeroFit:

**Targeted Marketing Campaigns:**
     - **KP281:** Focus on affordability and ease of use. Use mass-marketing channels to reach a broad, younger audience.
     - **KP481:** Position this model as a value-added choice for those looking to progress in their fitness journey.
     - **KP781:** Promote this as a premium, high-performance product. Utilize specialized marketing channels to reach affluent, fitness-focused individuals, especially men.

**Sales Strategy:** Since partnered individuals are more likely to make a purchase, consider offering promotions or bundle deals for couples or families                                                       to boost sales across all product lines.

***

### **Technical Details**

- **Dataset:** Aerofit_treadmill.csv
- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scipy, statsmodels
- **Environment:** Google Colab
- **Repository Link:** `https://github.com/ramanujar12-com/treadmill`

***

### **How to Run the Project**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ramanujar12-com/yulu_project.git](https://github.com/ramanujar12-com/.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd treadmill
    ```
3.  **Open the Jupyter Notebook or Google Colab file (`.ipynb`):**
    - You can open it directly in Google Colab.
4.  **Install the required libraries** (if not already installed):
    ```bash
    pip install pandas numpy matplotlib seaborn scipy statsmodels
    ```
5.  **Run the notebook cells sequentially** to replicate the analysis and view the results.
