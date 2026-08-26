# Healthcare Analysis Project

**Healthcare Analysis Project** reflects my commitment to raising awareness on risk factors that could affect economic, social and physical wellbeing. The purpose of this project is to provide a healthcare insurance business with an exploratory data analysis (EDA), based on a clean data frame I extract, transform and load (ETL) as part of the data preperation to enhance the integrity of insights drawn from the dataset. 

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

The requirements in this healthcare insurance analysis is to review and prepare raw data prior to analysis. Once the ETL pipeline is complete my goal is to apply the EDA process and present connections between personal attributes or regional factors affecting insurance charges. As a result, the business will have access to an insightful resource contributing toward data driven decision making.

## Hypothesis and how to validate?

The hypothesis for this healthcare analysis are listed as a series of questions:

* How does smoking status affect the minimum, average and maximum insurance charges?

* What is the correlation between smoking status, age or number of children on insurance charges?

* Can BMI affect insurance charges?

* Are insurance charges affected by regional factors?

* How do charges differ between genders in correlation with number of children and charges? 

* Is there a trend for higher premiums on insurance charges for women who experience increased childbirth?

A range of charts are visualised by importing libiraries Plotly, Seaborn and Matplotlib to validate the questions raised in the hypothesis. 


## Project Plan

**Initialise Project Environment**
Create a repositry on GitHub to connect with a virtual environment setup on VS Code. Add .gitignore file, folders for data and Jupyter notebooks. Install dependencies required for the ETL and Data Visualisation notebooks code cells to run successfully. Add README.md template including guidance notes provided by Code Institute.   

**Collect Data**
The dataset required for the healthcare insurance analysis is downloaded as a CSV file from Kaggle. I store the data inside a folder which is also accessible in my GitHub repositry.

**Extract, Transform and Load (ETL)**
Data is summarised using Pandas to load and review the dataframe. Missing or unique values and duplications are evaluated to enhance integrity of the dataset prior to drawing insights from the data. 

**Data Visualisation**
A clean dataframe is loaded to apply different methods for visualising dataset using Plotly, Seaborn and Matplotlib. Markdowns and psydocode is recorded throughout jupyter notebook to highlight the steps toward visualisation. 

**Review Project**
A final review of the entire project is considered prior to submitting the healthcare insurance analysis. 

## The rationale to map the business requirements to the Data Visualisations

* List your business requirements and a rationale for mapping them to the Data Visualisations

## Analysis techniques used

* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques? Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations

The dataset does not breach GDPR because there is no directly identifiable personal information visible that would identify any individual. 

However, it is important to acknowledge the dataset is simulated and thus cannot be liable to inform real-world decision making within a healthcare insurance business. Using this report could put potentially viable customers at risk to be excluded from accessing healthcare insurance or being charged higher premiums as a result of the insights presented in this hypothetical analysis.

Economic status, education, mental health and other factors which could potentially also influence insurance charges are not included in this dataset. 

## Dashboard Design (optional)

* Feel free to delete this section if this is a data visualisation only (unit 1 or 2) project submission.
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during project development, you may revisit your dashboard plan to update a feature (for example, at the beginning of the project, you were confident you would use a given plot to display an insight, but later you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs

* Please list any unfixed bugs and explain why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap

* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Main Data Analysis Libraries

Numpy, Pandas, Seaborn, Matplotlib and Plotly. 

## Credits

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials; however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section into Content and Media, depending on what you include in your project. 

### Content 

- The text for the Home page was taken from the Wikipedia Article A
- Instructions on how to implement form validation were taken from a [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)

* Thank the people who supported this project.