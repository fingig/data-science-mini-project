# Video Game Sales - Mini Data Science Project
This is a formulative project completed for year 2 *Foundations of Data Science* course.
The ultimate goal was to explore a dataset, in this case **vgsales.csv** and try to answer a research question using a visualisation. I formulated the question in a way in which I was able to use simple linear regression so that I could put into practice what I have learnt thus far in this course. The question being:

**“Does the year of release influence global video game sales?”**

The project includes full exploratory analysis, visualisation, regression modelling, and a LaTeX-written report.

##  Research Question

**Does the release year of a video game influence its global sales?**

This question was investigated by:
- cleaning the dataset  
- visualising trends over time  
- examining missing values  
- fitting a linear regression model  
- interpreting both the visuals and statistical output


##  Data Cleaning Summary

- Removed rows with missing `Year` values (cannot be imputed reasonably)
- Converted `Year` from float → integer for modelling
- Checked dataset structure, missing values, unique counts
- Identified outliers and understood their effect on sales distribution

No advanced imputation was used because year-of-release cannot be reliably inferred. 

 
##  Exploratory Visualisations

The notebook includes several key plots:

### **1. Scatter Plot: Year vs Global Sales**  
Revealed heavy noise and large variation between individual game sales.

### **2. Average Global Sales Per Year**  
Showed a clear **non-linear** trend with sales peaking in the mid-2000s then declining.

### **3. Regression Plot with Fitted Line**  
A linear regression line was added to the scatter plot to visualise the trend.

All visualisations were exported as PNGs and included in the LaTeX report.


## Final Report
For  more information see the PDF report under **`report/main..pdf`**. The laTeX source tex file is also provided.

## Author
Sebastian Todd

## Final Reflection
looking back there were many things I would of done to improve the quality of this project like choosing a different data set with more numerical features to properly explore some linear relationships, or going into more depth at certain parts. Howver for my first time using Git laTeX and my first time building a data science project on my own I think I did a very good job.
