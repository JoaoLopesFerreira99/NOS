1.1
names.py is used to check the names and details of the columns of the dataset.
data_processing.py processes and cleans the data.
plots.py uses the precessed and clean dataset to take preliminar conclusions using scatterplots and plots.
1.2
1.2.1
database.py shows how to create a database in SQLite (lightweight and adequate for small projects). 
Other approaches include MySQL and MongoDB.
1.2.2
Possible approaches include:
    - Task scheduler: Database is updated at fixed intervals set by the user.
    - File Watcher: If new data is added to a folder, Python watchdog can be used to detect new files and process them automatically.
