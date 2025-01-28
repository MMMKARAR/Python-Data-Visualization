# Python-Data-Visualization
Python exercise covering Data Visualization
# Exercise 1: (Score : 4)
# Create a line plot using matplotlib pyplot that displays the population of four different cities over time. Each city should have its own line, 
# and the x-axis should represent years (e.g. 2010, 2011, 2012, etc.) while the y-axis should represent the population.
# The data for the four cities is provided below:
# City A: [500000, 550000, 600000, 650000, 700000, 750000, 800000]
# City B: [800000, 850000, 900000, 950000, 1000000, 1050000, 1100000]
# City C: [1000000, 1050000, 1100000, 1150000, 1200000, 1250000, 1300000]
# City D: [1200000, 1250000, 1300000, 1350000, 1400000, 1450000, 1500000]
import matplotlib.pyplot as plt
years=[2010,2011,2012,2013,2014,2015,2016]
city_a=[500000,550000,600000,650000,700000,750000,800000]
city_b=[800000,850000,900000,950000,1000000,1050000,1100000]
city_c=[1000000,1050000,1100000,1150000,1200000,1250000,1300000]
city_d=[1200000,1250000,1300000,1350000,1400000,1450000,1500000]
plt.figure(figsize=(10,6))
plt.plot(years,city_a,label='cityA',marker='o')
plt.plot(years,city_b,label='cityB',marker='o')
plt.plot(years,city_c,label='cityC',marker='o')
plt.plot(years,city_d,label='cityD',marker='o')
plt.title('population growth of four cities over time')
plt.xlabel('year')
plt.ylabel('population')
plt.legend()
plt.show()
![DATA1](https://github.com/user-attachments/assets/3d984933-f8cf-4006-9a1c-38eae32aaa90)
# Exercise 2: (Score : 3)
# Create a scatter plot using seaborn that shows the relationship between the number of hours studied and the test scores obtained by a group of students. Use the following data:
# Hours Studied: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
# Test Scores: [93, 57, 61, 54, 51, 53, 87, 81, 83, 85]
hours_studied=[1,2,3,4,5,6,7,8,9,10]
test_scores=[93,57,61,54,51,53,87,81,83,85]
plt.figure(figsize=(10,6))
plt.scatter(hours_studied,test_scores)
plt.title('relationship between hours studied and test scores')
plt.xlabel('hour studied')
plt.ylabel('test scores')
plt.show()
![DATA2](https://github.com/user-attachments/assets/c1371054-eb47-426d-a1b6-efc5085d9871)
# Exercise 3: (Score : 3)
# Create a bar chart using matplotlib pyplot that shows the total sales for each month of the year. Use the following data:
# Month: ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"]
# Sales: [11860, 10480, 4997, 5523, 13965, 6011, 13158, 9533, 5158, 9058, 11346, 6675]
# import matplotlib.pyplot as plt
months=["jan","feb","mar","apr","may","jun","jul","aug","sep","oct","nov","dec"]
sales=[11860,10480,4997,5523,13965,6011,13158,9533,5158,9058,11346,6675]
plt.bar(months,sales,color='skyblue',edgecolor='black')
plt.title('total sales for each month',fontsize=16)
plt.xlabel('month',fontsize=12)
plt.ylabel('total sales',fontsize=12)
plt.xticks(fontsize=10)
plt.yticks(fontsize=10)
plt.tight_layout()
plt.show()
![DATA3](https://github.com/user-attachments/assets/1409eb36-56ba-46c5-a3c6-6eb5657f8f7d)


