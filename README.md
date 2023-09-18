# Data-analytics-project
This is my take on the Google data analytics capstone project. I will be following its guidelines except that the project I decided to work on isn't necessarily business related. **Note that** this is my first project and first GitHub contribution. 

# Scenario
The final project of my psychology class in university was suggesting a hypothesis and gathering data to validate or invalidate it. Since the sample size was insufficient and the data was confined to a small geological area, I found the Google data analytics capstone case study to be a great opportunity to develop the project by adding public data to be analyzed, consequently (hopefully) gaining valuable insights from both data sources and also from comparing them side by side. 

# Ask 
In this part of the project we will be establishing a solid foundation and addressing the key factors essential for the study.Achieving this will be done n by answering the four following questions:  
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
  
### religious attendance by age:   
![dataset_1 age_religious attendance (l1 church,1 mosque)](https://github.com/ChristianAkrouche/data-analytics-project-/assets/130599572/27ffe357-b6bf-4c79-8d96-59c882361fb7)

### religiosity according to age,England and whales,2021:   
![dataset_2  age _religiosity](https://github.com/ChristianAkrouche/data-analytics-project-/assets/130599572/96e57783-ce91-40e3-9a99-8099248fbcd7)

It was clear that both datasets followed strikingly similar tragectories. Religiosity had a consistent pattern of growth reaching its peak in late adultery. However it then took a descending trajectory in old adultery(reasons will be discussed in next phase).
The positive correlation  between age and religiosity was especially seen in the adult age group, which serves the most important point in our analysis. The following graphs bellow illustrate this phenomenon:  
![Adults_dataset1](https://github.com/ChristianAkrouche/data-analytics-project-/assets/130599572/5c7a120b-4090-441b-af44-47fc01e1fbd2)

![Adults_dataset2](https://github.com/ChristianAkrouche/data-analytics-project-/assets/130599572/e7142f51-04cd-4cd2-8354-86c9f2d46f39)

#### Pearson's correlation coefficoent
This is a measure of the linear relationship between two continuous variables. It ranges from -1 to 1, where -1 indicates a perfect negative linear relationship, 1 indicates a perfect positive linear relationship, and 0 indicates no linear relationship.
this calculation was done on the adult group in dataset 2, and the answer was 0.9812  This value indicates a strong positive linear relationship between the two variables. **Please note that correlation doesn't always mean causation**, social and individual reasons should be investigated to insure the causation.

# Act 
**Conclusion:**
The present study provides support for the hypothesis that people become more religious as they get older. This finding is consistent with previous research, which has suggested that age is positively related to religiosity (Hill & Pargament, 2008; Levin et al., 1994). There are several possible explanations for this relationship here are two:

1.	Existential Theory: People become more religious as they age because they get more aware about their mortality and in turn will begin searching for meaning . And in this search they will find  religion as a source of comfort and support in their lives .  A study by Koenig et al. (2012) found that older adults who were more religious had better psychological well-being, this suggest that religion serves as a coping mechanism for  life problems and stressors

2.	Socialization and Life Changes:Social factors,external motivators and major life changes, such as retirement or loss of a spouse, can lead people to seek  religiosity. According to this view, individuals facing difficult and stressing times may turn to religion as a source of social support and comfort. A study by Krause (2006) found that individuals who experienced negative life events, such as the death of relatives and  chronic health problems, were more likely to increase their religious participation.

Please note that these  are only thought after speculation regarding the reasoning behind this hypothesis. To delve deeper into this subject and gain a more profound understanding, further studies employing a more philosophical and psychological approach should be undertaken.

Finally, it was notable that the trend did not appear to apply to those of very advanced age, this can be due to to health-related factors that may render them physically incapable of participating in religious activities, as well as cognitive impairments that could hinder their engagement.



