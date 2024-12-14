# CookingOrderAnalytics
This project analyzes user behavior, cooking preferences, and order trends by merging and exploring datasets on user demographics, cooking sessions, and order details. The insights aim to uncover key patterns and offer business recommendations.
Here’s a sample **README.md** file based on the information you've provided. It includes the points you mentioned, focusing on business recommendations and providing clear instructions on how to navigate the project:

---

# **Data Analytics for User Behavior, Cooking Preferences, and Order Trends**

## **Objective**
This project aims to analyze and uncover insights from datasets related to **user behavior**, **cooking preferences**, and **order trends**. By examining three key datasets—**UserDetails**, **CookingSessions**, and **OrderDetails**—we explore the relationships between user activity, cooking sessions, and orders. Based on the analysis, actionable business recommendations have been made to help optimize marketing strategies and improve user engagement.

## **Data Sources**
The project analyzes the following datasets:
- **UserDetails**: Contains demographic data about users, including age, gender, and location.
- **CookingSessions**: Captures user cooking sessions, including dish names and session dates.
- **OrderDetails**: Tracks user orders, including order value, dishes ordered, and the date of the order.

## **Methodology**
### **Data Cleaning**
- Removed duplicates and handled missing values to ensure clean, accurate datasets.
- Standardized data formats, such as user IDs and date formats.

### **Data Merging**
- Merged the three datasets using the `user_id` field as the primary key to create a comprehensive view of user activities.

### **Analysis**
- **Relationship between Cooking and Ordering**: Analyzed the correlation between the number of cooking sessions and order frequency.
- **Popular Dishes**: Identified the top dishes that are both commonly cooked and ordered.
- **Demographic Insights**: Explored how age, gender, and location influence cooking habits and order behavior.

### **Key Insights**
- **User Engagement**: Users who cook more often tend to place more orders. 
- **Popular Dishes**: Dishes like **Spaghetti Carbonara** and **Chicken Alfredo** are popular among users both in cooking sessions and orders.
- **Demographic Behavior**: Users aged 25-34 are the most active, while urban users place more orders than those in rural areas.

## **Business Recommendations**
### **4.1. Popular Dishes Should Be Marketed**
- **Market dishes like Spaghetti Carbonara and Chicken Alfredo** through specialized marketing campaigns.
- Creating **special bundles** with these popular items will create **upsell opportunities**. For example, offer discounts on beverages or desserts when customers order the popular dishes.

### **4.2. Reward Frequent Cooking**
- Introduce **loyalty programs** for users who frequently participate in cooking sessions. This could include **discounts on orders** based on the number of cooking sessions completed.
- **Incentivizing frequent cooks** will increase user engagement and foster a sense of reward, which can also drive more orders.

## **Files in This Repository**
- **Raw Data Files**:
  - `UserDetails.csv`
  - `CookingSessions.csv`
  - `OrderDetails.csv`
- **Merged Data**:
  - `MergedData.csv`
- **Analysis Scripts**:
  - `data_analysis.ipynb` or `data_analysis.xlsx`
- **Visualization Files**:
  - `popular_dishes_chart.png`
- **Final Report**:
  - `Final_Report.pdf` (contains detailed analysis and findings)

## **Tools Used**
- **Google Sheets/Excel**: Data cleaning, merging, and basic analysis.
- **Python (Optional)**: Used for advanced analysis, including visualizations using libraries like `pandas`, `matplotlib`, and `seaborn`.
- **GitHub**: Version control and collaboration platform.

## **How to Reproduce**
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Load the datasets into your analysis tool (Excel, Python, etc.).
3. Follow the steps in the **data_analysis.ipynb** or **data_analysis.xlsx** file to reproduce the analysis.

## **Contributors**
- **Harsha Vardhan - Data Analyst
