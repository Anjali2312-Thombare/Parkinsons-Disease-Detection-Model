# Parkinsons-Disease-Detection-Model
Machine learning project

import all required libraries 

1)read the data using read_csv command of pandas 
Note:we can read .data file using same command that is raed_csv

2)frame the data for better reprenstation

3).head() command will print 1st five rows  

4).shape will give the number of rows and number of coloums 
    
    
     -number of rows represents number of patients
     -number of coloums represent the number of features 
   
5).info() will give you the how many non values are there in given coloums 
   
   
    -there are no null values in our dataset hence noNull count of each coloum of dataset is 195

6)similarly .isnull().sum()  give the count of null values in dataset

7)**.describe()**
  
  -it will give you 
    
    1)count\n
    2)mean
    3)standard deviation
    4)minimum value of each coloum
    5)25% values are less than  reading  n of each coloum
    6)50% values are less than  reading n of each coloum
    7)75% values are less than  reading n of each coloum
    8)maximum reading of each coloum
    
 
 8) .value_counts() will give the number of patient with parkinson and patient with no parkinson

 9).drop(columns()) will drop the coloums which are not required for training 
    
