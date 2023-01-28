# PANDAS
this repository contains all brief information about pandas (Series/DataFrame) contains all functions and methods like groupby(),merge and many more.

🅿🅰🆁🆃 1 🅲🅾🅽🆃🅰🅸🅽🆂 
 
 1.What is Pandas.
 
 2.Series from lists
 
 3.Series from dict
 
 4.Series Attributes(size/dtype/name/is_unique/index/values)
 
 5.Series using read_csv
 
 6.Series methods
 
 7.series.head()/series.tail()
 
 8.series.sample()
 
 9.value_counts()
 
 10.sort_values()
 
 11.sort_index()
 
 12.Series Maths Methods
 
 13.count()
 
 14.series.sum/product
 
 15.mean/median/mode
 
 16.min/max
 
 17.Describe
 
 18.Series Indexing
 
 19.Editing Series

 20.astype
 
 21.between
 
 22.clip
 
 23.drop_duplicates

 24.duplicated
 
 25.isnull
 
 26.dropna

 27.fillna
 
 28.isin

 29.apply
 
 30.copy
 
🅿🅰🆁🆃 2 🅲🅾🅽🆃🅰🅸🅽🆂
 
 Creating DataFrame
 
 1.using lists
 
 2.using dicts
 
 3.using read_csv
 
 4.DataFrame Attributes and Methods
   shape
   dtypes
   index
   columns
   values
   
   head and tail()
   sample()
   info()
   describe()
   isnull()
   duplicated()
   rename()

 5.Mathematical Methods

 6.Selecting cols from a DataFrame -- single cols

 7.Selecting cols from a DataFrame -- multiple cols

 8.Selecting rows from a DataFrame

 9.iloc - searches using index positions

 10.loc - searches using index labels

 11.Selecting both rows and cols

 12.Filtering a DataFrame

 13.Adding new cols - completely new

 14.Adding new cols - from existing ones


 Dataframe IMPORTANT function 
 
 1.value_counts
 
 2. Toss decision plot
 
 3. No of matches each team has played
 
 4. sort_values
 
 5. Sort values on nan values
 
 6. Sorting on multiple columns
 
 7. rank
 
 8. sort index
 
 9. set index
 
 10. reset index
 
 11. How to replace existing index without loosing
 
 12. Series to dataframe using reset_index
 
 13. rename index & rename
 
 14. unique & nunique
 
 15. isnull/notnull
 
 16. dropna
 
 17. fillna
 
 18. drop_duplicates
 
 19. find the last match played by virat kohli in Delhi
 
 20. drop
 
 21. apply

🅿🅰🆁🆃 3 🅲🅾🅽🆃🅰🅸🅽🆂

 GroupBy
 
 Applying builtin aggregation fuctions on groupby objects

 find the top 3 genres by total earning

 find the genre with highest avg IMDB rating
 
 find director with most popularity

 find the highest rated movie of each genre

 find number of movies done by each actor

# GroupBy Attributes and Methods

 find total number of groups -- len
 
 find items in each group -- size

 first()/last() / nth item

 get_group / vs filtering

 groups attribute

 describe / # sample / # nunique

 # agg method -  passing dict
 # agg method -  passing list
 
 looping on groups
 find the highest rated movie of each genre

 apply -- builtin function

 find number of movies starting with A for each group

 find ranking of each movie in the group according to IMDB score

 find normalized IMDB rating group wise

 groupby on multiple cols

 find the most earning actor -- director combo

 find the best(in-terms of metascore(avg)) actor -- genre combo

 agg on multiple groupby

🅿🅰🆁🆃 4 🅲🅾🅽🆃🅰🅸🅽🆂

 IPL Dataset

  # find the top 10 batsman in terms of runs

  # find the batsman with max no of sixes

  # find batsman with most number of 4's and 6's in last 5 overs


  # find V Kohli's record against all teams

  # Create a function that can return the highest score of any batsman
  
🅿🅰🆁🆃 5 🅲🅾🅽🆃🅰🅸🅽🆂  

   #pd.concat
   
   #df.append

   #Concat as mullitindex df 

   #concat dataframes horizontally

   #Merge 
       
       #inner_join
        
       #left_join
      
       #right_join

       #outer_join

   # 1. find total revenue generated
   
   # 2. find month by month revenue

   # 3. Print the registration table
    
   # 4. Plot bar chart for revenue/course

   # 5. find students who enrolled in both the months

   # 6. find course that got no enrollment
   
   # 7. find students who did not enroll into any courses

   # 8. Print student name -- partner name for all enrolled students

   # 9. find top 3 students who did most number enrollments

   # 10. find top 3 students who spent most amount of money on courses

   # Alternate syntax for merge - pd.merge       

 # IPL Problems

   # find top 3 stadiums with highest sixes/match ratio
   
   # find orange cap holder of all the seasons

🅿🅰🆁🆃 6 🅲🅾🅽🆃🅰🅸🅽🆂

  MultiIndex Session Start

  Having Multiple Index

  how to create multiindex object

  creating a series with multiindex object

  Fetching Items from multindex series

  Dimension of multi Index series?

  #unstack
  
  #stack
 
  Why to use Multi Index series?
 
 #MultiIndex DataFrame

 # Are columns really different from index?

 #MultiIndex Data Frame from columns perspective

 #MultiIndex on row and column both

 #Stacking  and #Unstacking

 Working with #multiIndex DataFrames

 # Extracting Single row

# Extracting Cols

# Extracting both

# sorting index

#Transpose Dataframe

#swaplevel

#LongVsWide Data

#Pandas-melt -- simple example branch

# melt - real world example


🅿🅰🆁🆃 7 🅲🅾🅽🆃🅰🅸🅽🆂

   pivot_table 
   
   #aggfunc
   
   #multidimensional pivot_table

   #pivot_table margin
   
   #plotting_graph
   
  
🅿🅰🆁🆃 8 🅲🅾🅽🆃🅰🅸🅽🆂
  
  #pandas_string
   
   # What are vectorized string operations
   
   # problem in vectorized opertions in vanilla python
   
   # How pandas solves this issue?
   
   # Common Functions
            
            lower/upper/capitalize/title
            
            #len/strip
            
            #split -- get

            #replace 

 # filtering - # startswith/endswith  isdigit/isalpha...

 # applying regex

 # find last names with start and end char vowel
 
 # slicing


🅿🅰🆁🆃 9 🅲🅾🅽🆃🅰🅸🅽🆂

    #pandas date_time
    
    Creating Timestamp objects
    
    # using datetime.datetime object
    
    # fetching attributes - year/month/day/
    
    #why separate objects to handle data and time when python already has datetime functionality?
    
    #DatetimeIndex Object
    
    #date_range function
    
    #to_datetime function
    
    #date time accessor
    
    #plotting 
