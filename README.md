# Data-analytics-project
This is my take on the Google data analytics capstone project. I will be following its guidelines except that the project I decided to work on isn't necessarily business related. **Note that** this is my first project and first GitHub contribution. 

# Scenario
The final project of my psychology class in university was suggesting a hypothesis and gathering data to validate or invalidate it. Since the sample size was insufficient and the data was confined to a small geological area, I found the Google data analytics capstone case study to be a great opportunity to develop the project by adding public data to be analyzed, consequently (hopefully) gaining valuable insights from both data sources and also from comparing them side by side. 

# Ask 
In this part of the project we will be establishing a solid foundation foundation and addressing the key factors essential for the study.Achieving this will be done n by answering the four following questions:  
[1. what is the topic to be investigated?](#the-topic)  
[2. Who is the target audience?](#the-audience)  
[3. what dataset is being analyzed?](#the-dataset)  
[4. what are the metrics to be used?](the-metrics)  

### The topic
The hypothesis being tested is **Religiosity positively correlates with age". This suggests that as individuals grow old, their level of religiosity rises, excluding those who aren't old enough to form independent opinions and worldviews even if the trend still holds for them.  
investigating this hypothesis can help us uncover and understand societal trends regarding the dynamics of religiosity in different age groups over time.  

### The audience
The findings of this case study can benefit a number of entities and individuals mainly:  
**Academic researchers:** This study can serve as a basis for further academic research, contributing to the body of knowledge in fields such as sociology, psychology, and religious studies.  
**Advertisers:** Marketing algorithms can be designed with this correlation in mind helping market researchers, advertisers and corporations reach the right demographic consequently improving sales and user satisfaction.

### The dataset
To reach our objective we will use the following two datasets:  
**Dataset1**: For the previously mentioned phsycology project my colleague and I conducted an observation at a local mosque and at a local church during peak prayer time (mosque: Friday/ church: Sunday). We recorded the age of the attenders in the period of one day. you can find the raw data in the [raw-data-1](https://github.com/ChristianAkrouche/data-analytics-project-/blob/main/Raw-data-1.xlsx) file.
**dataset2**: The second data set to be used in this study is a public dataset sourced form the office for national statistics.This dataset, derived from the 2021 Census in England and Wales, offers insights into the religious affiliations of residents. It categorizes individuals into different religious groups, including "No religion," and accommodates those who didn't respond to the question.

### the metrics 
To reach our goal and get useful insights from our data, metrics will be used such as:  
1.Scatter plot: A scatter plot is an excellent choice when visualizing the relationship between two continuous variables, such as age and religiosity.  
2.line chart: A line chart displays data points as dots connected by lines. It's often used to visualize trends over time. It will be use to test how religious attendance changes with age.  
3.Pearson's correlation coefficient: It is statistical measure that quantifies the strength and direction of the linear relationship between two continuous variables. This will be used to test the correlation between age and religiosity.

# Prepare
In this part of the study we will be testing the credibility of each data source, to achieve this we will be checking if the data **ROCC**s, meaning **R**eliable, **O**riginal, **C**omprehensive, **C**urrent and **C**ited.  
  
**Dataset1:**  
❌Reliable: The data is unbiased, but it has a small sample size meaning it may not accurately represent the broader population or phenomenon being studied.    
✔️Original: That data was gathered by my colleague and I, meaning it is first-party data.  
✔️Comprehensive: The data contains the needed information in the context of this study.  
✔️Curent: The data is recent (2022).  
✔️Cited: The data is cited    
  
**Dataset2:**  
✔️Reliable: The data is unbiased and has a large sample size making up for the first dataset.  
✔️Original: The data is data sourced from the Office for National Statistics (ONS), this would be considered second-party data.  
✔️Comprehensive: The data contains the needed information in the context of this study.  
✔️Curent: The data is recent (2021).  
✔️Cited: The data is cited(Office for National Statistics (ONS)), which is a trusted and well-known organization.  

# Prepare 
Now that we got a clear idea of the data we are working with, the next step is cleaning and transforming the data to align with the requirements of our data. It's important to note that we won't be editing the actual content of the data. To ensure transparency, we will thoroughly document the entire process, allowing you to view both the raw data before any modifications and the final result after our transformations are applied.  
**Dataset1:**  
The process can be found in this file: [transformed data 1](https://github.com/ChristianAkrouche/data-analytics-project-/blob/main/transformed%20data1.xlsx)  
**Dataset2:**  
This could have been replicated using BigQuery but the transformation procces was very simple and better done in the spreadsheet.  
the process can be found in this file: [transformed data 2](https://github.com/ChristianAkrouche/data-analytics-project-/blob/main/transformed_data_2.xlsx)

# Share
The subsequent phase involved harnessing the power of Tableau to craft compelling visualizations that would unveil the narrative hidden within the data. Raw numbers were transformed into vibrant insightful displays:  
  
### religious attendance by age: ![dataset_1 age_religious attendance (l1 church,1 mosque)](https://github.com/ChristianAkrouche/data-analytics-project-/assets/130599572/27ffe357-b6bf-4c79-8d96-59c882361fb7)


### religiosity according to age,England and whales,2021:![dataset_2  age _religiosity](https://github.com/ChristianAkrouche/data-analytics-project-/assets/130599572/96e57783-ce91-40e3-9a99-8099248fbcd7)


