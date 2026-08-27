# Healthcare Analysis Project

**Healthcare Analysis Project** reflects my commitment to raising awareness of risk factors that could affect economic, social and physical wellbeing. The purpose of this project is to provide a healthcare insurance business with an Exploratory Data Analysis (EDA), based on a clean DataFrame I extract, transform and load (ETL) as part of the data preparation process to improve the integrity of insights drawn from the dataset.

## Dataset Content

This dataset contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits), geographic factors, and their impact on medical insurance charges. It can be used to study how these features influence insurance costs and develop predictive models for estimating healthcare expenses.

> Age: The insured person's age.

> Sex: Gender (male or female) of the insured.

> BMI (Body Mass Index): A measure of body fat based on height and weight.

> Children: The number of dependents covered.

> Smoker: Whether the insured is a smoker (yes or no).

> Region: The geographic area of coverage.

> Charges: The medical insurance costs incurred by the insured person.

The dataset and description provided can be found on the link to Kaggle website below:

https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance

## Business Requirements

The requirements for this healthcare insurance analysis are to review and prepare raw data prior to analysis. Once the ETL pipeline is complete, my goal is to apply the EDA process and present relationships between personal attributes and insurance charges. As a result, the business will have access to an insightful resource contributing towards data-driven decision making.

## Hypothesis and how to validate?

The hypothesis for this healthcare analysis is explored through a series of questions:

* What is the distribution quality in the dataset?

* How does smoking status affect the minimum, average and maximum insurance charges?

* What is the correlation between smoking status, age and insurance charges?

A range of charts are visualised by importing Plotly, Seaborn and Matplotlib to validate the questions raised in the hypothesis.

**NOTE:** The original analysis plan was reduced due to time restrictions and underestimating the time required to manage the EDA process. In hindsight, more time should have been allocated to the EDA stage or tasks organised more effectively. The analysis was therefore focused on the questions considered most relevant to the business requirements.

## Project Plan

**Initialise Project Environment**
Create a repositry on GitHub to connect with a virtual environment setup on VS Code. Add .gitignore file, folders for data and Jupyter notebooks. Install dependencies required for the ETL and Data Visualisation notebooks code cells to run successfully. Add README.md template including guidance notes provided by Code Institute.   

**Collect Data**
The dataset required for the healthcare insurance analysis is downloaded as a CSV file from Kaggle. I store the data inside a folder which is also accessible in my GitHub repositry.

**Extract, Transform and Load (ETL)**
Data is summarised using Pandas to load and review the dataframe. Missing or unique values and duplications are evaluated to enhance integrity of the dataset prior to drawing insights from the data. 

**Data Visualisation**
The clean DataFrame and smokers charges DataFrame are loaded to apply different visualisation methods using Plotly, Seaborn and Matplotlib. Markdown and pseudocode are recorded throughout the Jupyter notebook to highlight the steps towards visualisation and interpretation.

**Review Project**
A final review of the entire project is considered prior to submitting the healthcare insurance analysis. 

## The rationale to map the business requirements to the Data Visualisations

**Extract, Transform, Load:** Follow the ETL steps to verify data integrity, integrate feature engineering for predictive analysis and save clean DataFrames before entering the EDA process.

**Exploratory Data Analysis:** Present clean DataFrames to communicate meaningful visualisations answering questions listed in the hypothesis.

## Analysis techniques used

**Descriptive:** Bar charts and boxplots were used to explore the distribution of categorical and numerical attributes.

**Correlation:** Scatterplots were used to explore relationships between age, smoking status and insurance charges.

**Predictive:** An engineered DataFrame containing minimum, mean and maximum insurance charges by smoker status was visualised using Plotly to estimate differences in charges.

The data analysis techniques were structured into descriptive, correlation and predictive analysis. Each section includes an explanation of the technique used and an interpretation of the results.

The limited attributes reduced the ability to fairly predict insurance charges. However, the available data provided meaningful insights into relationships between the attributes.

GitHub Copilot was used within the IDE to generate and fix code and improve code readability.

## Ethical considerations

The dataset does not breach GDPR because there is no directly identifiable personal information visible that would identify any individual. 

However, it is important to acknowledge the dataset is simulated and thus cannot be liable to inform real-world decision making within a healthcare insurance business. Using this report could put potentially viable customers at risk to be excluded from accessing healthcare insurance or being charged higher premiums as a result of the insights presented in this hypothetical analysis.

