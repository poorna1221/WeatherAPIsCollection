# WeatherAPIsCollection


 Introduction

This project aim is to get the weather report as output based on the following scenarios.

 Latitude and Longitude is provided as input
 PostCode is provided as input

	
 Assumptions

I assume following softwares are installed on the machine where this project will be executed.

●	Postman
●	Npm (command to install npm[npm install -g npm])
●	Newman (command to install npm[npm install -g newman])
●	Newman html extra reports (command to install npm[npm install -g newman-reporter-htmlextra])
●	Powershell

Steps for Executing the program:

●	Open the folder named QantasWeatherAPIs.

●	Right click on ExecuteWeatherAPIs.ps1 file which is located inside QantasWeatherAPIs folder->Run with Powershell


●	You will get message as Press enter to accept default value -33.925500 or please enter desired latitude. If you want to provide a specific location latitude you can provide it and API output will be based on provided latitude. If you do not want to provide any latitude and want to let the code take the defaulted latitude -33.925500, then just  press enter.

●	You will get message as Press enter to accept default value 151.186773 or please enter desired Logitude. If you want to provide a specific location Logitude you can provide it and API output will be based on provided Logitude. If you do not want to provide any latitude and want to let the code take the defaulted Logitude 151.186773, then just  press enter.


●	You will get message as Press enter to accept default value AU or please enter desired CountryCode. If you want to provide a specific country code you can provide it and API output will be based on provided country code. If you do not want to provide any country code and want to let the code take the defaulted country code AU, then just  press enter.


●	You will get message as Press enter to accept default value 2020 or please enter desired post code . If you want to provide a specific post code you can provide it and API output will be based on provided postcode. If you do not want to provide any post code and want to let the code take the defaulted postcode 2020, then just  press enter.


●	Provide 1,2 or 3 to select respective environment.

●	Program take around 10 seconds and reports will be stored as newman folder, and also report will be opened automatically for easy access to user.

Note: I have also recorded two videos on how to execute the project and how to view the results with newman. One video shows how to execute the program with default values, and other video with dynamic values for executing the weather API's. Hope you like the project.

