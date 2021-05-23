# Jesse's Eau Claire's Salon
https://github.com/jessecallahan/HairSalon.Solution

Created 05.21.21</br>
By _**Jesse Callahan**_</br>
Contact: _**Jessetylercallahan@gmail.com**_</br>

## Description
Eau Clarie's Salon is a C# application in the .NET MVC Framework that utilizes a local sql database. This application simulates a Salon database, where an owner can see all the Stylists and Clients they have booked using a one to many database relationship. 

## Setup/Installation Requirements

1. Clone this [repository](https://github.com/jessecallahan/HairSalon.Solution)
2. From the project directory folder create a 'appsettings.json' file
3. Copy this into the appsettings.json file:<br/>  `{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=jesse_callahan;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
}`<br/>  *[YOUR-PASSWORD-HERE] is your sql password*
4. From the project directory folder use command 'dotnet restore' in your terminal to load boilerplate
5. From the project directory foldernuse command 'dotnet run' in your terminal to run server
6. Copy the local host 5000 server link into your perferred web browser
7. Enjoy!

## Specs

![image info](./HairSalon/wwwroot/images/schema_pic.png)
## Technologies Used
* C#
* MySql
* Entity Framework
* .NET
* MVC
* CSS/HTML


