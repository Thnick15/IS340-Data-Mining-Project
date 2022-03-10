# IS340-Dataset-Wine-Reviews
Business Application Programming (Python)

<h2 align="center">IS 340 Python Data Mining Project</h4>

<h4 align="center">California State University, Long Beach</h4>

<h4 align="center">Spring 2018</h4>

<h4 align="center">IS 340 - Business Application Programming</h4>

<h3 align="center">Dataset: Wine Reviews</h4>

<h5 align="center">Team G4:</h5>
<h5 align="center">Isam Muwanas 012004913</h5>
<h5 align="center">Nicholas Pickens 016248425</h5>
<h5 align="center">Sebastian Torres 016220202</h5>
<h5 align="center">Kathleen Tran 015023747</h5>

Link to dataset: https://drive.google.com/file/d/1TST3JYL5bmE7aCowDEvqvR_mOtxUBsXT/view?usp=sharing

<h4 align="left">Data</h4>

In this report, we draw insights by analyzing textual, numerical, and string data through the use of programming concepts and text-mining methods from a dataset of wine reviews. The dataset has approximately 130,000 records of wine reviews, with columns consisting of the country, description, designation, points, price, province, region, variety, and winery. Country shows where the wine is from. The description describes the wine’s taste, smell, look, feel, and so on. Designation is the vineyard within the winery where the grapes that made the wine are from. Points uses a scale of 1 to 100; however, wine reviews used in our dataset are only greater than or equal to 80. 80-89 is described as a very good wine with special qualities, 90-95 is an outstanding wine of superior character and style, and 96-100 is considered to be a classic and a great wine. Price is the cost for a single bottle of wine. Province is the area the wine is from. Region is to specify to a greater extent as to where the wine is from. Variety is the type of grapes that were used to make the wine. Lastly, winery is the establishment of where the wine was created. Given the columns of the dataset stated above, the variables used in our program are wineCountry, wineProvince, winePoint, winePrice, and wineDescript. 

<h4 align="left">Problem</h4>

Wine is an alcoholic beverage that has been around for centuries. Within every bottle is a history and science.  Some of the problems we are trying to solve are which country has the highest rated wine, the lowest rated wine, and if there is a correlation between the rating (wine points) and the price variable of wines. This is important because it will help us narrow down and gain an insight about the wine data. We have found the wine with the highest rating. This can be helpful for customers to help them choose the best wine. Our group has found the wine with the lowest rating. This data is significantly helpful because it can help wine companies know how they are doing in the wine market. They can find ways for improvement so their wine reflects the wine score. In this project, we examine the relationship between the points and the price. We used the 100-Point Wine Scale as a benchmark to determine the quality of wines in the wine industry. It is normally considered the basic scale by how critics rate wine. 

<h4 align="left">Analysis</h4>

With the variables selected, we used wineCountry and winePoint in a dictionary to find the following for each country: average points, highest rated, and lowest rated. In addition, a similar procedure was performed for wineProvince and winePoint to find the following for each province: average points, highest rated, and lowest rated. For structured data, statistical analysis was performed on the variables winePoint and winePrice to find the maximum, minimum, average, mode, median, range, and standard deviation. The description of wines were used for unstructured data, where sentiment analysis was conducted to find the maximum, minimum, average, rage, and standard deviation  sentiment values. Our team has determined there is a correlation between two variables: the description and points. We want to find the correlation to show which brands have the highest points compared to the best description. Using Matplot Library, we tested the correlation between the following: Price vs. Point, Rating Sentiment vs. Points, and Sentiment vs. Price.

<h4 align="left">Results</h4>

Through our analysis conducted on our variables used, we were able to yield significant results. With much surprise, it was discovered that the highest rated country was Britain with 91.55 points and Peru with the lowest of 83.56 points. Whereas, when it came to provinces, the highest rated was Austria, Burgenland with a rating of 94 points. In the statistical analysis of the points data, the results showed a maximum: 100, minimum: 80, average: 88.42, mode: 88, median: 88, range: 20, and standard deviation: 3.04. In reference to the price data, it revealed a maximum: $3300.00, minimum: $4.00, average: $35.36, mode: $20, median: $25, range: $3296, and standard deviation: $41.02. Lastly, for our sentiment analysis on the description data, the analysis provided a maximum: 1.00, minimum: -0.80, average: 0.16, range: 1.80, and standard deviation: 0.17. 

