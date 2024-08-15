## Team Project Part 2
### Consumer Behavior and Shopping Habits

### Group 24 
#### Team Members 

- Shiraz Latif: 
- Jessilynn Kim: [Jessilynn Kim Video Presentation](https://drive.google.com/file/d/16JKt7eNzkZ4f2KJKzUVe3NXJt1AjNvd-/view?usp=drive_link)
- Mykhailo Vitvinov: [Mykhailo Vitvinov Video Presentation](https://youtu.be/iCLoVATeNbM)
- Olena Bolokhonova: [Olena Bolokhonova Video Presentation](https://drive.google.com/file/d/16x3i4J19JZwW5B_Aid46RUqg7wWY4rh-/view?usp=drivesdk)

### 1. Overview of Findings from Part 1

In Part 1 of our project, we set out to analyze a dataset of customer shopping habits with the goal of uncovering patterns that could inform marketing strategies. The dataset included variables such as age, gender, purchase amounts, seasons, and more. Our initial aim was to use this data to explore how different demographic factors influence shopping behavior.

However, as we began our analysis, we encountered several red flags that raised concerns about the authenticity of the dataset. Specifically, we observed minimal significant differences in purchase amounts across various demographic segments like age, gender, discount applied, previous purchases. These results were unexpected, as real-world data typically shows more variability in these areas. 

Additionally, the dataset was already cleaned and contained no missing values—an unusual characteristic for real-world datasets, which often require substantial cleaning. The absence of references to surveys, sampling methods, or any clear data collection process further suggested that the dataset might be generated rather than real.

Despite these limitations, we proceeded with the analysis to demonstrate how certain methods could be applied to real-world data projects.

We used several techniques that are valuable in analyzing customer behavior, including:

- **Linear Regression** to identify potential relationships between variables like age, gender, discount applied, previous purchase and purchase amounts.
- **Grouping Techniques** to segment data and analyze patterns within these groups.
- **Bar Charts** to provide clear visualizations of the data, making it easier to interpret results.
- **Classification Model (K-Nearest Neighbors - KNN)** to predict whether a customer would subscribe based on their shopping habits. The model performed well with an accuracy of 83%, demonstrating the potential of such models when applied to well-prepared datasets.

In summary, while the dataset's authenticity limited its use for drawing real marketing insights, the methods we applied are directly transferable to real-world scenarios. These techniques are essential for analyzing customer data, uncovering trends, and guiding strategic decisions in the retail sector.

### Data Visualization Guide 
#### 2. Main Goals and Objectives of Visualization (What are the main goals and objectives of our visualization project?)
Given that the data we were working with  lacks the complexity and variability found in real-world datasets, we realized that this dataset does not lend itself well to improvements through code changes typically applied in the "Scaling to Production" module. 

While the dataset's quality may limit our ability to showcase advancements in scaling or sampling methodologies, it provides a valuable context for applying advanced visualization techniques. By refining our visualizations, we can still extract meaningful insights from the data and communicate these effectively, emphasizing the importance of clear, accessible data presentation in real-world scenarios.
#### 2.1. Revise Existing Plots
The first objective of Part 2 is to review and refine the existing plots created during Part 1. The goal is to ensure that these visualizations are accessible, readable, and accurate. This involves enhancing the clarity of charts, particularly those showing distribution patterns and other key insights. We aim to make these visualizations more informative and easier to interpret, thus improving the overall quality of the data presentation.

#### 2.2. Explore Real Datasets
To further validate our findings, we aim to explore and identify a real dataset with similar variables to those in our current dataset. By comparing the results from the generated dataset with a real-world dataset, we can better understand the reliability of our initial findings. This comparison will also provide a benchmark against which the generated data can be evaluated, highlighting any significant differences or similarities in data patterns.

#### 2.3. Comparative Visualization
Once a real dataset is identified and analyzed, the next step is to compare the visualizations from our project with those derived from the real dataset. This comparative analysis will involve side-by-side comparisons of key visualizations such as distribution charts. The goal is to assess how closely the generated dataset mirrors real-world data and to identify any discrepancies that may arise in visual patterns.

#### 2.4. Add New Visualizations Using Effective Tools for Retail Sector
In this final objective, we will propose various effective tools that can be utilized in the retail sector to uncover important patterns and trends. We will explore the use of advanced visualization tools such as Power BI and Tableau, as well as Python libraries like Matplotlib, Plotly Express and Seaborn. By demonstrating how these tools can be applied to real datasets, we aim to provide actionable insights that can drive business decisions and improve marketing strategies within the retail industry.

#### Roles and Responsibilities 
- **2.1. Revise Existing Plots** - Mykhailo Vitvinov
- **2.2. Explore Real Datasets** - Shiraz Latif, Olena Bolokhonova
- **2.3. Comparative Visualization** - Olena Bolokhonova
- **2.4.  Add New Visualizations Using Effective Tools for Retail Sector** - Jessilynn Kim (Power BI), Shiraz Latif (Tableu), Olena Bolokhonova (Python libraries) 

#### 3.Tailoring Visualization for Effective Communication (How can we tailor the visualization to effectively communicate with our audience?)
To effectively communicate insights from our retail dataset, we are tailoring visualizations to emphasize key patterns such as location distributions and demographic-based purchase behavior. By using bar charts and line graphs, we are clearly illustrating differences in sales across locations and demographics, making the data more accessible and relevant for decision-makers. This approach ensures that the visualizations are focused on actionable insights that align with the audience's needs.

#### 4.Type of Visualization Selection (What type of visualization best suits our data and objectives (e.g., bar chart, scatter plot, heatmap)?)
For our retail dataset, we select a combination of visualizations to best suit our objectives. In Power BI, we use bar charts combined with line graphs to effectively showcase the relationship between total purchases and previous purchases, with a focus on visualizing variances over time. Additionally, in Python, we utilize line graphs and bar charts to further analyze and present demographic-based purchase behavior and location distributions. These visualizations are chosen for their ability to clearly convey key patterns and trends within the data, making the insights accessible and actionable.

#### 5.Libraries and/or Frameworks Selection (Are there any specific libraries or frameworks that are well-suited to our project requirements?)
In Python, we use Matplotlib, Plotly Express, and Seaborn to create detailed line graphs and bar charts, helping us explore and present key insights. Pandas is essential for data manipulation and analysis. Additionally, we employ Power BI to create interactive dashboards that allow for dynamic exploration of the data, making it easier to communicate findings to stakeholders.

#### 6.Addressing Feedback and Iterative Improvements (How can we iterate on our design to address feedback and make iterative improvements?)
To iterate on our design and address feedback, we plan to share our visualizations with friends and peers to gather their insights. By collecting their feedback, we can identify areas for improvement, such as clarity, accessibility, and overall effectiveness. We will then make iterative changes to refine the visualizations, ensuring they better meet the needs of our audience. This collaborative approach allows us to continuously enhance our designs based on real-world input.

#### 7.Ensuring Inclusivity and Diversity in Visualization (What best practices can we follow to promote inclusivity and diversity in our visualization design?)
To promote inclusivity and diversity in our visualization design, we follow these best practices:

7.1. **Use Accessible Color Palettes:** We choose colorblind-friendly palettes and avoid relying solely on color to convey information, ensuring that our visuals are accessible to all viewers.
   
7.2. **Clear and Simple Language:** We use straightforward language in labels, titles, and descriptions to make our visualizations easily understandable by a diverse audience, including those with varying levels of data literacy.

7.3. **Interactive Features:** Where possible, we incorporate interactive elements that allow users to explore the data in ways that are meaningful to them, accommodating a range of perspectives and needs.

#### 8. Ensuring Data Visualization Representation Accuracy (How can we ensure that our visualization accurately represents the underlying data without misleading or misinterpreting information?)
To ensure our visualizations accurately represent the underlying data without misleading or misinterpreting information, we follow these best practices:

8.1. **Maintain Proper Scaling:** We use appropriate scales and avoid truncating axes to prevent exaggerating or downplaying trends. This helps to present the data in a way that is true to its actual distribution.

8.2. **Clear Labeling:** We ensure that all axes, legends, and data points are clearly labeled, providing context to avoid any potential confusion about what the visualization represents.

8.3. **Transparent Methodology:** We provide clear explanations of the methods and calculations used in creating the visualizations, so viewers understand how the data was processed and visualized.

8.4. **Consistent Use of Visual Elements:** We apply consistent color schemes, shapes, and sizes across all visualizations to ensure that comparisons are fair and that the data is represented uniformly.


#### 9. Addressing Privacy Concerns or Sensitive Information (Are there any privacy concerns or sensitive information that need to be addressed in our visualization?)
There are no privacy concerns or sensitive information in our dataset, as the data is entirely generated and not real. It does not contain any personally identifiable information (PII) or confidential details. Since the dataset is synthetic, it poses no risks related to privacy or sensitive information.

## Visualization Results

### Introduction of New Visualizations

#### Interactive Dashboards in Power BI:

- **Description:** Cusomter Shopping Behaviour Analysis Power BI Dashboard created using bar chart with line graph, line graph and pie chart with attribute filters. This visualization incorporates various attributes and metrics part of the datasets. Leveraging demographic and transactional attributes as filters, this visualization looks to showcase following: 1) Total Purchase in comparison to previous purchase with variance based on age, 2) average review ratings by age and gender, 3) purchaase amount summary by season and gender 

