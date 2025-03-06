
### Amanjot Kandhola

Data Analyst | Salesforce, SQL, Python, Pandas, Data Visualization | Taught Coding languages

Data Science - University of Waterloo and University of Toronto
<br>Masters of Computer Science Engineering - Chitkara University, India

Current job: Data Analyst at Nonprofit Serving Individuals with Visual Impairments

----------
Hi 👋 

As a data analyst at [CNIB](https://www.cnib.ca/en?region=on), a nonprofit organization dedicated to supporting individuals with visual impairments, I bring a Masters of Engineering in Computer Science and over 10 years of experience in teaching coding languages and bringing data analytics to the table.

Driven by an insatiable curiosity and a solid foundation in critical thinking, my career has been centered around solving complex problems. I specialize in using SQL and Python for tasks ranging from data collection and wrangling to analysis and visualization, ensuring that insights are not only comprehensive but also accessible to all.

In summary, I offer a unique combination of technical expertise, problem-solving skills, and a dedication to serving our community. My proficiency in utilizing the Python data science software ecosystem enables me to provide valuable insights and drive meaningful change through data analysis, visualization, and effective communication.

Currently enrolled in [Data Science program](https://github.com/amanjot-git/data-science-UofT/tree/main) by University of Waterloo and University of Toronto

------------

### 🎓My Learning - Experience Journey 
- [Data Science - University of Toronto and University of Waterloo](https://learn.utoronto.ca/programs-courses/certificates/data-science) ('24)
- [Google Data Analytics ](https://www.coursera.org/account/accomplishments/specialization/2VM7V2A6ZAS5) ('22)
- Master of Engineering in Computer Engineering - Chitkara University ('16)
- Bachelor of Engineering in Computer Engineering - Chitkara University ('13)



### 🌱 My latest projects 
From Energy to Health: Data Science Insights Across Diverse Domains
In my journey as a data scientist, I’ve had the opportunity to work on diverse projects that span energy management, financial risk, probability puzzles, behavioral science, and healthcare. Each project has allowed me to apply advanced data processing, statistical inference, machine learning, and simulation techniques to generate actionable insights. Here’s an in‐depth look at these projects and the methodologies I used to drive impactful business outcomes.

### 1. Powering Insights: Energizing Customer Segmentation Through K-Means Clustering**
In one of my earlier projects, I was tasked with analyzing electricity usage data to help energy providers optimize consumption management. The first step was to preprocess and normalize the raw electricity usage data. This process involved handling missing values, scaling the data appropriately, and ensuring that all features were on a comparable scale for clustering.

### Preprocessing and Normalization:
I started by cleaning the dataset to remove or impute any missing or inconsistent values. After ensuring data quality, I applied normalization techniques to scale the usage data so that variations in energy consumption could be compared fairly across different customers.

### Applying K-Means Clustering:
With the data prepped, I applied the K-Means algorithm to segment clients into distinct groups based on their consumption patterns. The idea was to uncover natural clusters in the data that could indicate different types of energy usage profiles.

### Iterative Tuning and Cluster Evaluation:
I iteratively tuned the number of clusters by running multiple experiments and evaluating cluster performance using metrics such as the silhouette score. By visually examining the cluster profiles and quantifying inter-cluster differences, I derived actionable insights that helped optimize energy management strategies. These insights included recommendations on targeted energy-saving programs and identifying high-consumption clusters that might benefit from specialized tariffs or incentives.

This project not only demonstrated the power of unsupervised learning in segmenting customers but also provided a roadmap for energy companies to implement data-driven strategies that reduce consumption and improve operational efficiency.

### 2. Credit Crunch Classifiers: Tuning Random Forest & KNN for Default Prediction
Another project involved developing a predictive model for credit card defaults. The goal was to create a comprehensive data pipeline that would allow for robust risk assessment in the financial sector.

### Data Pipeline Construction:
I began by exploring the raw features of the credit card defaults dataset. The pipeline involved data cleaning (handling missing values, outliers, and inconsistencies), feature engineering, and ensuring the dataset was ready for model training. A key step was splitting the data into training and testing sets using a fixed random seed to ensure reproducibility.

### Model Implementation and Cross-Validation:
Two classification models were chosen—Random Forest and K-Nearest Neighbors (KNN). For each model, I tuned critical hyperparameters: for Random Forest, I varied the number of estimators (ranging from 4 to 50), and for KNN, I tuned the number of neighbors. I then employed 5-fold cross-validation to evaluate model performance consistently.

### Performance Evaluation Using ROC Analysis:
The ROC (Receiver Operating Characteristic) curve was used to compare the performance of both models. The area under the ROC curve (AUC) helped determine which model better distinguished between defaulters and non-defaulters. This detailed performance evaluation ultimately guided the selection of the optimal model, enabling the credit card company to better manage risk and reduce default rates.

This project underscored the importance of building a full data pipeline and how careful cross-validation and model tuning can lead to significant improvements in predictive accuracy.

### 3. The Winning Switch: Unraveling the Monty Hall Paradox via Simulation
Inspired by a classic probability puzzle, I developed a Python simulation to explore the Monty Hall problem. This exercise was not only intellectually stimulating but also a great example of how simulation can shed light on counterintuitive probability outcomes.

### Simulation Setup:
The simulation was designed to run thousands of iterations of the Monty Hall game. In each iteration, a car was randomly placed behind one of three doors, and the contestant made an initial choice. The host then opened one of the remaining doors, always revealing a goat.

### Strategy Comparison:
I simulated two strategies: sticking with the initial choice versus switching to the remaining door. By recording the outcomes for each strategy across thousands of iterations, I was able to compare win rates directly.

### Results and Insights:
The simulation consistently demonstrated that switching doors increased the win rate significantly compared to staying with the initial choice. This exercise not only confirmed the counterintuitive nature of the Monty Hall problem but also highlighted the power of simulation in validating probabilistic models and hypotheses.

This project is a prime example of how theoretical probability can be brought to life through simulation, providing tangible evidence to support the strategy of switching doors.

### 4. Buzzing Differences: Beer vs. Water in Mosquito Attraction Revealed
In a project focused on behavioral science and experimental design, I analyzed a dataset that measured the number of mosquitoes attracted under two different treatments: beer consumption versus water consumption.

### Visual Data Exploration:
I began by loading the mosquitos dataset and creating side-by-side boxplots to visually compare the distribution of mosquito counts between the Beer and Water groups. The visualizations revealed that the Beer group had a higher median and a wider interquartile range compared to the Water group.

### Descriptive Statistics:
I computed key descriptive statistics (mean, median, and standard deviation) for each group. The statistics confirmed that, on average, more mosquitoes were attracted when beer was consumed. This provided initial evidence of an association between beer consumption and increased mosquito attraction.

### Permutation Testing via Resampling:
To test the significance of this association, I implemented a permutation test by resampling the data over 10,000 iterations. The test calculated a very low p-value, leading to the rejection of the null hypothesis. This statistically supported the claim that there is a meaningful association between beer consumption and mosquito attraction.

This project combined exploratory data analysis with rigorous statistical testing to validate experimental findings—demonstrating the effectiveness of resampling techniques in hypothesis testing.

### 5. Risk, Rewards, and Returns: Statistical Inferences in Finance and HR
In another multifaceted project, I applied statistical inference methods to assess both financial and operational data. The project had two key parts: analyzing portfolio performance under the Capital Asset Pricing Model (CAPM) and evaluating the effectiveness of a new HR rewards system on reducing employee absenteeism.

### Analyzing Portfolio Performance:
I used statistical measures such as z-scores and p-values to analyze the distribution of portfolio returns assumed to be normally distributed under CAPM. By calculating expected returns and the probability of negative returns, I provided insights into the risk profile of the portfolio. Additionally, I computed cutoff points for the highest 15% of returns, offering valuable benchmarks for portfolio performance.

### Evaluating HR Rewards System:
Past data indicated that low morale led to significant absenteeism. After the implementation of a new rewards system, I collected a sample of employee data and performed a hypothesis test to determine whether absenteeism had decreased significantly. The test results, based on a 90% confidence level, showed that the new rewards system was effective. I further calculated the probability of a Type II error (missing the reduction in absenteeism) and determined the required sample size for achieving a β of 5%.

### Chi-Square Goodness-of-Fit:
Finally, I performed a chi-square goodness-of-fit test on stock return streaks to evaluate whether the observed distribution of streaks followed the expected geometric distribution. The test confirmed that the stock return streaks did not deviate significantly from the expected values, thereby supporting the efficient market hypothesis.

This comprehensive project showcased how combining financial analysis with HR analytics and robust statistical testing can lead to actionable business insights, helping organizations make informed decisions on both risk management and employee engagement strategies.

### 6. Linear Logic: Transformations, Diagnostics, and the Art of Regression
In a project centered on regression analysis, I explored several datasets to understand the nature of relationships between variables, applying both linear and non-linear models as needed.

### Exploratory Analysis and Data Transformation:
I began by creating scatter plots for each dataset to visually inspect the relationship between variables. For datasets that displayed non-linear trends (such as exponential or logarithmic relationships), I applied various transformations (logarithmic, exponential, square root) to achieve linearity. This step was crucial because linear regression assumptions must be met for the model to be valid.

### Building OLS Regression Models:
Once the appropriate transformations were identified, I built Ordinary Least Squares (OLS) regression models on both the original and transformed data. For each model, I generated diagnostic charts—including residual plots, leverage plots, and influence plots—to check for normality, homoscedasticity, and the presence of outliers.

### Outlier Analysis and Model Comparison:
In datasets with influential outliers, I compared models built with and without these points. The removal of outliers often led to a noticeable change in the model’s slope, intercept, and R-squared values. This comprehensive analysis allowed me to interpret the regression coefficients accurately, offering insights into how the independent variables affect the dependent variable.

This project emphasized the importance of data transformations and diagnostic testing in regression analysis, ensuring that the final models were both statistically sound and practically interpretable.

### 7. Health Under the Lens: Data-Driven Insights in Diabetes Risk & Prevention
My most extensive project involved working with a large diabetes dataset. This project spanned data cleaning, enrichment, exploratory data analysis (EDA), hypothesis testing, and predictive modeling—all aimed at uncovering key risk factors for diabetes and informing preventive strategies.

### Data Cleaning and Enrichment:
I began by cleaning the dataset, addressing missing values and inconsistencies. I enriched the data by categorizing patients into different groups based on age, BMI, race, and HbA1c levels. For instance, I created age groups (Under 18, 18-44, 45-64, Over 65), BMI categories (Underweight, Healthy Weight, Overweight, Obesity), and classified HbA1c levels (Normal, Prediabetes, Diabetes). This categorization helped in stratifying the patient population and enabled more granular analysis.

### Exploratory Data Analysis (EDA):
I conducted extensive EDA by generating histograms, boxplots, and bar charts to visualize the distribution of continuous variables (age, BMI, HbA1c, blood glucose) and to compare diabetes prevalence across different groups. For example, side-by-side boxplots highlighted differences in HbA1c levels between diabetic and non-diabetic patients, while bar charts illustrated variations in diabetes prevalence by race and gender. Descriptive statistics and bootstrapping were used to generate confidence intervals, providing a robust statistical foundation for my findings.

### Statistical Analyses and Predictive Modeling:
I built logistic regression models to predict diabetes status based on key risk factors such as hypertension, heart disease, BMI, HbA1c levels, blood glucose levels, and smoking history. I also performed Chi-square tests to evaluate dependencies between diabetes and categorical variables like race and gender. Additionally, time trend analyses were carried out to examine how the prevalence of diabetes—and related health metrics—changed over time (from 2015 to 2022). This multi-layered approach provided insights into which groups were at higher risk and where targeted preventive measures could be most effective.

### Key Insights and Business Impact:
The analysis revealed that older populations, particularly those in the 45-64 and Over 65 age groups, as well as individuals in the Obesity and Overweight BMI categories, exhibited higher diabetes prevalence. Conditions like hypertension and heart disease further compounded the risk. The logistic regression models consistently showed that HbA1c and blood glucose levels were the strongest predictors of diabetes across all racial groups. These findings support targeted health interventions and preventive strategies, enabling healthcare providers to allocate resources effectively and design customized programs for high-risk populations.

### Conclusion
Each of these projects reflects my commitment to leveraging data science to drive actionable insights across varied domains. Whether optimizing energy consumption, predicting financial defaults, solving classical probability puzzles, investigating behavioral phenomena, or advancing healthcare outcomes, my approach is centered on thorough data preprocessing, rigorous statistical testing, and thoughtful model evaluation.

By combining these methodologies, I have been able to provide stakeholders with clear, data-driven recommendations that not only improve operational efficiency but also enhance risk management and preventive healthcare strategies. I am excited to continue exploring new challenges and harnessing the power of data to transform insights into impactful actions.


- [KNN Classification](https://github.com/amanjot-git/data-science-UofT/blob/main/assignment4_Classification.ipynb)
- [Credit Risk Analysis ](https://github.com/amanjot-git/credit-risk-analytics/blob/main/Credit%20Risk%20Analysis.ipynb) 
- [COVID Data Exploration in SQL](https://github.com/amanjot-git/PortfolioProjects/blob/main/Portfolio%20Project%20-%20COVID%20Data%20Exploration%20in%20SQL.sql) - Alex the Analyst Practice Project
- [Real Estate Data Analytics](https://github.com/amanjot-git/real-estate-data-analytics/blob/main/Real%20Estate%20Data%20Analytics.ipynb)
  



### 🏆My Latest Certifications  
- [dbt Fundamentals](https://credentials.getdbt.com/ca66b04f-4329-4b83-996e-aa21abfc25e2) - May 2024
- [IBM Data Analysis and Visualization Foundations](https://www.coursera.org/account/accomplishments/specialization/QFB6FGDZFGRB) - June 2023
- [Google Data Analytics Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/2VM7V2A6ZAS5) - September 2022
- [Microsoft Power BI Desktop](https://www.linkedin.com/learning/certificates/7bca1a17416ff1fec09e02cd90fc7360b55e870f8be0081802d655a996bc15d0?trk=backfilled_certificate) - June 2020
- [Advanced SQL for Data Scientists](https://www.linkedin.com/learning/certificates/20b8b7a430446ae58029425159f5d46c7fa6484890435b5603d75fb2565862da?trk=backfilled_certificate) - June 2020
  



## My Skill Set  
<table><tr><td valign="top" width="33%">



### Frameworks, Platforms and Libraries  
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)



### Databases  
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)  
  



### IDEs/Editors  
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84.svg?style=for-the-badge&logo=android-studio&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)  


</td><td valign="top" width="33%">



### Languages  
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)  
  



### ML/DL  
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

</td><td valign="top" width="33%">


### Education  
[![Coursera](https://img.shields.io/badge/Coursera-%230056D2.svg?style=for-the-badge&logo=Coursera&logoColor=white)](https://www.coursera.org/user/fb4413559ca3b9e51de0f898bb6a32e2)
[![Salesforce](https://img.shields.io/badge/Salesforce-%2302262B.svg?style=for-the-badge&logo=Salesforce&logoColor=Blue)](https://www.salesforce.com/trailblazer/akaur38)
[![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/users/me/achievements#badges-section)
</td></tr></table>  

<br/>  


## Connect with me  
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amanjot-kandhola-a7831270/)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:dhillonaman91@outlook.com)
  

<br/> 



 Last Updated on 08/06/2024 
