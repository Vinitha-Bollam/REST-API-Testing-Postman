# REST-API-Testing-Postman
REST-API testing using Postman tool 
Here is Swagger Documentation: https://restful-booker.herokuapp.com/apidoc/index.html

Perform CRUD operations on Heroku booking app and perform all required assertions.

In this repo we have static and dynamic tests to perform CRUD operations on Heroku App.

1. In order to view and run the static tests import both "HerokuBookings.postman_collection" and "HerokuBookings.postman.GlobalVariables" json files into postman and run the collection.

Here are the results:
![image](https://user-images.githubusercontent.com/108022872/212811002-00a3ff86-864e-4543-9ab4-ad83ed1320ee.png)

![image](https://user-images.githubusercontent.com/108022872/212811060-3c14f13e-713a-4712-bcb8-f82e71b26b60.png)

![image](https://user-images.githubusercontent.com/108022872/212811174-a72b3024-d1fc-45b3-99c4-b15793d86995.png)

2. In order to view and run the dynamic tests import both "HerokuBookings_DataDrivenTest.postman_collection" and "HerokuBookings.postman.GlobalVariables" json files into postman and use HerokuBookingEndpoint.csv to run the collection with different sets of data.

Here are the steps to import csv :
![image](https://user-images.githubusercontent.com/108022872/213933938-dd4da911-5bc0-42e4-bbb3-344146f8bc5d.png)

After running the collection here is the report summary
![image](https://user-images.githubusercontent.com/108022872/213933974-58fe6f22-f646-47b8-a847-8dc010a2422c.png)