- **Key Features:**
Demographic and purchase transaction attributes as filters: gender, location, season, payment method, subscription status and frequency of purchase 
total purchase amount summary: as filters are applied, this value will change 
Zoom slider: added to bar chart with line graph and line graph to dril down graphs
Data: linked directly to the excel source. For future update, update in data source will refresh Power BI dashboard 
Hover Enabled: users can hover over visualization to get data
Drill-down: all visualization within the dashboard has drill-down capabilities 
Colour theme: updated to distinguish between different segments 
- **User Interaction:** 
As the user leverages the filters, visualizations within the dashboard will update based on the selected filters. 
Audience can also hover over the graphs and visualization to get additional information as required. 
Intention is to ensure to provide summary of the data as well as detailed visualization to tailor the dashboard for wide-range of audience 
![Power BI Visualization](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Power%20BI%20Visualization%20-%20Team%20Project2.png)



#### Interactive Dashboards in Tableau:

- **Description:** Tableau dashboard was created to support self-serve insights generation. It is designed keeping in view a general business user who lack technical skills but have broader business knowledge. The dashboard focuses on geographical coverage area and other features like age, product class, item purchased, rating and their impact on purchasing. We used map to uncover geo-mapping, bar charts to compare different age groups, heatmap for comparison of item purchased, stacked bar charts for comparing gender and category whereas scatterplot for understanding correlation between amount purchased and rating. 

