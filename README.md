# mongodb-application

Download the JSON version of the [Enron data](http://svm-hf1g10-data-science.ecs.soton.ac.uk/messages.json.gz) and import into a collection called messages
in a database called enron. You do not need to set up any authentication. In the Jupyter
notebook provided, perform the following tasks, using the Python PyMongo library. Marks
available for each question are enclosed in square brackets.
1. Write a function which returns a MongoDB connection object to the "messages"
collection.​ ​[1]
2. Write a function which returns the amount of emails in the messages collection in
total​ ​[1]
3. Write a function which returns each person who was BCCed on an email. Include
each person only once, and display only their name according to the X-From header.
[2]
4. Write a function with parameter subject, which returns all emails in a thread with
that parameter, and orders them by date (ascending) [3]
5. Write a function which returns the percentage of emails sent on a weekend (i.e.,
Saturday and Sunday) as a float between 0 and 1 [3]
6. Write a function which takes an argument email_address, and limit. The function
should return the amount of emails sent, received, and total (sent + received)
between each other email address, and the email address specified as an argument,
as follows: [{"contact": "michael.simmons@enron.com", "from": 42,
"to": 92, "total": 134}, {"contact"......}]. Use the To, From, and
Cc headers.

    a. Sort the output by the total amount of emails descending
    
    b. The parameter limit which specifies how many results should be returned. If it
is null, the function should return them all. [5]


## My Code
[here](https://github.com/Trouble404/mongodb-application/blob/master/app.ipynb)

## MongoDB Tutorial
*    [MongoDB 教程](http://www.runoob.com/mongodb/mongodb-tutorial.html)
*    [MongoDB 聚合管道1](http://blog.csdn.net/myjiayan/article/details/42271159)
*    [MongoDB 聚合管道2](http://www.cnblogs.com/shanyou/p/3494854.html)

## 100 points code
[waitting update]


