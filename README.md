# WeatherScraping Tool with Python

Group Number: 
Member of the Group: Chiara Georgiadis (17-607-136), David Matern(), Nicolas Hebeisen (17-605-643), Thomas ()

** About**
This project is part of the Advanced Programming course, conducted at the University of St. Gallen.
The goal of the project was to create a weather scraping tool using the predefined website SRF METEO
It needs to be noted that the language of the website is German and can't be changed to English.
To avoid ambiguity, we refer to the translations paragraph, where keywords of the project are translated.
The project was inspired by the following tutorial: https://www.dataquest.io/blog/web-scraping-tutorial-python/ 

** Motivation **
The process of obtaining data from a source is called data extraction. 
This can be carried out manually or automatically. 
It can be used to get information from many different places, like files, databases, and websites. 
This is especially useful when the public website doesnt have an API or only provides limited access to the data. 
This project is our groups first attempt at extracting data from a public website. 
The skills acquired in this process will certainly be very helpful for future projects, be it at the university or at a professional level.

** Pre-requisites **
The project works with Python3
In order to run the program, the following libraries need to be installed:
BeeautifulSoup, requests

** Instructions **
1. Start Code
2. Enter the location of your choosing
3. Read the comments in the code for a more detailed description of the code
4. Receive detailed weather forecast for the chosen location of the following 6 days

** Translation of keywords/sentences **
-Input-
Von welchem Standort möchten Sie das Wetter wissen?: From which location would you like to know the weather?
Mögliche Standorte: Possible Locations

-Output-
Heute : today
Morgen : tomorrow
Übermorgen : day after tomorrow
Montag: monday
Dienstag: tuesday
Mittwoch: wednesday
Donnerstag: thursday
Freitag: friday
Samstag: saturday
Sonntag: sunday

Temperatur: temperatur
Tag: day
Nacht : night
Regenmenge: rainfall

** Sources **
Tutorial: https://www.dataquest.io/blog/web-scraping-tutorial-python/
Weather Website: https://www.srf.ch/meteo
