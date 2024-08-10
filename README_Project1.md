# **Team Project Part 1**
## Consumer Behavior and Shopping Habits

### Group#24 
#### Team Members 

- Shiraz Latif: [Shiraz Latif Video Presentation](https://youtu.be/b9ZE5oaf9DM)  
- Jessilynn Kim: [Jessilynn Kim Video Presentation](https://drive.google.com/file/d/154oUYqRxrjb2NYRciiltaPbO3xmOLw3g/view?usp=sharing)
- Mykhailo Vitvinov: [Mykhailo Vitvinov Video Presentation](https://youtu.be/Sj4QRFj9Vk8?si=8gOwglDGda79a35Y)
- Olena Bolokhonova: [Olena Bolokhonova Video Presentation](https://drive.google.com/file/d/1v07EtJ6vsUtRywuMMTopht9VIy6_oRRa/view?usp=drivesdk)

## Team's approach 
### Data Selection
After determining the sectors we had chosen for the team project (Retail/Commerce & Finance), we collectively explored various datasets in Retail/Commerce field in Kaggle.
The dataset used in this project can be found on Kaggle: [Customer Shopping Trends Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset).

### Analysis Focus
Each team member reviewed Consumer Behavior and Shopping Habits dataset separately by answering questions part of Team Project 1 Instruction to better understand the data and to set objective of the analysis. We formulated possible variables/relationships/hypothesis and updated excel tracker. 

### Roles and Responsibilities 
Taking everyone's strength, background and circumstances into consideration, everyone contributed to the group project to ensure successful completion. 
Shiraz setup overall framework for the project and reviewed codes as he has the most technical background. Olena dove into data and documentations of work to jumpstart the project.  Mykhailo continued the data analysis to round out the possibilities of meaningful data relationships. Jessilynn completed pre-analysis of the dataset and completed README file for the group with everyone's input. With everyone's input, we contributed as a group to provide insights and recommendations for the project. Additionally, we've leverage Rules of Engagement we've setup for the team to ensure successful completion of this project. 

### Data Analysis 
#### Description
This project aims to analyze consumer behavior and shopping habits using a wide range of variables such as age, gender, purchase amount, location, product category, and more. The primary objective is to explore the relationships between these variables to uncover meaningful insights that can inform business strategies on how to drive total purchase amount.

#### Key Variables and Attributes in the Dataset:
1.	Customer ID: Unique identifier for each customer.
2.	Age: Age of the customer.
3.	Gender: Gender of the customer.
4.	Item Purchased: Specific product purchased by the customer.
5.	Category: Broad classification of the purchased item (e.g., clothing, electronics).
6.	Purchase Amount (USD): Monetary value of the transaction.
7.	Location: Geographical location where the purchase was made.
8.	Size: Size specification of the purchased item (if applicable).
9.	Color: Color of the purchased item.
10.	Season: Seasonal relevance of the purchased item (e.g., spring, summer).
11.	Review Rating: Customer's satisfaction rating for the purchased item.
12.	Subscription Status: Whether the customer has a subscription service.
13.	Payment Method: Mode of payment used by the customer.
14.	Shipping Type: Method used to deliver the purchased item.
15.	Discount Applied: Indicates if any discounts were applied to the purchase.
16.	Promo Code Used: Notes if a promotional code was used during the transaction.
17.	Previous Purchases: Information on the number or frequency of prior purchases by the customer.
18.	Preferred Payment Method: Customer's preferred mode of payment.
19.	Frequency of Purchases: How often the customer makes purchases. 
    
#### Libraries and Tools Used

- **Data Manipulation:** `numpy`, `pandas`
- **Statistical Analysis:** `statsmodels`, `scipy`
- **Machine Learning:** `sklearn`
- **Data Visualization:** `matplotlib`, `seaborn`

#### Data Import and Preparation

The dataset was imported using `pandas`, and an initial inspection showed no missing values across the 19 columns, indicating a clean dataset.

![Cust_Shop_Trends_Dataframe](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Cust_Shop_Trends_Dataframe.png)


##### Specific Libraries or Frameworks Well-Suited to the Project Requirements:
1.	Pandas: For data manipulation and analysis.
2.	NumPy: For numerical computations.
3.	Matplotlib and Seaborn: For data visualization.
4.	SciPy: For statistical analysis and hypothesis testing.
5.	Statsmodels: For regression analysis and statistical modeling.
6.	Scikit-learn: For machine learning algorithms and clustering analysis.
7.	Jupyter Notebook: For interactive data analysis and visualization.

### Exploratory Data Analysis (EDA)

Several initial analyses were conducted to understand the data:

- **Gender and Purchase Amount:**
  - **Analysis Method:** Bar Plot, Linear Regression
  - **Question:** Do women spend more on shopping than men in a single transaction?
  - **Conclusion:** The analysis, using both bar plots and linear regression, showed no significant variance in the average purchase amount per transaction between genders. Both male and female customers spent similar amounts on average, indicating that gender may not be a strong differentiator in purchase behavior for this dataset.

- **Age and Purchase Amount:**
  - **Analysis Method:** Linear Regression
  - **Question:** Do older customers have higher average purchase amounts compared to younger customers?
  - **Conclusion:** Linear regression analysis revealed no significant relationship between age and purchase amount, indicating that age does not significantly influence spending.

- **Discounts and Purchase Amount:**
  - **Analysis Method:** Linear Regression
  - **Question:** Are purchases with applied discounts higher in overall spending?
  - **Conclusion:** Linear regression analysis found that the average purchase amounts with and without discounts were similar, suggesting that discounts do not significantly impact overall spending.

- **Previous Purchases and Purchase Amount:**
  - **Analysis Method:** Linear Regression
  - **Question:** Do customers with a higher number of previous purchases have higher average purchase amounts?
  - **Conclusion:** Linear regression analysis did not support the hypothesis that customers with more previous purchases spend more, indicating no significant relationship between purchase history and spending.

- **Exploring Customer Demographics and Purchasing Behavior:**
  - **Plot Types:** Bar Plot, `groupby` method
  - **Question:** How do customer demographics, specifically gender and location, influence purchasing behavior?
  - **Conclusion:** Bar plots and grouping methods were used to explore customer demographics. The analysis revealed that gender distribution showed no significant variance in purchase amounts, while location-based insights indicated that certain regions have higher concentrations of customers, which could inform region-specific promotional strategies.

- **Location Distribution:**
  - **Methods:** `counts`, Bar Plot
  - **Details:** The `counts` method and bar plots were employed to visualize the distribution of customers across different locations. This analysis showed that customers were concentrated in specific regions, such as Montana, California, and Texas.

- **Explore Location-Based Insights:**
  - **Methods:** `cust_data.groupby`, Plot
  - **Details:** The `groupby` method and plotting were used to explore location-based purchasing behavior. The analysis highlighted regions where customers tend to spend more on average, such as Alabama and Alaska, offering insights for targeted marketing strategies.

#### Key Insights and Recommendations:
The analysis conducted on the dataset revealed several key insights, but it also highlighted the limitations of the data in providing actionable distinctions across different demographic and behavioral segments. Specifically, there were no significant differences in purchase amounts based on gender, age, discount application, or previous purchase history. 

Additionally, while exploring customer demographics and location-based purchasing behavior, the data showed consistent patterns that did not vary significantly by gender or location.

As a result, we rejected all hypotheses due to lack of statistical significance supported by regression analyses. 

We shifted our focus to a classification model, aiming to predict a customer's subscription status based on their shopping habits.

#### Classification Model:
  - **Model Type:** K-Nearest Neighbors (KNN)
  - **Objective:** To predict whether a customer will subscribe based on their shopping habits.
  - **Results:** The model performed well, achieving an accuracy of 83%. This indicates that with a well-prepared dataset, such models can be powerful tools for predicting customer behavior and guiding marketing strategies.

## Conclusion
1. Our initial exploration of the dataset raised concerns about its authenticity, which led us to further investigate whether the data was real or generated.

2. Through deeper analysis, we identified several indicators suggesting that the dataset might be generated. Specifically, we found minimal significant differences in purchase amounts across various ages, genders, and seasons—patterns that would typically show more variability in real-world data. Additionally, the data was already cleaned and contained no missing values, which is unusual for real-world datasets. Moreover, the absence of any references to surveys, sampling methods, or other data collection processes further supported our suspicion that the dataset might not be genuine.

3. Although the dataset may not be suitable for marketing purposes as initially intended, our project effectively demonstrated methods that can be utilized in real-world scenarios to uncover important patterns or predict customer behavior. For instance, linear regressions and grouping techniques were useful for identifying potential relationships between variables, while bar charts provided clear visualizations during our exploratory analysis.

4. We also implemented a classification model, specifically using K-Nearest Neighbors (KNN), to predict whether a customer would subscribe based on their shopping habits. The model performed well, achieving an accuracy of 83%. This indicates that with a well-prepared dataset, such models can be powerful tools for predicting customer behavior and guiding marketing strategies.

## Rules of Engagement 

### Engagement Channel:
1. Zoom Breakout Room
2. Whatsapp Group
3. Slacks
4. Github
5. Emails
6. Google Meets

### Communication:
• Leveraging Whatsapp group for main communication
• Any delays in joining meeting, completion of task, or availabilities for meeting times are shared 

### Meeting Schedule:
1. Post live session breakout room 
    • Check in around 7:15 for about 15 mins
    • Check in around 9:00 for about 15 mins
2. Friday
    • During work period 
    • Evening around 6-7 pm 
3. Saturday -TBD

### Progress Tracking
Shared Excel Tracker
    • Documenting tasks and progress
    • Avoid possible duplication with visibility for everyone

### Conflict Resolution 
1. Voting
2. Respecting other's opinions
3. Listening
4. Actively communicating during meetings
5. Avoid assumptions and ask questions where clarity is required 


