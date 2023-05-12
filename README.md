# Wine Variety Prediction

In this project we will be predicting the wine variety column using different features such as

1. User Reviews
2. Ratings Score
3. Country
4. Provinces

| user_name     |  country  |                                 review_title                                 |                                                                                           review_description                                                                                           |      designation      | points | price |    province    |        region_1        |    region_2    |       winery       |    variety |
| ------------- | :-------: | :--------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------: | :----: | :---: | :-------------: | :---------------------: | :-------------: | :----------------: | ---------: |
| Nan           | Australia | Andrew Peace 2007 Peace Family Vineyard Chardonnay (South Eastern Australia) |         Classic Chardonnay aromas of apple, pear and hay lead into a palate marked by decent intensity but also a bit of sweetness. Orange and candy notes run through the rather short finish.         | Peace Family Vineyard |   83   | 10.0 | Australia Other | South Eastern Australia |       NaN       |    Andrew Peace    | Chardonnay |
| @wawinereport |    US    |              North by Northwest 2014 Red (Columbia Valley (WA))              | This wine is near equal parts Syrah and Merlot with the balance Cabernet Sauvignon. Aromas of blue fruit, vanilla, cherry and herb lead to full-bodied pit-fruit flavors that bring a sense of delic... |          NaN          |   89   | 15.0 |   Washington   |  Columbia Valley (WA)  | Columbia Valley | North by Northwest |  Red Blend |

Here I shall be using **VS Code** 

Please install all the requirements in a fresh environment using -

> !pip install -r requirements.txt

 This project can be broken into three parts

1. Eda
2. preprocessing
3. predictive modeling
