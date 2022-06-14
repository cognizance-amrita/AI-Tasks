# Task - 3

## Machine Learning Introduction

Machine learning (ML) is a category of an algorithm that allows software applications to become more accurate in predicting outcomes without being explicitly programmed. The basic premise of machine learning is to build algorithms that can receive input data and use statistical analysis to predict an output while updating outputs as new data becomes available.

<hr>
<br>

### Question - 1
Prepare a short writeup on machine learning (consisting of what is ML, types and applications). Make use of the resources provided. <br>
**Page Limit : 2**

<br>

## Data Preprocessing
Data preprocessing in Machine Learning is a crucial step that helps enhance the quality of data to promote the extraction of meaningful insights from the data. Data preprocessing in Machine Learning refers to the technique of preparing (cleaning and organizing) the raw data to make it suitable for a building and training Machine Learning models.

<hr>
<br>

### Question - 2
A. How will you replace all the values greater than a given value to a given cutoff from the array a, replace all values greater than 45 to 45 and less than 15 to 15.

**Input:** <br>
```
np.random.seed(100) 
a = np.random.uniform(1,50, 20) 
Hint : Use np.clip and np.where
```


B. Write a python program to split a text column into two separate columns using pandas.

**Input:** <br>
```
df = pd.DataFrame(["STD, City ,state"]) 
"33, Mumbai   Maharashtra", 
"44, Chennai    Tamil Nadu", 
"40,Vishakapatnam    Telengana", 
"80, Bangalore    Karnataka"], columns=['row'])
```

**Expected Output:** <br>
```
0 STD        City        State 
1  33      Mumbai      Maharashtra 
2  44     Chennai      Tamil Nadu 
3  40   Vishakapatnam    Telengana 
4  80   Bangalore        Karnataka 
```

<br>

### Question - 3
Apply Data Pre-processing steps to uncover the factors that affect an Indian engineering graduate’s salary and subsequently select only relevant categories that have high impact on the salary. Clean the data such a way that it can be used by any regression algorithm to predict the salary.

<br>

[___Dataset Link___](https://www.kaggle.com/datasets/manishkc06/engineering-graduate-salary-prediction)

<br>

### Question - 4
Perform linear regression using sklearn package for predicting the medical cost of a patient. Visualize the data using scatter plot and find the relationship between features using heat maps. Result should include model accuracy and scatter plot containing hypothesis line.

<br>

[___Dataset Link___](https://www.kaggle.com/datasets/mirichoi0218/insurance?select=insurance.csv)

<br>

[___Submission Link___](https://forms.gle/ciMUj1Z4b7jUUhjL7)




