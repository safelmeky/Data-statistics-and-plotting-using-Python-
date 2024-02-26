A statistical analysis on a movies data set provided by IMDB with the higest level of credibility on Kaggle of 10/10.

Programing language used :Python 

Packages used (Pandas-seaborn-numpy-matplotlib) 

hypothesis:
1- Corelation between budget and Gross_income is directly proportional
2- Corelation between Company's name and Gross_income is directly proportional

process:
- started with some data cleaning  checking for duplicates (there were non)
- removing Nan valuses (switching them to zeros if exited in numerical column )
- extracting the year from the date column to be in a sperate column
- normalizing the data and using statistics (Pearson) method to find the correlation between the columns

Findings:
1-Corelation between budget and Gross_income is directly proportional (correct with a corr of 0.74)
2-A company's name has an effect on Gross_income (wrong companies has no effect on the gross income of a movie )

Visulization:
Extracting the data from the notebook and creating a very interesting Dashboard using Tableau
