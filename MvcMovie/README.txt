Program name: -		WEB452_WebApplication1
Program Date: -		20/09/2022
Program Purpose: -	Create Web Application using ASP.NET using MVC Framework.
-----------------------------------------------------------------------------------------------------------------------
20/09/2022
1020 - Created a new project using MVC framework for .NET application.
1021 - Commented down the ssl port because of the lab computer for hosting the file.
1022 - Created a new README file for storing the documentation.
1025 - confirmation of the web applicaiton is running.
1030 - Added a new controller empty named as HelloWorldController.cs
1035 - Added my account to the github on the Visual Studio and pushed my code to the repository.
1050 - Replace the contents of Controllers/HelloWorldController.cs trying to add public method to run the controller to the 
1100 - Updated the startup file and looked up for the pattern code.
1130 - Tried adding the Welcome method to include two parameters and commenting out the previous Welcome method.

For information: 
*The URL segment Parameters isn't used.
*The name and numTimes parameters are passed in the query string.
*The ? (question mark) in the above URL is a separator, and the query string follows.
*The & character separates field-value pairs.

22/09/2022
-----------------------------------------------------------------------------------------------------------------------
1035 - Testing the application
1037 - The applications is runiing sucessfully.
1100 - Commented down all the contolllers and undo the IACTIONRESULT Index.
1102 - Added a new Folder in the view folder and hen added a new Item caled Index.cschtml as it is a razor page view.
1105 - Changed the layout.cshtml file for updating the year option dynamically as (@DateTime.Now.Year) for the webApp, so as per the year changes,it changes automatically.
1106 - Updated Index.cshtml file as per the requirement.
1110 - Updated the names for the Application from WEB452_WebApplication to Movie App in Views/Shared/_Layout.cshtml
1120 - The Views/_ViewStart.cshtml file brings in the Views/Shared/_Layout.cshtml file to each view. The Layout property can be used to set a different layout view, or set it to null so no layout file will be used.
	 - Open the Views/HelloWorld/Index.cshtml view file.
1121 - Save the change and navigate to https://localhost:{PORT}/HelloWorld.
1125 - Left for Passing Data from the Controller to the View.

27/09/2022
-------------------------------------------------------------------------------------------------------------------------

1005 - Clone the repository and running the application to check the result for Adding the view
1006 - Starting the application from where I left from Passing Data from the Controller to the view.
1010 - Created new template for as in Views/HelloWorld/Welcome.cshtml
1015 - Updated Welcome.cshtml with the code and try running the application.
1020 - The Application ran perfectly and at this point of time we have successfully finished adding a view.

1025 - Starting with the new Tutorial name Add a data model class.
1030 - Created new Data Model Class in Models Folder by clicking ADD > CLASS and saved as Movie.cs
1033 - Trying to add Nuget packages in Studio.
1045 - Install the Framework Microsoft.EntityFrameworkCore.SqlServer
1115 - Left from Initial migration.

1142 - last Updated from Add a model> Examine the database connection string