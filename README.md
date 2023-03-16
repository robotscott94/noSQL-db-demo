# noSQL-db-demo

## Purpose
Utilize noSQL database MongoDB to extract, transform and analyze UK restaurant data.

## Tools
Data was added to MongoDB via the command line, and the pymongo dependency in python is used to load and transform data. The pprint package is used to inspect collection elements, and multiple queries on the data are executed for analysis.

## Results
In the first notebook, the data is loaded and inspected. Also, new restaurants are added, and variable types are changed. In the second notebook, various questions are answered using queries. For instance, a list of top restaurants in London with a specified hygeine score is generated and coverted into a dataframe for further analysis. All updates are saved in the original database, and all queries can be re-exececuted in the notebook.
