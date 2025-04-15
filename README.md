# Converting-Data-Type-by-Python

Hi there,

We just finished collecting survey data from a few thousand customers wo've purchased our alarm clocks(see attached).

Can you read the data into Python and make sure the data type of each column makes sense? We'd like to do quite a few calculations using the data, so if a column can be converted to anumeric or datetime column, please do so.

Thanks!

Alan

## Key Objectives

- Read in data from Excel spreadsheet and store it in a Pandas DataFrame
- Check the data type of each column
- Convert object columns into numeric or datetime columns as needed

## Key notes
- To see the data type of the data frame
  data_frame.dtypes or data_frame.info()

- Use pd.to_datetime() to convert object columns into datetime columns
- Use pd.to_numeric() to convert object columns into numeric columns
