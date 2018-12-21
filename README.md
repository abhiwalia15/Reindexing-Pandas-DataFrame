# Reindexing-Pandas-DataFrame
*We can reindex the columns and rows in pandas. 

  *Reindexing in pandas is used to change the row labels and column labels of a dataframe.

  *We make use of dataframe.reindex() method to change the index.

  *Default values which are present in our new index and that are not present in the dataframe are assigned as NaN. 
  
    *Missing values from our dataframe can be filled by passing a value to the keyword fill_calue.
    *This keyword replaces the NaN values in our dataframe.
   
  *For reindexing the columns we can make use of axis keyword and pass columns to it in reindex() method.
