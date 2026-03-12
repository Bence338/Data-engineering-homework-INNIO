Medallion Architecture

I have started by reviewing the CSV and the TXT file so I know what I will be working on.

Running the notebook will load the data into a pandas dataframe. After that, with the help of the PySpark library, I just made an SQL table.
After that, the notebook will filter the dataframe by some of the requirements and make a second SQL table. In this SQL table, I haven't filtered the records with invalid values as planned. I made a query to select the records with invalid values so I can delete them directly.
Then I made the final silver level SQL table. Then the notebook will remove the duplicated rows (based on my interpretation, those rows contain information that was not there before, even though the record is complete and valid).
After making the business filtering as well, the notebook will create the final SQL table.

Visualization


