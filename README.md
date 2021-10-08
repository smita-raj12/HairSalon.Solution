# Eau Claire's Salon

A MVC web application to help stylists to find clients and clients to find there stylists. User can add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. The stylists have specific specialties, so each client can only see (belong to) a single stylist.

User Stories

* As the salon owner, I need to be able to see a list of all stylists.

* As the salon owner, I need to be able to select a stylist, see their details, and see a  list of all clients that belong to that stylist.

* As the salon owner, I need to add new stylists to our system when they are hired.

* As the salon owner, I need to be able to add new clients to a specific stylist. I should not be able to add a client if no stylists have been added.


## Name of Author:

   _Smita_

## Technologies used:

* C#

* MySQL

* MySQL Workbench

* .NET 5 SDK

* Git BASH

* ASP .NET CORE MVC

* My SQL Designer

## Setup/Installation Requirements

1. Download or clone the [https://github.com/smita-raj12/HairSalon.Solution](https://github.com/smita-raj12/HairSalon.Solution) to your local machine.

2. Download any Code Editor for your choice. (Here I used VSCode).

3. Open git BASH terminal and navigate to the HairSalon folder, within the directory
Run `dotnet restore` in the git BASH terminal to install dependencies. 

4. Create your own version of the database by importing the smitarajpurohit.sql file from the repo with MySQL Workbench.

5. Create appsettings.json file in the HairSalon directory of HairSalon.Solution (run the command touch appsettings.json) and add the following code to the file: appsettings.json
  
  {
  
    "ConnectionStrings":

    {

      "DefaultConnection": "Server=localhost;Port=3306;database=hair_salon;uid={YOUR_USERNAME_NAME};pwd={YOUR_PASSWORD};"

    }

  }
 
6. Remove the {YOUR_USERNAME_NAME} and {YOUR_PASSWORD} and fill in the the code snippet with your username for MySQL, and MySQL password Do not include the curly brackets in your code snippet of appsettings.json

7. Run "dotnet build" in the git BASH terminal to build, and run the project in the terminal. $ dotnet watch run

8. View the website by visiting localhost:5000/ in a new web browser( such as google chrome) tab!


## Known bugs

None 

## License information with a copyright and date:

 [MIT](https://opensource.org/licenses/MIT)

## Contact information:
   
* EmailId: smita.raj12@gmail.com

