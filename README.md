# Analyzing Media Bias in Defense and Foreign Affairs: A Deep Learning and eXplainable Artificial Intelligence Approach

In this paper, to gain a more detailed understanding of whether it is possible to distinguish biases through news articles or differentiate media outlets themselves, we collected an extensive amount of news articles spanning over five years. To efficiently analyze this vast amount of data, we applied machine learning techniques.

RQ1: Can we accurately classify the political orientation of news articles focusing on national defense and foreign policy topics?

RQ2: How effective is the LIME model in identifying the key features driving the classification of political orientation and in detecting temporal shifts in media bias across different periods?


# Data

For data collection, we crawled entire articles posted in the subcategories of diplomacy/defense within the politics section of the following news sources. To ensure a balanced collection across conservative and progressive administrations, the data collection period was set from January 1, 2017, to February 25, 2024. The total collected dataset amounted to 510,398 articles. After undergoing various preprocessing steps, we utilized a final set of 42,350 conservative and 16,929 progressive articles.

The sample dataset is available in "news crawling data(sample).xlsx" file. We are only allowed to distribute the data for the research purpose, if you want to achieve full datasets, please complete the request form @ https://docs.google.com/forms/d/e/1FAIpQLSc72tNn4QPWYXRcUOv6D8E6zzR0a4IHCS_Qo0Z9NYfkrxw6dw/viewform?usp=sf_link

# Result
- **Result of Learning Rate Test (1e-5 to 7e-5)** 
 
   ![image](https://github.com/user-attachments/assets/ce658573-1a0b-441b-93d9-7a8260edb109)
  

- **Result of Epochs Test (1 to 10)**
     
   ![image](https://github.com/user-attachments/assets/8a4f9716-15ee-4aa0-bbfb-0473ef45ab79)


- **Word Clusters of top most frequently shown XAI weighted feature words. The red color samples indicate conservative and the blue liberal**

   ![image](https://github.com/user-attachments/assets/8d40b7fd-b099-44a0-9002-7b22968c4572)


## Reference
```
@article{
}
```
