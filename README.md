# TasksApi
#### A simple API built in ASP.NET Core Web API 6, connecting SQL Server Express database with EF Core and using JWT-based authentication with refresh tokens
#### We will use the latest and greatest version of Visual Studio 2022 – Community Edition to build our ASP.NET Core Web API using the fastest .NET Standard framework which is .NET 6 and C# 10.

#### The good news is that VS 2022 comes bundled with the latest version of .NET and C#, so you don’t have to worry about searching and installing any of them. So, if you haven’t got VS 2022 already, make sure you download and install Visual Studio 2022 so we can get started with our tutorial to Apply JWT Access Tokens and Refresh Tokens in ASP.NET Core Web API 6.

<h2>Nuget Package Manager</h2>

 We have to add below packages:
 
#### 1.   Microsoft.AspNetCore.Authentication.JwtBeare
 
#### 2.   Microsoft.EntityFrameworkCore
 
#### 3.   Microsoft.EntityFrameworkCore.SqlServer
 
#### 4.   Microsoft.AspNetCore.Authentication.JwtBeare


<h2>Note : </h2> I have used the wonderful extension EF Core Power Tools which in a magical way it can translate a whole database structure and relationships into neat and proper DbContext entities and configurations.

You can install it from Extensions tab -> Manage Extensions of your Visual Studio 2022

![EF core Power Tools](https://user-images.githubusercontent.com/98104395/184864023-a6cb6682-8ade-44b2-a644-2633fe02e571.png)

#### If you are following the design-first model for building your database first and then your EF Core mapping, I would highly recommend that you use this blazing fast and reliable tool to perform such operation, which will therefore boost your productivity and reduce the number of errors that might be introduced from manually creating the entities and configurations.