The dashboard is very much interactive i.e. selection from one chart will filter the remaining charts in the dashboard so that a business user can better slice and dice the data to reach to the root cause of a problem and ultimately make a better marketing strategy that is built on data driven insights. 

- **Key Insights:** The data shows that 
  - the western states of the country are performing very well including Nevada, Montana, California and Idaho. 
  - Customer aging from 20 to 60 years are all equally contributing in the sales. 
  - Overall Blouse is the frequently purchased item and is the top most contributor for the business. 
  - Distribution for purchase amount is very much flat i.e. we did not find any evidence that shows a particular range of purchase amount was more frequent then others.  
  - Nevada stores struggle with attracting customer of middle age who are in their 40s whereas in other regions, this was not the case. 
  - Jackets being the most popular item for customers in 40s whereas Jewellery is popular for customers in 30s. 
  - There was no major distinction between the purchasing behavior of men vs women. 


- **Dashboard Screenshot:** 
![Customer Shopping Analysis in Tableau ](https://github.com/OlenaBolokhonova/team_project_2/blob/feature-tableau1/src/tableau1.png) 


- **Short Demo on interactivity:** 
  
![Customer Shopping Analysis in Tableau ](https://github.com/OlenaBolokhonova/team_project_2/blob/feature-tableau1/src/tableau1.gif) 


### Comparative Analysis: Generated vs. Real Dataset Visualizations

#### Introduction
An acquiring real datasets for analyzing customer purchase behaviors was challenging. Large retail platforms like Amazon, eBay, Walmart, and Home Depot, etc typically do not release real customer data for public research due to privacy concerns, particularly when it involves sensitive demographic information such as age and gender. 

After extensive searching, we identified a real-world dataset from a recent study published by Nature titled ["Open e-commerce 1.0"](https://www.nature.com/articles/s41597-024-03329-6#Sec10). This dataset contains detailed purchase histories from over 5,000 U.S. Amazon.com consumers between 2018 and 2022. 

The "Open e-commerce 1.0" public dataset due to security and privacy concerns does not open demographic details such as age and gender are absent. The dataset contains only anonymized identifiers, like coded survey responder IDs. However, based on gender and age demographics this source does provide line graphs that can be used for comparison. 

![Head Dataframe Amazon](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Head_dataframe_Amazon.jpg)

Given these circumstances, we decided to compare the visualizations generated from our dataset with those derived from this real-world dataset to highlight the differences in patterns, and insights.

## Comparative Analysis

### 1. Age and Purchase Amount Comparison

- **Generated Data**:
  - **Visualization**: The line graph from our generated dataset displayed minor fluctuations in purchase amounts across different ages. Although some variations were present, they were not significant enough to suggest any clear trend or correlation between age and spending.

![Purchase Amount by Age](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Python_purchase_amount_age.png)

  - **Insights**: The visualizations demonstrated that while line graphs can suggest some variability, bar charts provided a more accurate depiction, showing no significant differences in spending among different age groups. This consistency across different visualizations underscores the limitations of synthetic data in identifying nuanced behavior patterns.
    
![Average Purchase Amount by Age Group](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Python_vis_ave_amount_purchases_age_group.png)

- **Real Data**:
  - **Visualization**: The line graph from the "Open e-commerce 1.0" dataset showed much clearer trends, with distinct peaks and troughs corresponding to different age groups. This graph indicated a stronger correlation between age and purchase amounts, with certain age groups consistently spending more than others.

![Fig 2 Dataset Amazon](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Fig2_dataset_Amazon.jpg)


### 2. Gender and Purchase Amount Comparison

- **Generated Data**:
  - **Visualization**: The bar charts from our generated dataset displayed slight differences between male and female customers in terms of total purchases, number of purchases, and average purchase amounts. However, these differences were minimal and did not indicate any strong gender-based trend.
  - **Insights**: The consistency in minimal differences across the visualizations highlights the limitations of generated data in capturing real-world gender-based spending patterns.
    
![Purchases by Gender](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Pyton_purchases_by_gender.png)

- **Real Data**:
  - **Visualization**: The "Open e-commerce 1.0" dataset, however, revealed more pronounced differences in gender-based spending. For example, males and females displayed different purchasing patterns over time, with males generally spending more on certain types of products, while females showed a stronger preference for other categories.
  - **Insights**: The gender-based analysis in the real dataset revealed tangible differences in spending habits between men and women, which were not evident in the generated data. This suggests that gender plays a more significant role in real-world consumer behavior.
    
  ![Fig 2 Dataset Amazon](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Fig2_dataset_Amazon.jpg)

### 3. Revised Location Distribution Visualization
 
- **Generated Data**:
 - **Visualization**: The Location Distribution visualization provides an overview of customer distribution across various U.S. states. The visualization highlights regions with higher concentrations of customers, making it easier to identify key markets.

 ![Customer Location Distribution](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Location_Distribution_Visualization.png)

 - **Insights**: The generated data successfully displays the geographic distribution of customers, which can help in identifying potential target areas for marketing campaigns. However, the simplicity of the generated data might not capture more nuanced distribution patterns that could be present in a real dataset.

- **Real Data**:
 - **Visualization**: In a real-world dataset, we would expect more variability in customer distribution across regions, potentially revealing trends related to economic factors, population density, and consumer behavior that are not fully captured by the generated data.

 - **Insights**: A real dataset would likely provide a more complex picture of location-based consumer behavior, allowing for more targeted and effective marketing strategies.

### 4. Revised Purchase Amount by Location

- **Generated Data**:
 - **Visualization**: The Purchase Amount by Location visualization compares average purchase amounts across different U.S. states. It highlights the top and bottom states by average spending, providing a clear view of regional spending behavior.

 ![Customer Purchase Amount by Location](https://github.com/OlenaBolokhonova/team_project_2/blob/team_project_2/src/Purchase_Amount_by_Location.png)

 - **Insights**: This visualization offers insights into which regions have higher or lower average spending. While useful, the generated data may not fully reflect the complexities of consumer spending patterns that would be seen in a real dataset.

- **Real Data**:
 - **Visualization**: A real-world dataset would likely show more varied spending patterns across locations, influenced by factors such as income levels, local economic conditions, and cultural differences.

 - **Insights**: The real data would provide a more nuanced understanding of regional spending habits, allowing for better-informed decisions in resource allocation and marketing efforts.

## Conclusion
The comparative analysis highlights the importance of using real-world data for deriving actionable insights. While generated datasets are valuable for practicing data analysis and visualization techniques, they lack the variability and complexity of real consumer behavior. In contrast, the "Open e-commerce 1.0" dataset provides a rich source of information that can lead to more accurate and impactful business decisions. 

The visualizations from the real dataset were clearer in depicting trends over time, as the data was rich with chronological purchase histories that allowed for a detailed analysis of how shopping behaviors evolved. 

The real dataset enabled us to extract more actionable insights, such as identifying peak shopping periods for different demographics and understanding how external factors (like holidays or economic changes) influenced purchase behavior.

#### Accomplishment Log
1. Aug 6 - created README_Project2.md file and leveraged project 1 README file as a foundation for project 2 updates - Jessilynn Kim
2. Aug 6 - created PowerBI visualization dashboard - Jessilynn Kim
3. Aug 7 - new repository was created with new branch team_project_2 - Olena Bolokhonova
4. Aug 7 - reviewed previous dataset and determined to search for similar dataset that is not fictious - all team members
5. Aug 8 - updated README_Project2.md - Jessilynn Kim
6. Aug 9 - renamed and updated README_Project1.md - Olena Bolokhonova
7. Aug 9 - updated README_Project2.md - Olena Bolokhonova
8. Aug 9 - updated customer shopping behavior analysis.ipynb - Olena Bolokhonova
9. Aug 9 - Power BI Visualization - Team Project file added to src folder - Jessilynn Kim
10. Aug 9 - updated Power BI visualization details - Jessilynn Kim
11. Aug 10 - add visualization_project_part2.ipynb  - Olena Bolokhonova
12. Aug 10 - add Python_purchase_amount_age.png, Python_vis_ave_amount_purchases_age_group.png, Pyton_purchases_by_gender.png - Olena Bolokhonova
13. Aug 13 - update visualization_project_part2.ipynb - Mykhailo Vitvinov
14. Aug 14 - add Location_Distribution_Visualization.png, Purchase_Amount_by_Location.png - Mykhailo Vitvinov
15. Aug 14 - updated README_Project2.md - Mykhailo Vitvinov
16. Aug 14 - designed Tableu Dashboard - Shiraz Latif
17. Aug 14 - add tableau1.png and tableau1.gif - Shiraz Latif
18. Aug 15  - updated README_Project2.md - Shiraz Latif

### Rules of Engagement 
#### Engagement Channel:
1. Zoom Breakout Room
2. Whatsapp Group
3. Slacks
4. Github
5. Emails
6. Google Meets

#### Communication:
• Leveraging Whatsapp group for main communication
• Any delays in joining meeting, completion of task, or availabilities for meeting times are shared 

#### Meeting Schedule:
1. Post live session breakout room 
    • Check in around 7:15 for about 15 mins
    • Check in around 9:00 for about 15 mins
2. Friday
    • During work period 
    • Evening around 6-7 pm 
3. Saturday -TBD

#### Progress Tracking
Shared Excel Tracker
    • Documenting tasks and progress
    • Avoid possible duplication with visibility for everyone

#### Conflict Resolution 
1. Voting
2. Respecting other's opinions
3. Listening
5. Actively communicating during meetings
6. Avoid assumptions and ask questions where clarity is required 



