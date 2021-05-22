# Jesse's Eau Claire's Salon
https://github.com/jessecallahan/HairSalon

Created 05.21.21</br>
By _**Jesse Callahan**_</br>
Contact: _**Jessetylercallahan@gmail.com**_</br>

## Description
Eau Clarie's Salon is a C# application in the .NET MVC Framework that utilizes a local sql database. This application simulates a Salon database, where an owner can see all the Stylists and Clients they have booked. 

## Setup/Installation Requirements

1. Clone this [repository](https://github.com/jessecallahan/HairSalon)
2. From the project directory folder create a 'appsettings.json' file
3. Copy this into the appsettings.json file:<br/>  `{
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=jesse_callahan;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
}`<br/>  *[YOUR-PASSWORD-HERE] is your sql password*
4. From the project directory folder use comman 'dotnet restore' in your terminal to load boilerplate
5. Copy the local host 5000 server link into your perferred web browser
6. Enjoy!

## Specs

_**Stylist Class**_

|  Amount/User Input|  Type | Output  | Test Function |
|---|---|---|---|
| 1  |  "stylist" | Instance of Bread is Bread type | BreadConstructor_CreatesInstanceOfBread_Bread() | 
| 1  |  "stylist"  | Amount is being recognized | GetAmount_ReturnsstylistAmount_Int() |
| 0  |  "stylist" | $0 |ReturnBreadTotalCost_ReturnsBreadTotalCostTest1_Int()|


_**Client Class**_

|  Amount/User Input|  Type | Output  | Test Function |
|---|---|---|---|
| 1  |  "Client" | Instance of Client is Partry type | PastriesConstructor_CreatesInstanceOfClient_Pastries() | 
| 1  |  "Client"  | Amount is being recognized | GetAmount_ReturnsClientAmount_Int() |
| 0  |  "Client" | $0 | ReturnPastryTotalCost_ReturnsPastryTotalCostTest1_Int()|


![image info](./HairSalon/wwwroot/images/schema_pic.png)
## Technologies Used
* C#
* MySql
* Entity Framework
* .NET
* MVC
* CSS/HTML


