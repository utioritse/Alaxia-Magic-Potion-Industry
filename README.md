# Alaxia-Magic-Potion-Industry
An overview of the magic potion industry in the fantasy land of Alaxia

## Background
While looking for a small dataset to practice with, I generated one based on the industry of a fantasy land. The dataset, provided in a [CSV file](https://github.com/utioritse/Alaxia-Magic-Potion-Industry/blob/main/Magic_Potions_Industry.csv), showcases potion data from five regions: Dragonspire, Enchanted Forest, Golden Hills, Mystic Falls, and the Shadowlands. The data further categorizes potions by type, main ingredient, price, production cost, seasonality, age groups, and customer ratings. Further analysis was done with [Python](https://github.com/utioritse/Alaxia-Magic-Potion-Industry/blob/main/Alaxia.ipynb).

## Objective
To provide a comprehensive analysis of the Alaxia potion market, highlighting sales trends, customer demographics, seasonal demand, and regional distribution. This dashboard aims to enable data-driven decisions for optimizing production, marketing strategies, and enhancing profitability across the potion industry.

![Dashboard](Alaxia%20Dashboard.png)

## Key Insights 
- Dragon Healing Potion is the highest-selling potion across all five regions.
- Stealth potions are very popular among young people.
- Enhancements are also very popular among people ages 41-60. 
- The Shadowlands is the region with the most activity.
- Potion vendors retain only 21% of the industry's revenue due to high production costs.
- Healing and Combat type potions are the most popular across all regions.
- Fire Resistance Potion has the highest average customer rating across the five regions, because who wouldn't be happy with being resistant to fire?

## Further Drilling
### Leveraging the interactive features of the dashboard, I explored deeper insights into potion sales and regional trends.
#### Fire Resistance
Using the region slicer, we learn that Fire Resistance Potion is sold mostly in Golden Hills, which suggests a bombardment of fire-based attacks in the region. The potion's average rating also falls to the mid-range, as frequent and consistent use by customers draws harsher criticism. 

![Fire Resistance](Fire%20Resistance.png)

![Fire Resistance 1](Fire%20Resistance%201.png)

#### Dragon Breathing Potion 
The highest-selling potion in Alaxia sees its sales peak in the summer. It's a versatile potion mainly used for Healing, Enhancement and Combat. All these factors would suggest a lot of fighting during summer.

![Dragon Breath](Dragon%20Breathing%20Potion.png)

## Python 
python
''' 
'''#importing the pandas library
import pandas as pd
#getting a general understanding of the database
potions = pd.read_csv('Magic_Potions_Industry.csv')
print(potions.columns)
potions.head()
print(potions.isnull().sum())
'''


## Recommendations
- Due to high production costs, the industry needs to find a way to imbibe efficiency to improve profit.
- Other potion types could be introduced to entice young people, including teleportation, flight etc.
- Demand for potions in the Shadowlands and Enchanted Forest is strong, so investors should focus their attention in those regions. 
