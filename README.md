# Liquid Nitrogen Freezer Organizer
This repo contains information for both the front-end and back-end for this liquid nitrogen inventory management application.

#### By _**Ian Bravo**_

## Table of Contents
* [Liquid Nitrogen Freezer Organizer API](#liquid-nitrogen-freezer-organizer-api)
  * [API Technologies Used](#api-technologies-used)
  * [API Description](#api-description)
  * [API Setup and Installation Requirements](#api-setup-and-installation-requirements)
  * [API Documentation](#api-documentation)
* [Liquid Nitrogen Freezer Organizer Application](#liquid-nitrogen-freezer-organizer-application)
  * [Technologies Used](#technologies-used)
  * [Description](#description)
  * [Setup and Installation Requirements](#setup-and-installation-requirements)
* [Known Bugs](#known-bugs)
* [License](#license)

# [Liquid Nitrogen Freezer Organizer API](#liquid-nitrogen-freezer-organizer-api)

### _This RESTful web API is designed for a Liquid Nitrogen Freezer Organizer Application._

## [API Technologies Used](#api-technologies-used)

* _C# 10.0_
* _.Net 6.0_
* _ASP.NET Core 6.0_
* _Entity Framework Core 6.0_
* _MySQL 8.0_
* _Postman_
* _Swashbuckle.AspNetCore 6.2_

## [API Description](#api-description)

This RESTful API will allow for the creation of a freezer management system. This web API has many different endpoints as shown in the <a href="https://github.com/ian-bravo/LNFreezerAPI">API's README</a>. User Authentication and Authorization implementation is planned.

## [API Setup and Installation Requirements](#api-setup-and-installation-requirements)

Installing/Configuring MySQL:

1. Follow the instructions on this <a href="https://full-time-pre-october.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql">page</a> for installing and configuring MySQL.

Installing Postman:
1. Follow the instructions <a href="https://www.postman.com/downloads/">here,</a> for installing Postman to use for API calling.

Installing dotnet-ef:
1. Run the following command to globally install dotnet-ef tools which will allow you to create migrations and create databases:    
```
$ dotnet tool install --global dotnet-ef --version 6.0.0
```


Cloning the API Repo:
1. Open the terminal.
2. Change your directory to where you would want the cloned directory.
3. Input the following command into your terminal:  
```
$ git clone https://github.com/ian-bravo/LNFreezerAPI
```

4. Using the terminal, navigate to the production directory: "LNFreezerAPI" and create a new file called appsettings.json
5. Within appsettings.json, put in the following code while also replacing the following values with your own values as shown in the code snippet below:
```json
{
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  },
  "AllowedHosts": "*",
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[YOUR-DB-NAME];uid=[YOUR-USERNAME-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}
```
* [YOUR-USERNAME-HERE] with your username
* [YOUR-PASSWORD-HERE] with your password
* [YOUR-DB-NAME] with the name of your database

Generating the database:
1. Navigate to the project's production directory "LNFreezerAPI" using the terminal.
2. Run the following command to update the database:   
```
$ dotnet ef database update
``` 

Launch the API:
1. Navigate to the project's production directory "LNFreezerAPI" using the terminal.
2. Run the following command to grant access for the browser/Postman to use the API:      
```
$ dotnet run
```

## [API Documentation](#api-documentation)
* Please review the README.md found in the <a href="https://github.com/ian-bravo/LNFreezerAPI">API's repo</a> to view the API documentation.

--------------------

# [Liquid Nitrogen Freezer Organizer Application](#liquid-nitrogen-freezer-organizer-application)

### _This web application uses React to create a inventory system to track many unique specimens._

## [Technologies Used](#technologies-used)

* _HTML_
* _CSS_
* _JavaScript_
* _React_
* _npm v8.1.2_
* _node v16.13.1_

## [Description](#description)

This web application utilizes React to manage a liquid nitrogen freezer inventory system. This application has full CRUD functionality. The user will be able to search and filter based on a number of different fields. This application is a work in progress. User Authentication and Authorization implementation is planned.

<!-- ## Component Diagram

<img src="./src/img/component-diagram.png" alt="component diagram"> -->

## [Setup and Installation Requirements](#setup-and-installation-requirements)

1. Open Terminal.
2. Change your directory to where you would want the cloned directory.
3. Input the following command into your terminal:  
```
$ git clone https://github.com/ian-bravo/ln-freezer-react
```
4. Navigate to the top level of this newly cloned directory.
5. Install all packages with: 
``` 
$ npm install 
```
6. Build the project using webpack with: 
```
$ npm run build
```
7. Start a development server with: 
```
$ npm run start
```
8. Lint JS files in the src folder with: 
```
$ npm run lint
```

--------------------------------

## [Known Bugs](#known-bugs)

* _Work in progress_


## [License](#license)

MIT License  

Copyright (c) 23-Dec-2023 Ian Bravo  

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



_For questions or concerns, please email me at bravo.ian@gmail.com_