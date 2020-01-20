1. Split dataset into **train_set** and **test_set**

2. Transform **train_set** with pipeline:

   + Numerical columns 
     + Fillna with median / drop columns with NA, etc
     + Add interested attributes 
     + Transform all attributes into same scale by standardization

   + Category columns
     + OneHotEncoder()

3. Fit train_set in LinearRegression model and measure RMSE(root mean squared error)

   