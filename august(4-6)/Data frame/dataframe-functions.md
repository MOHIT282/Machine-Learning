df.shape                          it gives no. of rows and columns of a dataframe
df.describe()                     it gives various description about the dataframes like mean median mode(does not work on non - numerical columns)
df.info()                         it gives the brief description of the dataframe ()
df.count()                        returns count of all the non-null values in the dataframe
df.isna()                         returns true for null values and false for non null values
df.size                           return total no. of values present in the dataframe
df.head([x])                      return first 5 rows by default variable sized data can be fetched
df.tail([x])                      works same as head but works be fetching data from the end