<h5 align="left">Points vs Price</h5>

![image](https://user-images.githubusercontent.com/101357023/157771549-8d0b7cc5-7a42-4944-8bac-29f45e93aed4.png)

In the graph above that we have conducted, there is a correlation (relationship between two variables) between the wine points and price. The x-axis stands for the price of the wine and the y-axis stands for the points of the wine. A higher priced wine would usually associate with being high quality and therefore have high points. But in this case, the most expensive wine here did not have a high score. The price of the wine is too expensive for people to afford and that means not everyone gets the chance to taste it. We found that there is little correlation for wine bottles under $500.00 with correlation observed after the point rating passes the 95 point mark and that is as the point rating rises the minimum price of the wine also increases. For wine that costs more than $500.00 the lowest rated wine is around 87 points: So as the price increases the probability that the wine is going to be below average is extremely low. Note a significant outlier: $3200 dollar bottle of wine that is rated 88.00 which is slightly lower than average at 88.42.

<h5 align="left">Description vs. Points</h5>

![image](https://user-images.githubusercontent.com/101357023/157771607-623efb54-285b-4f14-a01b-8f597ca1c0ff.png)

In the graph above, there is a correlation between the wine description and the points.  The x-axis stands for the points of the wine and the y-axis stands for the description of the wine. As the rating passes the 95 point mark. The average sentiment is more neutral but this is likely resulting due to the fact only 805 of 130,000 reviews were rated higher than 95. Using sentiment analysis we are confident that the description of the wine has minimal effect over the rating of the wine.

<h5 align="left">Description vs. Price</h5>

![image](https://user-images.githubusercontent.com/101357023/157771663-cb0dcc83-b06e-4ab3-8f37-91ad18b473ac.png)

In the graph above, there isn’t a correlation between the wine description and price.  The x-axis stands for the price of the wine and the y-axis stands for the description of the wine. The final chart tests the correlation between the description and the price of the wine. While considering that there are only 91 wines that were $500.00 or more. Wines of that price point have a theme of using very positive descriptive words such as “Classic, Fabulous, Beautiful, Amazing” complemented with a description of the flavors While wines of 500 and less stuck to the description of the wines flavors and themes.

<h4 align="left">Conclusion</h4>

In conclusion, we have found that ratings can help customers find quality wine based on a certain country, description, point, or price. Our data showed that there is a correlation between the wine description and the price. Overall, we feel that our data can help the wine connoisseur in you make the right choice when picking a wine to consume. There’s a price to point correlation (to an extent). European wines tend to score higher. Sentimental value increase for the description is not based on the price but for the points awarded. We recommend the Charles Smith 2006 Royal City Syrah, Columbia Valley (WA): $80 considering the average Price of a 100 Point Wine to be $485.94.

<h4 align="left">Code</h4>

```
import csv
import json
from collections import OrderedDict
from statistics import *
from openpyxl import *
from textblob import TextBlob
import matplotlib.pyplot as plt
import numpy as np
from collections import defaultdict
import operator
#LISTS
countList=[]
descList=[]
pointList=[]
priceList=[]
sentList=[]
#Dictionaries with defaultdict allows us to have multiple values for duplicate keys
country=defaultdict(list)
province=defaultdict(list)
description={}
nameDict={}
#Open Excel
wineBook = load_workbook("wineData.xlsx")
sheet1 = wineBook.active
#Reads of Columns
wineCountry = sheet1["b1"].value
wineDescript = sheet1["c1"].value
winePoint = sheet1["e1"].value
winePrice = sheet1["f1"].value
wineProvince = sheet1["g1"].value
wineName = sheet1["l1"].value
#Adds Excel Data to List
for i in range (2,120976):
                
        wineCountry = sheet1.cell(column = 2, row = i).value
        wineDescript = sheet1.cell(column = 3, row = i).value
        winePoint = sheet1.cell(column = 5, row = i).value
        winePrice = sheet1.cell(column = 6, row = i).value
        wineProvince = sheet1.cell(column = 7, row = i).value
        wineName = sheet1.cell(column = 12, row =i).value
        province[wineProvince].append(winePoint)
        country[wineCountry].append(winePoint)
        descList.append(wineDescript)
        countList.append(wineCountry)
        pointList.append(winePoint)
        priceList.append(winePrice)
        #Collects all 100 point wines in the nameDict
        if winePoint == 100:
                nameDict[wineName]=winePrice     

#header message
print("Dataset name: Wine Reviews")
print()

#Calculates Sentiment Analysis for each review and add to a list
for i in descList:
        review=TextBlob(i)
        sentList.append(review.sentiment.polarity)
        description[i]=review.sentiment.polarity
        

###PRICE FUNCTIONS 
#function that determines highest price
def maxPrice(priceList):
        maxIndex = 0
        maxValue = float("-inf")
        for i in range (len(priceList)):
                if priceList[i]>maxValue:
                         maxIndex = i
                         maxValue = priceList[i]
        return maxValue
#function that determines the lowest price
def minPrice(priceList):
        minIndex = 0
        minValue = float("inf")
        for i in range(len(priceList)):
                if priceList[i]<minValue:
                         minIndex = i
                         minValue = priceList[i]
        return minValue
#function that determines the average price
def avgPrice(priceList):
        avg = mean(priceList)
        return avg
#function that determines standard deviation of prices
def sd(priceList):
        sd = stdev(priceList)
        return sd
#function that determines mode price
def modPrice(priceList):
        try:
             mod = mode(priceList)
             return mod
        except StatisticsError: #except if there is no mode
             return None
#function that determines median price
def mediPrice(priceList):
        medi = median(priceList)
        return medi
#function that determines the range of prices
def rangeCalc(priceList):
        return max(priceList) - min(priceList)

###POINT FUNCTIONS
#function that determines highest points
def maxPoint(pointList):
        maxIndex = 0
        maxValue = float("-inf")
        for i in range (len(pointList)):
                if pointList[i]>maxValue:
                         maxIndex = i
                         maxValue = pointList[i]
        return maxValue
#function that determines the lowest points
def minPoint(pointList):
        minIndex = 0
        minValue = float("inf")
        for i in range(len(pointList)):
                if pointList[i]<minValue:
                         minIndex = i
                         minValue = pointList[i]
        return minValue
#function that determines average points
def averagePoint(pointList):
        total = 0
        for i in pointList:
                total = total + i
                avg = total/len(pointList)
        return round(avg,2)
#funcion that determines the mode of points
def modPoint(pointList):
        try:
                mod = mode(pointList)
                return mod
        except StatisticsError: #except if there is no mode
                return None
#function that determines the median of points
def mediPoint(pointList):
        medi = median(pointList)
        return medi
#function that determines the standard deviation of points
def sd(pointList):
        sd = stdev(pointList)
        return sd
#function that determines the range of points
def rangeCalc(pointList):
        return max(pointList) - min(pointList)

###SENTIMENT FUNCTIONS
#function that determines the max sentiment value
def maxSent(sentList):
        maxSent = max(sentList)
        return round(maxSent,2)
#function that determines the min sentiment value
def minSent(sentList):
        minSent = min(sentList)
        return round(minSent,2)
#function that determines the standard deviation of sent list
def sdevFunc(sentList):
        total=0
        sumDiff=0
        n=len(sentList)
        #for loop calculates the mean of the sentList
        for i in sentList:
                total=total+i
                avg=(total/n)
        #for loop calculates the sum of the squared differences
        for x in sentList:
                sumX=(x-avg)**2
                sumDiff=sumX+sumDiff
        #Calculates the standard deviation of the sentList
        sde=(((sumDiff))/(n-1))**(1/2.0)
        return round(sde,2)
#function that determines the avg of description in sentlist
def averageDesc(sentList):
        return sum(sentList)/len(sentList)
#function that determines the range of sentiment
def rangeCalc(sentList):
        return max(sentList) - min(sentList)
#avgDict to get average points for each country
avgDict = {}
print("Below is the average points for each country: ")
print()
for wineCountry,winePoint in country.items():
        avgDict[wineCountry]= round(sum(winePoint)/float(len(winePoint)),2)
for wineCountry,winePoint in avgDict.items():
        print(wineCountry, "-", winePoint)

#avgProv to get average points for each Province
avgProv = {}
print("Below is the average points for each province: ")
print()
for wineProvince,winePoint in province.items():
        avgProv[wineProvince]= round(sum(winePoint)/float(len(winePoint)),2)
for wineProvince,winePoint in avgProv.items():
        print(wineProvince, "-", winePoint)

#numerical - structured data
print()
print("--- Points Data ---")
print("Highest Points:", maxPoint(pointList))
print("Lowest Points:", minPoint(pointList))
print("Average Points: %.2f" % averagePoint(pointList))
print("Mode of Points:", modPoint(pointList))
print("Median of Points: %.2f" % mediPoint(pointList))
print("Range of Points:", rangeCalc(pointList))
print("Standard Deviation Value of Points: %.2f" % sd(pointList))
#numerical - structured data
print()
print("--- Price Data ---")
print("Highest Price: %.2f" % maxPrice(priceList))
print("Lowest Price: %.2f" % minPrice(priceList))
print("Average Price: %.2f " % avgPrice(priceList))
print("Mode of Prices:", modPrice(priceList))
print("Median of Prices:", mediPrice(priceList))
print("Range of Prices: %.2f" % rangeCalc(priceList))
print("Standard Deviation Value of Prices: %.2f" % sd(priceList))
#textual - unstructured data
print()
print("--- Description Data ---")
print("Maximum Sentimental Value of the Wine Description: %.2f" % maxSent(sentList))
print("Minimum Sentimental Value of the Wine Description: %.2f" % minSent(sentList))
print("Average Sentiment of the List : %.2f" % averageDesc(sentList))
print("Range of Sentiment: %.2f" % rangeCalc(sentList))
print("Standard Deviation Value of the Wine Description: %.2f" % sdevFunc(sentList))

#Highest Rated Country
maxCount=(max(avgDict.items(), key=operator.itemgetter(1)))
#Lowest Rated Country
minCount=(min(avgDict.items(), key=operator.itemgetter(1)))
#Highest Rated Province
maxProv=(max(avgProv.items(), key=operator.itemgetter(1)))
#Lowest Rated Province
minProv=(min(avgProv.items(), key=operator.itemgetter(1)))
#Highest Sentiment Description
maxDescript=(max(description.items(), key=operator.itemgetter(1)))
#lowest Sentiment Description
minDescript=(min(description.items(), key=operator.itemgetter(1)))
#lowest Priced 100 Point Wine
cheapWine =(min(nameDict.items(),key=operator.itemgetter(1)))

#Creates a new text file and names it f in python
with open('mohTXT.txt', 'w',encoding='utf-8') as f:
        #Writes the average country rating in the new text file
        f.write("Here is the list of all the Countries and their Average wine point rating\n")
        f.writelines('{0}:{1}\n'.format(wineCountry,winePoint) for wineCountry, winePoint in(avgDict.items()))
        f.write('\n')
        #writes the average province rating in the new text file
        f.write("Here is the list of all the Provinces and their Average wine point rating\n")
        f.writelines('{0}:{1}\n'.format(wineProvince,winePoint) for wineProvince, winePoint in(avgProv.items()))
        f.write('\n')
        #Highest Rated Country
        f.write("The Highest Rated Country is : " + str(maxCount)+'\n')
        #Lowest Rated Country
        f.write("The Lowest Rated Country is : " +str(minCount)+'\n')
        #Highest Rated Province
        f.write("The Highest Rated Province is : " +str(maxProv)+'\n')
        #Lowest Rated Province
        f.write("The Lowest Rated Province is : "+str(minProv)+'\n')
        #Highest Sentiment Description
        f.write("The Highest Sentiment is : " +str(maxDescript)+'\n')
        #lowest Sentiment Description
        f.write("The Lowest Sentiment is : " +str(minDescript)+'\n')
        #Lowest Priced 100 point wine
        f.write('\n')
        f.write("The Lowest Priced 100 Point Rated Wine is: " + str(cheapWine))
        
f.close()

#Correlation between description and the points
#Correlation between points and price
#Correlation between price and rating
#list1=priceList
#list2=pointList
#list3=sentList
#plot1=plt.scatter(list1,list2)
#plot2=plt.scatter(list1,list3)
#plot3=plt.hist(list2,list3)
#plot3=plt.scatter(list2,list3)
#plt.show(plot1)
#plt.show(plot2)
#plt.show(plot3)

```



