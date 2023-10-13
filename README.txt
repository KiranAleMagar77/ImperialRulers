2023-10-13  10-10

Assignment 1 (IMPERIAL RULERS)

Opened the vs code and made a new project in the local storage named Imperial Rulers

10-15
did everything as given in the tutorial to create the project
commented the //"sslPort": 44397

10-20
Ran the program to check if its working or not and it ran perfectly.

10-22
Addded the controllers in the controller in the controller folder called helloworldcontroller.cs

10-25
addded the welcoem message in index and welcome 

10-29
ran the project to seee if it shows the message or not and it ran perfectly
happy that its working as of now 

10-35
edited the configure method in startup.cs

10-38
now i started to change the welcome method in the controller so that it can show the name and numtimes

10-42
Had the problem with the id  in the contoller 

10-55
solved the problem by debugging 
it was a small typo

11:00
now started to add the view to the project

11:02
Added one folder named HelloWorld  and added a new file named index.cshtml

11:10
added the hello message in the file and ran the program to see the message

11:15
edited the _layout.cshtml in the views/shared folder 
and edited the helloworld file also and ran the program

11:25
Changed the helloworld controller as tutorial

added new file named welcome.cshtml and displayed the name for numtimes


11:45
Started to work on model 

11:50
Added the new class in the model folder named Ruler.cs
and added the properties to the class

12:10
tried to install nudget packages but had problem with framework 

12:15
solved the problem with this steps
/////to select the frame work//////// >DO IT BEFORE INSTALLING NUGET PACKAGE
1>go  to tools
2>nuget package
3>and managae nuget package manager
4>and search Microsoft.EntityFrameworkCore.SqlServer
5>then select the framework you want and install it 

12:20
Installed  FRAMEWORK 3.1.32

Install-Package Microsoft.EntityFrameworkCore.SqlServer -version 3.1.0

12:30
Created the Data folder  and made a new file inside it called ImperialRulerContext.cs

12:45
worked on scaffolding the Ruler page
and did the initial migraiton with following code

Add-Migration InitialCreate
Update-Database


12:50
ran the app to check again and it ran perfectly thank god !!!!!!!!!!!!!!!!!!!!!!1


1:00
edited @model IEnumerable<ImperialRulers.Models.Ruler> in index.cshtml

1:02
Now started to work with the database
i did this by going to  view menu and SQL Server Object Explorer
and checked the view data/view designer

1:10
Created new class inside the model folder called SeedData

1:12
Seeded the DB with 10 datas

1:20
replaced the code in program.cs with the code given in tutorial.


1:25
Ran the program and it ran without errors

1:30
Working on adding search to the table

1:45
edited the index method inside the rulercontroller.cs

1:50 
edited the method in Index.cshtml to get
1:55
addded the search by types of rulers

again edited the index method so that it can search the rulers by types

2:10
added the validation to the properties like the limits of words and the numbers
 
2:20
ran the program and it ran perfectly 

2:30
Made a new file called AboutUs.cshtml in Home folder

2:32
added a new nav-list as About Us in he _layout.cshtml

2:40

added 
  public IActionResult AboutUs()
        {
            return View();
        }
 in the home controller 

2:42
Ran the program and it showed the new navigation list called About us

3:00 
now working on formating the home page for the website

3:30 
added the images in the wwwroot folder  by creating a new folder named img and added the copyright free images





















