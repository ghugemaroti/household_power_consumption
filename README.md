# household_power_consumption

1. Download household power consumption data from this link

                http://archive.ics.uci.edu/ml/machine-learning-databases/00235/

 

2. Extract the zip file

We are using "jupyter notebook with python 3.5.0". jupyter notebook provides a favorable envirenment with having python shell.

python has some predefined packages and libraries which is used for machine learning.

Here we have used packages like  "Pandas" , "Numpy" , "matplotlib" ,"seaborn"

# packages and there functions.

*In case if packages / libraries are not already available . we will first insatll them by using "pip" command' in command promt.
*eg:- pip install Pandas 

*we using following libraries versions:

 python: 3.5.0 (v3.5.0:374f501f4567, Sep 13 2015, 02:27:37) [MSC v.1900 64 bit (AMD64)]
 
 pandas: 0.23.4
 
 numpy: 1.15.0

# importing libraries 
 
import numpy as np                           
                                                    # linear algebra
import pandas as pd                                 # data procssing, CSV file I/O (e.g. pd.read_csv),for data manipulation 
import matplotlib.pyplot as plt                     # this is used for the plot the graph 
import seaborn as sns                               # used for plot interactive graph. 

3. Load this dataset into dataframe using "pd.read_csv" meathod.


4.  Calculate power consumed in by week/month

    * Calculate Global_active_power consumed in by Month
 

6. Calculate power consumed by each sub=meter by week/month
    
    * Calculate the power of Sub_metering_1 consumed in by Month
    * Calculate the power of Sub_metering_2 consumed in by Month
    * Calculate the power of Sub_metering_3 consumed in by Month

7.   Data Visualization using Plot
     
     * Global_active_power resampled over day for sum
     * Sub_metering_1,Sub_metering_2,Sub_metering_3 resampled over day for sum
     
     
  file includes following four files:
  
  *code file   : 1) household_power_consumption.ipynb
                
  * text file  : 2)README.md
      
