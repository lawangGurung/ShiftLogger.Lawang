
# Shifts-Logger.Lawang
This Shifts Logger application saves the Start and End shift time of the Employee along with employee name in the SqlServer database which is connected via Entity FrameworkCore ORM. 
This Console app uses WebApi to perform CRUD operation on the database.

## Features
- Uses (Web API/EF) stack which is very common in enterprise application.
- This is an application where you can record Employee Name with their Start and End Shift time.
-  Users are able to Add, Delete, Update and Read from a database, using the console.
- Code first approach is obtained using Entity FrameworkCore.






## Deployment

To deploy this project Create .env file and inside .env file replace "YOUR_CONNECTION_STRING" with your desired connection string.

`ConnectionString = YOUR_CONNECTION_STRING`


 ## Screen shots:


![Screenshot from 2024-09-29 15-20-15](https://github.com/user-attachments/assets/4512d6ae-479c-4d5e-a45e-cc66e9e17a23)

![Screenshot from 2024-09-29 15-20-36](https://github.com/user-attachments/assets/47e14a63-12d4-4220-817e-f2c7fc48fa44)

![Screenshot from 2024-09-29 15-21-43](https://github.com/user-attachments/assets/d77dd997-1306-43b7-9ef5-fb391640cc8b)




- Data is presented to user in Table format, using the external library Spectre.Console.
- This app is beautified using Spectre.Console.



## Project Summary
#### What challenges did you face and how did you overcome them?

* I had previous expericnce using and creating .NET/WEB Api so this project was kind of a revision for me.




## 🛠 Skills Learned
#### ENTITY-FRAMEWORK
* I had previous experiences with entity framework but doing this project was like a revision for me and helped me retain some crucial information

#### Spectre.Console
* I honed my Spectre.Console skill in this project which i previously learned.

#### .NET WEB/API
* I got a good grasp on the concepts of web api and how to handle request and response in the web api.


## FAQ

#### How to beautify the table in the project?

Answer I used the Microsoft.Spectre.Console package, which you can get for Nuget package manager. Install it and add Reference to your project. 

For more information u can visit the docs https://spectreconsole.net




## Feedback

If you have any feedback, please reach out to us at depeshgurung44@gmail.com

