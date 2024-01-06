# RFM-Analysis-Python
<p align="center">
<img src="https://raw.githubusercontent.com/phonixt12/RFM-Analysis-Python/main/images/Incontent_image.png" align="center" width="800" height="450" >

# Definition of RFM analyis
RFM is an acronym representing recency, frequency, and monetary value, wherein each component correlates with crucial customer attributes. These RFM metrics serve as significant indicators of customer behaviour, as frequency and monetary value directly impact a customer's lifetime value, while recency influences retention, a metric reflective of engagement

# The benefit of RFM analysis
Businesses without a direct monetary component, such as those focused on viewership, readership, or surfing-oriented products, may opt for engagement parameters in lieu of monetary factors. This adaptation results in the utilisation of RFE, a variant of RFM. Moreover, the engagement parameter can be delineated as a composite value derived from metrics such as bounce rate, visit duration, number of pages visited, and time spent per page, among others.

The RFM factors underscore the following insights:

The recency of a purchase positively correlates with the customer's responsiveness to promotions. A higher frequency of customer purchases indicates increased engagement and satisfaction. The monetary value serves as a distinguishing factor, delineating heavy spenders from low-value purchasers

# The Case Study
This case study was used to demonstrate my skill in Python. In this case study, the business's condition is analysed by the author using a dataset. The author will give some views about the business's situations and give insight and solutions. This is the link to the case study : [Link](https://github.com/phonixt12/RFM-Analysis-Python/blob/main/RFM%20analysis%20.ipynb)  and the link of data : [Link](https://github.com/phonixt12/RFM-Analysis-Python/blob/main/ecommerce%20retail.xlsx)

# I.Introduction 
**1.Business need**
 "SuperStore Company is an international retailer." Consequently, the business has numerous consumers.
In recognition of the upcoming holidays and the new year, the Marketing Department intends to execute promotional campaigns to express gratitude to customers for their continued support. In addition to capitalising on consumers who possess the capacity to develop loyalty.

As the data set is too large to be processed manually as in previous years, the Marketing Department has been unable to classify each consumer this year. As a result, we requested the Data Analysis Department's assistance in implementing a classification problem. Segment each consumer in order to implement the most appropriate marketing programme for each customer group.

Additionally, the Marketing Director recommended implementing the RFM model; however, during the company's earlier stages of development, the team has the capability to compute and categorise it using Excel. At present, the volume of data exceeds our capacity; therefore, we request that the Data Department develop a Python programming flow to implement segmentation evaluation
**2. Dataset**

Dataset includes 2 different related tables including: transaction informatio from 2010 to 2011 and RFM classification

**Transaction information dataframe**

![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/ba97694f-71b2-43a4-bb2b-d949a8f6bed8)


![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/706c194f-1667-4380-8bfd-ebe01b64933a)
**Segmentation dataframe**
![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/bd683489-b903-49d1-b60b-4fe761b9e9a4)
![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/2dc71000-55ef-49bc-be9c-e268975248fb)


![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/fcf3c80b-6d86-4b7a-8008-85ccf77f777f)
![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/515a442d-55cb-4524-ba28-534254fd420d)


![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/af2fcadd-75d5-41db-8554-030688c99af5)
![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/5e1b6ef8-77e0-497a-ad50-dd8e2bac771e)

![image](https://github.com/phonixt12/RFM-Analysis-Python/assets/139587231/6a079af8-4aa1-4179-b79a-316b781cd9c4)

**3 .Insight and recommandation** 
**Insight**

The data presented in the table reveals a notable high mean value for Recency, indicating that customers are inclined to discontinue their association with Superstore in the future. Conversely, there is an absence of positive signals in Frequency, with a mean value of 4.3, falling below the normal range, and a median of 2, signaling a significant concern for SuperStore. Despite these challenges, the Monetary aspect exhibits a positive side, with a mean value exceeding 2000

The charts illustrating revenue and customer distribution across segments highlight that the Champions group, constituting 19.15% of the customer base, contributes more than 60% of the revenue. Following closely in revenue are the Loyal and At-risk groups, contributing 12% and 8.2%, respectively. However, Hibernating and Lost customers account for 16.4% and 13.1%, respectively, yet purchase fewer types of products, at 3.3% and 1.4%, respectively. The Need Attention group, comprising 5% of revenue, represents only 6.2% of total customers, necessitating special attention

Examining the chart depicting customer segments, it is evident that the Championship group constitutes the largest portion at around 60%, signifying that Superstore possesses a considerable number of loyal customers

The revenue chart underscores the significance of the Championship and Loyal groups as the highest contributors to the store's earnings

The division of other customer groups into potential and in-danger categories reveals opportunities and risks. Potential customers include Hibernating customers, potential loyalists, promising, and new customers

**Recommendation**

To address these insights, it is imperative for Superstore to concentrate efforts on increasing both Recency and Frequency values. This strategic focus will likely contribute to customer retention and overall store performance

Superstore should focus efforts on engaging with the Need Attention group, understanding their preferences, and implementing strategies to enhance their contribution to both revenue and overall customer satisfaction

To maintain this strong customer base, Superstore should implement targeted marketing campaigns, such as personalized offers, exclusive discounts, and special services, to reinforce the loyalty of the Championship group

Superstore should implement marketing campaigns tailored to the Championship and Loyal groups, focusing on strategies like birthday gifts, new product experiences, discounted offerings, and personalized customer care to strengthen their loyalty

For potential customers, Superstore should introduce a loyalty program, engage actively on social media, and encourage customer referrals. In contrast, in-danger customers should be identified and rewarded for their value, while feedback should be actively sought and utilized for continuous improvement

**Finally**

In conclusion, Superstore should personalize marketing messages, provide exclusive benefits to loyal customers, and implement targeted strategies for potential and in-danger customer groups to enhance overall customer satisfaction and store performance
