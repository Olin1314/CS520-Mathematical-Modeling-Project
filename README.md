# CS_520_Project_The Priority List of Statisticians for Boosting Home Value

## How to Run
Copy this repository and open **Project.Rproj** in RStudio. 

Open **Project_Home values.Rmd**. Proceed to install all associated libraries and run each file. While running the file, we may face some errors such as **"Error: package or namespace load failed for ‘kableExtra’ in loadNamespace(j <- i[[1L]], c(lib.loc, .libPaths()), versionCheck = vI[[j]]): there is no package called ‘systemfonts’"**, after installing all the required packages, everything should work well. If we fail to install some packages because of different versions of RStudio, the packages of **knitr** and **kableExtra** are also considered to help us generate a neat and well-formatted final document via R markdown.

In addition, we will need to upload the **king_county_map.png** for the line 34 **"include_graphics("king_county_map.png")"**.

## Data
A real-world dataset that contains house sale price information and the corresponding house features of **King County, Washington from 2014 to 2015** will be used. It is originated from **Kaggle**, and can be imported to R from **mlr3data** package. Basically, there are 21,613 observations along with 19 house features such as the number of bathrooms, bedrooms, floors, and square footage of the housein the original data. 

## Packages 
The first package that will be used in this project is **mlr3data**, which offers the dataset that we are going to analyze. Besides, we will use the **ggplot2** and **lattice** packages for the purpose of **data visualization** and **randomForest for random forest models** that can be helpful to analyze the effects of the house factors on the house price. Also, we will utilize the stargazer package to offer neat and more readable model results of linear regressions. Anotehr important package that can be useful in this project is **GGally**, in which the **ggcorr function** can help us obtain the correlation matrix. Finally, we also use the **dplyr** package to manipulate and modify data frames.

## Conclusion
Based on the codes, a priority list for boosting home value should contain the following two things:
1.Try to maintain the house in a good condition and add more custom design so that it can be graded higher.
2.Try to expand the space of living room in the house.

We can get the final version via reading  **Project_Home Values_Olin.pdf**. 

