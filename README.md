# COVID-19-World-Vaccination-Progress

This repository contains Python code that does an exploratory analysis, various machine learning techniques and regression analysis to gather insights which would eventually be shown on a data dashboard using Tableau.

We all know how the world has suffered a lot from Covid-19 and how everything is coming back to normal with vaccinations going on in each country. This data has an information on vaccination and its worldwide progress. Below is the data source summary:

Data Source
COVID-19 World Vaccination Progress
(Daily and Total Vaccination for COVID-19 in the World)
The dataset “COVID-19 World Vaccination Progress” is an open source, which I found on Kaggle
Data is collected daily from Our World in Data GitHub repository for covid-19. I rate the data as trustworthy.


Data Collection
Data is collected daily from Our World in Data GitHub repository for covid-19, merged and uploaded. Country level vaccination data is gathered and assembled in one single file. Then, this data file is merged with locations data file to include vaccination sources information. A second file, with manufacturers information, is included.


Data Content
The data (country vaccinations) contains the following information:
• Country- this is the country for which the vaccination information is provided;
• Country ISO Code - ISO code for the country;
• Date - date for the data entry; for some of the dates we have only the daily
vaccinations, for others, only the (cumulative) total;
• Total number of vaccinations - this is the absolute number of total
immunizations in the country;
• Total number of people vaccinated - a person, depending on the immunization
scheme, will receive one or more (typically 2) vaccines; at a certain moment, the
number of vaccination might be larger than the number of people;
• Total number of people fully vaccinated - this is the number of people that
received the entire set of immunization according to the immunization scheme (typically 2); at a certain moment in time, there might be a certain number of people that received one vaccine and another number (smaller) of people that received all vaccines in the scheme;
• Daily vaccinations (raw) - for a certain data entry, the number of vaccination for that date/country;
• Daily vaccinations - for a certain data entry, the number of vaccination for that date/country;
• Total vaccinations per hundred - ratio (in percent) between vaccination number and total population up to the date in the country;
• Total number of people vaccinated per hundred - ratio (in percent) between population immunized and total population up to the date in the country;
• Total number of people fully vaccinated per hundred - ratio (in percent) between population fully immunized and total population up to the date in the country;
• Number of vaccinations per day - number of daily vaccination for that day and country;
• Daily vaccinations per million - ratio (in ppm) between vaccination number and total population for the current date in the country;
• Vaccines used in the country - total number of vaccines used in the country (up to date);
• Source name - source of the information (national authority, international organization, local organization etc.);
• Source website - website of the source of information;
There is a second file added (country vaccinations by manufacturer), with the following columns:
• Location - country;
• Date - date;
• Vaccine - vaccine type;
• Total number of vaccinations - total number of vaccinations / current time and
vaccine type.

