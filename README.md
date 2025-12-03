# Assignment11_1
In this application, we will explore a dataset from Kaggle. Our goal is to understand what factors make a car more or less expensive. As a result of our analysis, we should provide clear recommendations to our client—a used car dealership—as to what consumers value in a used car.

Dataset referred : 
https://github.com/kapilsharma2411/Assignment11_1/blob/main/data/vehicles.csv

Notebook Link: 
https://github.com/kapilsharma2411/Assignment11_1/blob/main/PracticalApplication11_1.ipynb

Plots and Graphs associated with above notebook can be found under :
https://github.com/kapilsharma2411/Assignment11_1/tree/main/images

Based on the feature analysis, here are some recommendations for the used-car dealership client: 

1. Prioritize Age Over Mileage (Year is the Key)
    - Lasso method proves that "Year" was a highly influential positive factor. The scatter plot confirms this as model year increases (newer cars), the maximum and median price of the cars tends to rise clearly.
    -Image can be found at : 
    https://github.com/kapilsharma2411/Assignment11_1/blob/main/images/proof_1_year_vs_price.png
2. Target High-End Manufacturers
    - The box plot above clearly indicates high end manufacturer prices, their mean and median proces tends to rise higher then the average/normal manaufacturer such as "ford"
    -Image can be found at : 
    https://github.com/kapilsharma2411/Assignment11_1/blob/main/images/proof_2_high_low_manufacturers_price.png
3. Value Diesel Fuel cars
    - The third plot which is also a box plot between cars of Diesel fuel versus Gas clearly indicated that Diesel Cars have higher prices and hence those are the ones the car-dealership should prioritize over gas fuel type cars
    -Image can be found at : 
    https://github.com/kapilsharma2411/Assignment11_1/blob/main/images/proof_3_diesel_vs_gas_price.png