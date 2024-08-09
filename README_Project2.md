## Team Project Part 2
### Consumer Behavior and Shopping Habits

### Group 24 
#### Team Members 

- Shiraz Latif: 
- Jessilynn Kim:  
- Mykhailo Vitvinov: 
- Olena Bolokhonova: 

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

### Revised Visualizations

#### Enhanced Bar Charts:
- **Description:** Summarize the improvements made to the bar charts used in Part 1, focusing on how these changes improved readability, accuracy, and the communication of key insights.
- **Key Insights:** Highlight the primary takeaways from the revised bar charts, such as demographic purchase behaviors or location-based sales patterns.
#### link on png file 

### Introduction of New Visualizations

#### Interactive Dashboards in Power BI:
- **Description:** Explain the creation and purpose of interactive dashboards, emphasizing how these allow users to explore the data dynamically.
- **Key Features:** Highlight the features of the dashboards, such as filters, drill-down capabilities, and real-time updates.
- **User Interaction:** Describe how the audience can interact with the dashboards to customize their view and extract specific insights relevant to their needs.
#### link on png file 

#### Additional Visualizations (if any):
- **Description:** Introduce any new types of visualizations created in Part 2, such as heatmaps or scatter plots, and explain why these were chosen.
- **Key Insights:** Present the main findings or patterns these new visualizations reveal, and how they contribute to the overall analysis.
#### link on png file 

### Comparative Visualization
#### Comparison with Initial Visualizations:
- **Side-by-Side Comparison:** Show a comparison between the original visualizations from Part 1 and the revised or new visualizations from Part 2.
- **Improvement Discussion:** Discuss how the changes made in Part 2 improved the communication of data insights and addressed any shortcomings identified in the initial visualizations.

#### Comparison with Real Data Visualizations:
- **Real vs. Generated Data:** If applicable, compare visualizations from the generated dataset with those from a real dataset. Highlight differences in patterns, clarity, and insights derived from each.
#### link on png file 

#### Accomplishment Log
1. Aug 6 - created README_Project2.md file and leveraged project 1 README file as a foundation for project 2 updates - Jessilynn Kim
2. Aug 6 - created PowerBI visualization dashboard - Jessilynn Kim
3. Aug 7 - new repository was created with new branch team_project_2 - Olena Bolokhonova
4. Aug 7 - reviewed previous dataset and determined to search for similar dataset that is not fictious - all team members
5. Aug 8 - updated README_Project2.md - Jessilynn Kim
6. Aug 9 - renamed and updated README_Project1.md - Olena Bolokhonova
7. Aug 9 - updated REAME_Project2.md - Olena Bolokhonova


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
4. Actively communicating during meetings
5. Avoid assumptions and ask questions where clarity is required 



