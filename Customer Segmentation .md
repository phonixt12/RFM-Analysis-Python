**Customer Segmentation** :  involves the systematic grouping of customers based on shared characteristics. It will support in marketing campagain , including targeted campaigns, and the cultivation of customer loyalty. Companies typically segment their customerin some metrics : encompassing demographics (such as age, gender, and location), behavior (including past orders and responses to messaging), and psychographics (involving values, interests, and lifestyles) 

**RFM (Recency-Frequency-Monetary)** analysis is a technique for behavior-based customer segmentation. This method involves grouping customers according to their purchasing records, specifically considering how recently, how frequently, and how much they have made purchases. RFM is a useful tool for identifying and understanding the behavior of the most valuable customers. 
```
#Import library 
import pandas as pd
import datetime as dt
import seaborn as sns
import matplotlib.pyplot as plt
!pip install squarify
import squarify as sq

#Get data from excel
eco = pd.read_excel('C:/Users/phoni/Downloads/Final_project_RFM/Final_project_RFM/ecommerce retail.xlsx', sheet_name='ecommerce retail')
seg = pd.read_excel('C:/Users/phoni/Downloads/Final_project_RFM/Final_project_RFM/ecommerce retail.xlsx', sheet_name='Segmentation')
```
