Task 1: DECLARATION OF RULES-studied rules of declation of variables,OPERATORS-In operators studied about ASSIGNMENT RULES,Arithmatic operators,comparision operators,logical operators,Identity Erors,Membership operators.
Task 1 :TYPES OF DATA STRUCTURES:- Studied various data types 
 1. Numeric data types -I) Integer  II) complex  III)  float
 2.   2. Non numeric data set  - I) String
 3. 3. Sequential data set   -  I) List  II)  Tuple   III)set  IV) Dictionary
    4. We use integer data type to represent whole numbers,We use float data type to represent floating numbers(Decimal numbers)        complex data structure -It is a combination of real and Imaginary number,basically it is used in scientific calculations.        Non Numeric Data Type - String takes Alphabets. Sequential  data types : List -List stores in [] square brackets,It is mutable(Changable)  Tuple :- Touple is a readable version of list,It is unmutable (unchanged),creation of empty tuple in () brackets.set-set stores in {} curly brackets.Dictionary-If we want to represent a group of object as key-value paires then we should go for dictionary.It is stored in {} curly brackets **syntax**={key:'value',key:'value'}.
    
Task 2 : studied about In-Build function like If__ , If__else , If__ elif__ else , For loop and while loop.
If__statement  :that allows you to execute a block of code only if a specified condition is true. 
If__ else__statement :Provides an alternative execution path if the if condition is false
If__elif__statement  : that allows you to add additional conditions if the previous conditions are false.
for__loop__statement  : is a control flow statement that allows you to iterate over a sequence (like a list, tuple, string, or range) and execute a block of code for each item in that sequence.
While__loop : The while loop in Python repeatedly executes a block of code as long as a specified condition is True called Infinite loop.

Task 3 : studies about control statements like Break statement, Pass Statement, continue statement where tBreak statement used to break/stop the current iteration,countinue statement used to skip if we used "continue" to any condition and it is true then its skip that for one time and "Pass" is used when if we dont want give any condition to the situation and we want that if condition is true else it doesnt execute and passes next.
User defined function: we define function to compute some mathmatical calculation like odd-even ,Grades.
Statistical User define Function : we define function to compute some Statistical  calculation  like mean ,median .

Task 4: studied about Numpy library where 
 numpy stands for numerical python
 It is core library for numeric and scientific computing
 It consists of multi dimentional array object and a collection of routines for processing those arrays
 BASIC MATH FUNCTION
Arithmatic operations of Numpy arrays
substraction(-)
multiplication(*)
Division(/)
 matrix multiplication(@)
 Modulo(%)
 Transpose
Exponentiation(**)
 Floor Division(//)

 Task 5 : studied about Pandas library in which we created 5- notebook of pandas
1) series : studied  about various method of creating series in which creation from list creation from labels etc,and operation used for this series.
2) DataFrame : studied about how to create dataframe using matrix, and how to import csv file and xlsx file.
3) DataFrame Opertions :  we use some inbuilt operatition like 
df.head()
df.tail()
 df.shape
df.size
 df.columns
 df.dtypes
df.values
 df.index
 count
Index
unique
4) selection : studied about how we select data from DataFrame in which how to select one row ,multiple rows by index label and by integer index.Adding a new column to a dataframe, Adding a new row to a dataframe,deleting a  column to a dataframe,deleting a row to a dataframe.
5) Missing values :
6)  1.Using isna() or isnull() : These methods return a DataFrame of the same shape, but with Boolean values indicating whether each value is missing (True) or not (False).In which studied about checking of Missing values how to drop Missing value  by row and by column.
7)  Using notna() or notnull(): These methods return the opposite of isna()/isnull(), showing True for non-missing values.

8) Task 6 :  studied about matplotlib library and seaborn library where matplotlib used to visialize data or to plot the data . matplotlib is a ploting library for python and its mathmatical numeric extention numpy.Example  : Scatter plot,multiple line plot,line plot,pie chart,etc
9) Seaborn is a Python data visualization library based on Matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics. It is designed to make it easier to create complex plots and explore datasets.
1. relplot():A high-level interface for drawing relational plots.Examples: scatter plots, line plots.
2. catplot():A high-level interface for drawing categorical plots.Examples: bar plots, box plots, violin plots.
3.displot():A high-level interface for drawing distributional plots.Examples: histograms, KDE plots, rug plots.
4.pairplot(): A function for visualizing pairwise relationships in a dataset.Generates a matrix of plots to show relationships between each pair of variables.
5. heatmap():A function for drawing heatmaps.Useful for visualizing correlation matrices or frequency tables.

6. Task 7 : solved exercises : In this task soved the exercises on Ecommerce Data and saleries Data.in this task we done the preprocessing of the data .
7. Case Study : In Case study done the Model building on Titanic Data set,in which first day done  the pre-processing on the data and second day fitting the best  model.
8. project  :-In the project we studied about the machine learning.first we done preprocessing on the data,in this project we use Histerical data from Airline Delay to predict wether arrival of the flight will be delay or it will be on time.we approach this problem  as a classification problem.Airline data set have 539484 n-observation and eight different features .
9. Exploratory data Analysis : in exploratory data analysis we check the missing values but in data set there is no missing values after that we drop the unnessesary model which is "id".Then we shuffled the data into 150000 n-observations,then choose dependant and dependant variables.split the data into 80:20 ratio then fitting the model using 10 algorithm, and fit the model .to check the best parameter we use grid CV search and using best parameter fit the model.after we use feature importance code to identiify best features in the model .we got three best parametr which explain more praportion in the model which is (Airline,Length,Time).
    




