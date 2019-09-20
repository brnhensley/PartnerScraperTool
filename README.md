# ITUNES SCRAPER TOOL

#### By Megan Schulte & Brian Hensley Aug/Sept 2019

## Description

This was an internal tool created as an internship project as part of Epicodus bootcamp. It is built with a C#/EF Core/Sqlite back-end and Typescript/React front-end.

## Setup/Installation Requirements

- clone project
- Run $ _npm install_ in the PartnerScraper directory to install necessary packages
- Run $ _dotnet ef migrations add newMigration_ in the PartnerScraper directory
- Run $ _dotnet ef database update_ in the PartnerScraper directory to create the database
- Run $ _dotnet run_ to start the project on Local Server
- Navigate to https://localhost:5001/ in your browser
- Enter an album's UPC in the search bar to get that UPC's scrape history
- After searching click _SCRAPE NOW!_ to do a new scrape and see if it's currently live on iTunes

## Screen Shots of running project

## Features



# Current Features:



## Known Bugs

- Clicking back in the browser does not refresh the data tables to the current UPC.

## Support and contact details

Create a pull request on GitHub.

## Technologies Used

- C#
- .NET 2.1
- Entity Framework Core 2
- SQLite
- Typescript
- React
- Webpack
- npm
- HTML
- CSS
- Material-UI

### License

This project can't be used for any commercial purposes and should not be forked.

Copyright (c) 2019 Megan Schulte & Brian Hensley
