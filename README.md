# Diamond-Price-prediction-Kaggle
Price prediction and analysis of retail elements.

# STAR this repo if find useful :)

Link of the dataset : https://www.kaggle.com/shivam2503/diamonds
Link of the notebook in kaggle : https://www.kaggle.com/shivam2503/diamonds

You can visit my other works in [kaggl](https://www.kaggle.com/sagnik1511/notebooks)

### Data Description :

 ^   Column      Non-Null Count  Dtype  
 
 0   Unnamed: 0  53940 non-null  int64 
 
 1   carat       53940 non-null  float64
 
 2   cut         53940 non-null  object 
 
 3   color       53940 non-null  object 
 
 4   clarity     53940 non-null  object 
 
 5   depth       53940 non-null  float64
 
 6   table       53940 non-null  float64
 
 7   price       53940 non-null  int64  
 
 8   x           53940 non-null  float64
 
 9   y           53940 non-null  float64
 
 10  z           53940 non-null  float64
 
dtypes: float64(6), int64(2), object(3)
memory usage: 4.5+ MB


Approch :
1. encode
2. Feature engineering
3. Data splitting


Model :
* Library    : sklearn
* Module     : ensemble
* Model      : RandomForestRegressor
* Attributes : random_state=0 , default


Evaluation :

## Model Metrics :   
#### R2-score :   
        1. Train dataset : 99.99928433541474 %
        2. Test dataset  : 99.99839962104917 %
        
#### RMSE (Root Mean Squared Error) :
        1. Train dataset : 10.667275042359574
        2. Test dataset  : 15.988252090898984
