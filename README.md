# Twitter_MVP
MVP providing RESTful APIs for Twitter Search,Filter,Inserting in MongoDB NoSQL database and exporting filtered data into CSV files.

But first hardcode your Twitter token,token_secret,consumer_key,consumer_secret inside the 'restfulAPI.py' file before running.
Command to run:
$ python restfulAPI.py

NoSQL database-MongoDB is being used to store twitter data into 'Twitter_Data' database('information' collection) and fetch from it.
Please follow the python file comments in order to understand the usage of the RESTful APIs.
API1 is to send a keyword for query and the popular and recent searches are then stored in database.
API2 is to search/filter the data present in the database.
API3 is to export some filtered data to CSV file.


