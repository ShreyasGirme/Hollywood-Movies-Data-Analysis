# Hollywood-Movies-Data-Analysis
Hollywood Movies Data Analysis & Power BI Visualization.
Raw Data Set Was given for practice. 
It was imporeted To Rstudio To find  following values & remove Outliers.
Q1 <- quantile(df$Profitability, .25) 
Q3 <- quantile(df$Profitability, .75) 
IQR <- IQR(df$Profitability) 
Newly created & Cleaned file was then exporeted to PowerBI to create data vizualtion for following queries.

In Power BI Dashboard, the client would like to see: 
For the dashboard, the company would like you to use their brand colors which are blue, green and brown. 
You can use light or dark shades of each color.
For example, light blue and dark blue are acceptable. 
The average Rotten Tomatoes ratings of each genre
The number of movies produced per year 
The audience score for each film  
The profitability per studio 
The worldwide gross per genre 
![Analysis Dasbord 1](https://user-images.githubusercontent.com/119512038/208076370-8fc871ea-e8a5-4ccd-8336-ce6a24408f3d.PNG)
![Analysis Dashbaord](https://user-images.githubusercontent.com/119512038/208076520-8a96e5d7-dedf-47c2-878c-72be8aae444a.PNG)




