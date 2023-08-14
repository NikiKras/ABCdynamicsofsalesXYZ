# ABCdynamicsofsalesXYZ
Pet project: Three tasks in the sphere of trade: ABC-analysis, Dynamics of sales, XYZ-analysis.  
# Data:   
We have a piece of information provided by a pharmacy chain in which there is data about sales.
Used columns: 
  + DR_NDrugs - product name
  + DR_Kol - number of pieces sold
  + DR_CRoz - retail price
  + DR_SDisc - discount 
# Task:   
We need to perform three types of analysis: 
  1. ABC-analysis
  2. Sales dynamics
  3. XYZ-analysis
# Solution:
First I imported pandas and Numpy libraries, then configured the working area using function Set_Option.
# 1. ABC-analysis:  
One-dimensional ABC-analysis:  
  + Loaded the dataframe
  + Counted sales by product
  + Counted the contribution of each product
  + Counted the sales as an accumulation
  + Defined groups

Multidimensional ABC-analysis:
  + Counted sales by product and by retail price
  + Calculate groups for column with product quantity
  + Calculate groups for column with retail price
  + Selected the right columns and sorted

**Wrote a function to automate ABC-analysis**
# 2. Sales dynamics:
  + Loaded dataframe 'dataAptSecond.csv'
  + Assess the data structure, find out we have five days
  + Calculated the sales amount for each day, minus the discount in new column
  + **Three ways I counted sales dinamics:**
  <ol>
  <li>Using 'rolling' and lamda-function</li>
  <li>Using 'shift' and ordinary expression</li>
  <li>Using only 'pct_change'</li>
</ol>  

# 3. XYZ-analysis:   
  + Sales calculated per day for each product
  + Filtered only those products that sold for several days
  + Calculated the coefficient of variation
  + Defined groups
