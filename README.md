# Emrah Aydin – Elbruz Consulting Limited
Portfolio 

## About

I am currently a London based Data Analyst and Director of Elbruz Consulting Limited. I have recently completed my studies towards a Master's degree at Big Data Analytics and Management. I have a strong interest in Python, machine learning, data visualisation and statistical modelling. I also have undergraduate degree at Business Administration and Master of Business Administration (MBA). 

My project, You Have My Car (Arabam Sende), was selected in the top 10 in the entrepreneurship competition of TUSIAD. (https://www.bugenclikteisvar.com/bilgi-merkezi/katilimcilar/2011)  


<br>
  

## Table of contents
- [About](#about)
- [Portfolio Projects](#portfolio-projects)
	+ [Detection of Fake Sales](#detection-of-fake-sales)
	+ [Earthquake Prediction in Turkey with LSTM Model](#earthquake-prediction-in-turkey-with-lstm-model)
	+ [Violent Crimes in USA Communities](#violent-crimes-in-usa-communities)
	+ [Online Advertising Campaign Analysis](#online-advertising-campaign-analysis)
	+ [Airbnb Listings Analytics](#airbnb-listings-analytics)
- [Study Projects](#study-projects)  
    + [sklearn ML course](#sklearn-ML-course)
	+ [Kaggle 30 Days of ML](#kaggle-30-days-of-ml)
	+ [Data Analysis Course](#data-analyst-specialization)
	+ [Data Analysis Course Tinkoff-MSU](#data-analysis-course-tinkoff-msu)
	+ [Learning SQL](#learning-sql)
	+ [Python Developer Track](#python-developer-track)
	+ [Computer Science Career Path](#computer-science-career-path)
	+ [Google Python Class](#google-python-class)
	+ [Side Projects](#side-projects)
	+ [Tableau Vizzes](#tableau-vizzes)
- [Certificates](#certificates)
- [Contacts](#contacts)

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Detection of Fake Sales
**Code:** [`detection_of_fake_sales`](https://medium.com/@emrahmetu/a-real-life-example-data-analytics-in-audit-7a317bad9ccf)    
**Description:** The aim of this study is to test machine learning algorithms namely Logistic Regression, K-nears Neighbor and Decision Tree for determining which algorithm is the most effective for fake sales determination and comparing re-sampling techniques namely random under-sampling and SMOTE method. Auditors and finance staff can focus more on fraudulent activities instead of spending too much time with inefficient sampling.  
**Skills:** data cleaning, data analysis, descriptive statistics, central limit theorem, hypothesis testing, data visualization.  
**Technology:** Python, Pandas, Numpy, Scipy Stats, Seaborn, Matplotlib.  
**Conclusion:** According to the results obtained in this study, over-sampling method resulted with better accuracy in logistic regression algorithm by handling with imbalanced dataset better. Over-sampling do not cause data loss with contrast to under-sampling. We also tried outlier removal in under-sampling but we got better results without removing outliers. We did not try outlier removal in over-sampling because it takes more than 10 minutes to run. Outlier removal may give better results in over-sampling but there is always risk of losing significant information in our dataset.

### Earthquake Prediction in Turkey with LSTM Model
**Code:** [`earthquake_prediction_in_turkey`](https://medium.com/@emrahmetu/earthquake-prediction-in-turkey-with-lstm-model-327df0761e4)    
**Project:** [`my_project_slides.pdf`](https://docs.google.com/document/d/1zeLCcMfMLQQ-ttNTQQBWva6gCMx6iDsc/edit)   
**Description:** Turkey has had an observatory called Kandilli Rasathanesi since 1894 and it was connected to Bogazici University in 1982. During the 31 March Case in 1909, Kandilli Observatory and Earthquake Research Institute was destroyed, and it was reconstructed in 1910. The purpose of this paper is to review the seismicity in Turkey for the period 1910–2017 by using historical data observed by Kandilli Observatory and Earthquake Research Institute and predicting the earthquake by Long Short Term Memory which is a time-series data analysis method.
**Skills:** data cleaning, detecting data anomalies, python coding, data visualization, descriptive statistics, dealing with outliers, Shapiro–Wilk test, data transforms   
**Technology:** Python, Pandas, Numpy, lstm, Seaborn, Matplotlib, Statsmodels Stats, R programming, preprocessing, exploratory analysis   
**Conclusion:** When we check the past data, we concluded that most of the earthquakes have been occurred in northwest and southwest. LSTM that we applied to our data also predicts by looking at the past time series that most of the earthquakes will be in the western areas. 

### Violent Crimes in USA Communities
**Article:** [`notebook.ipynb`](https://medium.com/@emrahmetu/violent-crimes-in-usa-communities-b37923038172)      
**Summary:** Understanding where violent crime occurs may be a gateway to understand why it does occur. Environmental, socioeconomic and demographic factors may be important predictors of a society’s level of violent crime. Determining which ones are most prominent on the level of violent crime would provide useful insight to community design, economic growth and policing. The purpose of this paper is to examine and explore the predictors of ‘murder’ crimes committed in the United States, compare models using appropriate predictors to predict ‘murder’ and explain pros and cons. Data of communities and crimes was taken from the UCI Dataset Repository.
**Skills:** Shapiro-Wilk, Test for Skewness, Linear Regression, Decision Tree Regression, Random Forest Regression, data cleaning, data anomalies detection
**Technology:** Python, Pandas, Numpy, Scipy Stats, Seaborn, Matplotlib, Statsmodels Stats.   
**Conslusion:** The most significant factors influencing violent crime rates are increase in the percentage/number of kids born to people who never married, decrease in the percentage of Caucasian population, increase in the percentage of African-American population, decrease in the percent of kids of age 12–17 in two-parent households, decrease in the percent of kids 4 and under in two-parent households.

### Online Advertising Campaign Analysis
**Code:** [`ya_ad_int_solution.ipynb `](https://github.com/nktnlx/side_projects/blob/master/6_ya_ad_internship/ya_ad_int_solution.ipynb)    
**Presentation:** [`ya_ad_int_slides_upd.pdf`](https://github.com/nktnlx/side_projects/blob/master/6_ya_ad_internship/ya_ad_int_slides_upd.pdf)    
**Description:** My submission to Yandex Advertising Analytics internship program.    
**Skills:** data cleaning, CTR, CPC, CPA and CR calculation, comparing metrics with competitors, visualizing results, drawing conclusions.    
**Technology:** Python, Pandas, Numpy, Seaborn, Matplotlib.     
**Results:** the slide deck with online advertising campaign analysis and recommendations on how to improve based on the service category. 

### Airbnb Listings Analytics 
**Tableau Public:** [`dashboard`](https://public.tableau.com/app/profile/nktn.lx/viz/LondonAirbnbListingsAnalyticalDashboardpractice5/Dashboard1)    
**Dashboard canvas:** [`dashboard_canvas.pdf`](https://github.com/nktnlx/data_analysis_course/blob/main/32_airbnb_listings/dashboard_canvas.pdf)   
**Description:** Tableau Public dashboard consisted of: calculated renting property occupation rate; analytical chart to choose the best property by occupation rate, review score and price per night; a ranked table of top listings by calculated potential annual revenue; average price, average occupation rate and a number of unique listings KPIs; filters by neighborhood, occupation rate and a number of reviews per the last twelve month.    
**Skills:** interview with a customer, requirements capture, designing an analytical dashboard, product delivery.    
**Technology:** Tableau.    
**Results:** created an analytical dashboard to support daily activities of a company involved in apartments renting business. 

## Study Projects
In this section I will provide links to my github repositories containing code and jupyter notebooks I created while passing online courses or was just having fun with.

### sklearn ML course
**Description:** Machine Learning in Python with scikit-learn by France Université Numérique. [The course official page](https://www.fun-mooc.fr/en/courses/machine-learning-python-scikit-learn/).  
This 3 month course is an in-depth introduction to predictive modeling with scikit-learn. Step-by-step and didactic lessons introduce the fundamental methodological and software tools of machine learning, and is as such a stepping stone to more advanced challenges in artificial intelligence, text mining, or data science.  
**Repository:** Check the repository having jupyter notebooks with the course lectures and tasks' solutions ---> [go to repo..](https://github.com/nktnlx/sklearn_ml_course)  
**Status:** Completed in May 2022 (please, check the certificates section below).  

### Kaggle 30 Days of ML
**Description:** 30 days of Machine Learning by [Kaggle](https://www.kaggle.com/thirty-days-of-ml). The course rapidly covers the most essential skills needed to get hands dirty with data and quickly learn how to build machine learning models.  
**Repository:** Check the repository having jupyter notebooks with the course tasks' solutions ---> [go to repo..](https://github.com/nktnlx/kaggle_30_Days_of_ML)  
**Status:** Completed in August 2021 (please, check the certificates section below).    

### Data Analyst Specialization
**Description:** This is a 5 month specialization by [karpov.courses](https://karpov.courses/analytics). The specialization includes Python, API, Git, Airflow, SQL, Statistics, A/B testing, Visualization, Product development and Product Analytics modules.  
**Repository:** Check the repository having 37 data analysis mini-projects ---> [go to repo..](https://github.com/nktnlx/data_analysis_course)  
**Status:** Completed in July 2021 (please, check the certificates section below).  

### Data Analysis Course Tinkoff-MSU
**Description:** This is a 3 month course by [Tinkoff Education](https://fintech.tinkoff.ru/study/academy/analysis/). The course was created for Moscow State University Faculty of Mechanics and Mathematics students and includes following topics: Introduction to Data Analysis, SQL, Data Visualization in Python, A/B tests, Data Interpretation, Models, Logistic regression, Mobile Analytics, Random Forest, etc..  
**Repository:** Check the repository having my code and solutions for home-tasks and projects of the course ---> [go to repo..](https://github.com/nktnlx/data_analysis_tinkoff_msu)  
**Status:** Completed in May 2021 (please, check the certificates section below).   

### Learning SQL
**Description:** SQL queries for tasks from [codecademy](https://www.codecademy.com/learn/learn-sql), [sql-ex.ru](https://www.sql-ex.ru/?Lang=1), [stepik](https://stepik.org/course/63054/syllabus), [sql module on Yandex Praktikum](https://praktikum.yandex.ru/data-analyst/), etc.      
**Repository:** Check the repository having 400+ SQL queries ---> [go to repo..](https://github.com/nktnlx/learning_SQL)  
**Status:** Some of the courses are still in progress.  

### Python Developer Track
**Description:** 25 projects, 154 hours, 300 topics python developer track from [JetBrains Academy](https://hyperskill.org/tracks/2)  
**Repository:** Check the repository having 11 completed projects including: Hangman, Tic-Tac-Toe, Rock-Paper-Scissors games; Matrix calculator, own-coded Regex engine, To-Do list, etc. ---> [go to repo..](https://github.com/nktnlx/jetbrains_python_developer)  
**Status:** Completed 11 projects, studied 116 topics from the track to practice my python skills. Will revert back to the track later.  

### Computer Science Career Path
**Description:** 20 weeks Computer Science Career Path from [Codecademy](https://www.codecademy.com/learn/paths/computer-science). The career path includes following topics: command line commands, git, python 3, OOP, linear data structures, complex data structures, asymptotic notation, recursion, sorting algorithms, search algorithms, graph search algorithms.  
**Repository:** Although the career path has been already completed the repository is still under development, having only 9 listed projects including: words statistics calculator, English nouns pluralizer, English verbs conjugation, censor engine, etc. ---> [go to repo..](https://github.com/nktnlx/cs_path_codecademy)  
**Status:** Completed in July 2020 (please, check the certificates section below).  

### Google Python Class
**Description:** This is a free class for people with a little bit of programming experience who want to learn Python by [Google](https://developers.google.com/edu/python). Topics covered: strings, lists, sorting, dicts, files, regular expressions, utilities, urllib.  
**Repository:** Containing 10 cool projects including: mimicking random text generator, baby-names popularity counter (based on data from The Social Security administration US), etc. ---> [go to repo..](https://github.com/nktnlx/google_python_class)  
**Status:** Completed in November 2020.  

### Side Projects
**Description:** Side projects and various code snippets I'm having fun with.  
**Repository:** pull-ups ladder calculator, motivational bad habits tracker, my solutions to coding problems for Tinkoff Fintech Junior / Tinkoff Internship admission tests, applications to internships, [Google Sheets Course by Yandex Praktikum](https://practicum.yandex.ru/excel-for-work/), etc. ---> [go to repo..](https://github.com/nktnlx/side_projects)  
**Status:** ∞  

### Tableau Vizzes
**Description:** My Tableau Public account ---> [go to Tableau..](https://public.tableau.com/profile/nktn.lx#!/)  
**Status:** ∞  

## Certificates

List of certicates:

- [Google Data Analytics Certificate]( https://www.credly.com/badges/b6de9b8a-5d3f-4991-9768-a5f0e0c813c8?source=linked_in_profile) (June 2022) 
- [ACL Audit Tool Training]( https://www.wegalvanize.com/) (July 2020) (Galvanize)
- [Machine Learning A-Z]( https://cci.udemy.com/certificate/UC-fbf17660-569a-4692-9230-46f1ab4ad1de/) (May 2020) (SuperDataScience)
- [SQL Bootcamp]( https://cci.udemy.com/certificate/UC-0e7e6c99-fee1-4a89-bf13-bac37e65e8cf/) (May 2020) (Udemy)
- [Apache Spark with Scala]( https://udemy-certificate.s3.amazonaws.com/pdf/UC-aa9da56c-87b9-4f11-a88c-87c748f72b5f.pdf) (April 2020) (Sundog Education)
- [Automate the Boring Stuff with Python Programming]( https://udemy-certificate.s3.amazonaws.com/pdf/UC-52fc4dbb-bcf4-4e25-99c1-9e55fc555846.pdf) (April 2020) (Udemy)
- [Python Bootcamp]( https://www.udemy.com/certificate/UC-050822ea-9d08-438f-b3d1-6030ba83d632/) (April 2020) (Udemy)
- [Data Science A-Z]( https://cci.udemy.com/certificate/UC-de1a3148-c438-4ef9-96fe-39bd55b9ac8e/) (April 2020) (SuperDataScience)
- [ISO/IEC 27001 Information Security Management System]( https://udemy-certificate.s3.amazonaws.com/pdf/UC-65ef5ebf-e160-467c-a4c4-9a673c45b109.pdf) (April 2020) (RIGCERT)
- [Python A-Z]( https://cci.udemy.com/certificate/UC-8fdc1ee2-43f8-4b66-9dd8-41257f906117/) (April 2020) (SuperDataScience)
- [R Programming A-Z]( https://cci.udemy.com/certificate/UC-bf03cb49-5cac-4079-97c5-c07b8d4d2b38/) (April 2020) (SuperDataScience)
- [Data Science Foundations: Fundamentals]( http://www.linkedin.com/learning/data-science-foundations-fundamentals-5) (March 2020) (Linkedin)
- [Excel Macros in Depth]( https://www.linkedin.com/learning/excel-2016-macros-in-depth/welcome?u=85583354) (Jan 2019) (LinkedIn) 

## Contacts
- LinkedIn: [@emraydin]( https://www.linkedin.com/in/emraydin/)
- Twitter: [@elbruzconsult]( https://twitter.com/elbruzconsult)
- E-mail: emrahmetu@gmail.com