Economic status, education, mental health and other factors which could potentially also influence insurance charges are not included in this dataset. 

## Artificial intelligence disclosure 

AI is a tool I refer to as a semantic calculator I approach with a Socratic methodology. In other words, I form the questions to ask for me to meet the business requirements and complete tasks more efficiently. 

I preserve my agency over artificial intelligence by critically reading and challenging output to interogate the AI rationale. Ultimately I have ensured this Healthcare Analysis Project returns to my instrinsic motivations and subjective discretion. 

I consistently cross reference solutions for code, understanding keywords and propositions to optimise projects made by Chat GPT, Gemini and CoPilot with official documentation, LMS and websites discovered through the Google search engine. 

## Development Roadmap

A challenge I faced was managing the scope of the EDA process within the available time. I underestimated the time required to develop and interpret the visualisations, which resulted in the original hypothesis being reduced. In hindsight, I would have allocated more time to the EDA process or organised the tasks more effectively.

Feature engineering is limited in this project and could be expanded on in a future project. Whilst transforming the DataFrame in the ETL process I limit the potential to develop machine learning features which would improve the quality of the predictive analysis included in the EDA notebook. 

Additionally, I recognise a lack of confidence in choosing appropriate charts to visualise data meaningfully. My experience in this project has prompted me to learn (1) the usage for different charts to communicate attributes effectively and (2) interpreting results in the charts. 
 

## Main Data Analysis Libraries

Numpy, Pandas, Seaborn, Matplotlib and Plotly. 

## Credits

#### Extract, Transform, Load 

https://gist.github.com/Ri-Dearg/61447981a85878945e189b378f95d92c
https://gist.github.com/mbriscoe/244fab3649ef23da86099d0c5f4a6c81
https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf
https://jacknayem.medium.com/why-every-data-analyst-should-master-df-info-the-most-overlooked-tool-in-pandas-d4e3018e3606
https://www.geeksforgeeks.org/pandas/pandas-find-duplicate-rows/
https://stackoverflow.com/questions/22904523/select-rows-with-duplicate-observations-in-pandas
https://pandas.pydata.org/docs/getting_started/intro_tutorials/03_subset_data.html
https://www.geeksforgeeks.org/python/grouping-categorical-variables-in-pandas-dataframe/
https://github.com/ashishpatel26/Amazing-Feature-Engineering/blob/master/A%20Short%20Guide%20for%20Feature%20Engineering%20and%20Feature%20Selection.md
https://builtin.com/articles/feature-engineering
https://www.bhf.org.uk/informationsupport/heart-matters-magazine/medical/tests/bmi-chart

#### Data Visualisation 

https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplots.html 
https://seaborn.pydata.org/generated/seaborn.countplot.html
https://seaborn.pydata.org/generated/seaborn.scatterplot.html
https://plotly.com/python/bar-charts/

#### Jupyter Notebook Markdown

https://stackoverflow.com/questions/35616486/embed-code-for-illustration-in-jupyter
https://stackoverflow.com/questions/36583502/how-to-force-a-linebreak

#### README

https://github.com/Code-Institute-Solutions/da-README-template
https://github.com/petedanielsmith/HealthcareInsuranceDataAnalyticsProject/tree/main

#### Proofreading 

ChatGPT

Preserve your tone and style
Keep the wording minimal and concise
Correct grammar, spelling and punctuation
Improve clarity and technical accuracy where needed
Maintain a coherent ETL storyline from data loading through transformation and export
Preserve your existing Markdown and <code> formatting

#### Acknowledgements

Thank you to Mike at Code Institute for the fascinating dialogue around the future of AI and Data Visualisation, which motivated me to apply for this opportunity.

Thank you to Laura at Code Institute for believing in my intelligence to comprehend the information on the bootcamp and participate meaningfully in my cohort.

Thank you to Emma for teaching me there is, in fact, method in the madness.

Thank you to Rory for the patient and articulate masterclasses that consolidated the LMS content.

Thank you to my friend Patsy for being my existential coach and encouraging me to show up every day.

I’m grateful to the Ivkos for accommodating a hard reset in my search for stability and empowering me to reach my fullest potential.

I acknowledge and appreciate the use of ChatGPT, Gemini and GitHub Copilot throughout this project.