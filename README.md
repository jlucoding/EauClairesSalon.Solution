# Eau Claire's Salon

#### By Jonathan Lu

## Technologies Used

* C#
* .NET
* Razor
* HTML
* CSS
* Bootstrap
* MySQL
* Entity

## Description

This is a web application that ultimately helps Eau Clair to manage her lists of stylists and clients. Each client is assigned to one stylist; while each stylists can have multiple clients.

## Setup/Installation Requirements

1. In a terminal, run
    `` git clone https://github.com/jlucoding/EauClairesSalon.Solution.git ``
2. In the terminal, navigate to the root directory of the project "EauClairesSalon.Solution" and create a "appsetting.json" file.
3. Update the "appsetting.json" file and insert the following (remember to remove the square brackets)
``
    "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=jonathan_lu;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
  }
``
4. In the terminal, navigate to "HairSalon" directory and run these commands in the following order
    `` dotnet restore ``
    `` dotnet build ``
    `` dotnet run `` 
5. Open local host live server to start using the web application.

## Known Bugs

* None observed

## License

Copyright (c) July 2022. Jonathan Lu