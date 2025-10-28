# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
Name:S.Rohith kumar
Regestration number:212224240153
```
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
# Line Plot:

```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
```

<img width="802" height="550" alt="image" src="https://github.com/user-attachments/assets/e6d94961-fe89-4286-b509-bcc8d924c9c8" />

```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```

<img width="838" height="548" alt="image" src="https://github.com/user-attachments/assets/b7aa2bf4-fd64-43a9-b1cd-8c75254b644a" />

# Scatter Plot:

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
```

<img width="818" height="648" alt="image" src="https://github.com/user-attachments/assets/ecfa69ad-4a32-412f-bb97-13743f6ec449" />

```
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```

<img width="787" height="586" alt="image" src="https://github.com/user-attachments/assets/6f2acf8d-7fd9-40e9-a8f6-b0bf23a4f5f0" />


# Pie Chart:

```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="732" height="530" alt="image" src="https://github.com/user-attachments/assets/2388cebc-ee1e-4a4a-b430-d6ce32760b18" />

```
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```

<img width="697" height="522" alt="image" src="https://github.com/user-attachments/assets/bad4f87d-3140-4cee-b539-30593f776227" />

# Area Chart:

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]

plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```

<img width="786" height="536" alt="image" src="https://github.com/user-attachments/assets/a85c33d1-250f-4e76-98bf-f1212c1a1a33" />



# Bar Chart:

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="722" height="572" alt="image" src="https://github.com/user-attachments/assets/e79b308b-b26b-4e5b-92a8-825ce35f9845" />



# Histogram:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="680" height="532" alt="image" src="https://github.com/user-attachments/assets/b25b9d0f-a27a-4cdb-8f80-a35b06d6e3bd" />

# Box Plot:

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="778" height="441" alt="image" src="https://github.com/user-attachments/assets/772e2805-b43f-4eed-a22e-250f6cca4c31" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="725" height="562" alt="image" src="https://github.com/user-attachments/assets/b383454a-656a-4ba2-bceb-f7bc3de6c553" />




# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
