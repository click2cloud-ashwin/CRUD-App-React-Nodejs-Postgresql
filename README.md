# CRUD Application using React js, Nodejs and Postgresql as Database.


## Abstract

This is a small application using Express and Node.js that can record and remove information from a PostgreSQL database according to the HTTP requests it receives.
We have a simple React app to test and see how the entire application flows from front to back.


## Prerequisites:

1. You must have install Node js.
2. Create a database in Postgres DB and name the DB table as merchants. (You can have any table name but then need to replace the table name in the file `merchant_model.js`). 
   Then replace the connection string in the file `merchant_model.js`. This is DB table with 3 fields id, name, email.
   
    ![image](https://user-images.githubusercontent.com/82659622/176370501-d5547b78-2169-4dcb-b095-08636b5f1071.png)

## Starting the Application:

To start this application, follow the below steps:

1. To start backend, run the following command in one terminal.

```
node index.js
```

2. To start frontend i.e. React app, run the following command in another terminal.

```
npm start
```

Now you can access the application by hitting the url  `http://localhost:3000/` into your favourite web browser.

