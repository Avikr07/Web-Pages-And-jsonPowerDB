Title:

# Web-Pages-And-jsonPowerDB
It is a basic project describing the use of jsonPowerDB in web pages using the Apache NetBeans Ide.

Introduction to jpdb-JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS.

Description:

We are going to create a web page using the basic html and css.This web page in our case will be a from validating the user and many more operations.
For storing,retreiving,upadting and viewing the data that is related to the users we are going to use JPDB.


Benefits of using JsonPowerDB:

1.>It is very simple to use ,you just need token,db-name ,rel-name and a json format to put ,get,update or remove a data.
2.>It is schema free that's why easy to maintain.
3.>It provides serverless support.

Like other databases you donot need to specify the data_type ,no need to create tables beforehand for entry of data andd running the queries.



Code:

Basically we have created a form and will try to push data using the form.
There are several functions in the code that are being used.

1.>  function validateAndGetFormData()-this is going to take credentials from the user and validate it.
2.>  function createPUTRequest(connToken, jsonObj, dbName, relName)-it is goig to take token,dbname ,rel and jsonobject basically jsonstr to put into the table.
3.>  function executeCommand(reqString, dbBaseUrl, apiEndPointUrl)  -going to exceute the command using the url of jsonpower db login site.
4.>  function resetForm() - will reset the form after one request and move the cursor to the initial point of the form.
5.>  function saveEmployee() -It is going to save the employee data to the table after using the above functions sequentially.
