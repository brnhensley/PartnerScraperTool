# ITUNES SCRAPER TOOL

#### By Brian Hensley & Megan Schulte Aug/Sept 2019

## Description

This was an internal tool created as an internship project as part of Epicodus bootcamp. It is built with a C#/.NET CORE API  with Entity Framework Core 2/SQLite back-end and Typescript/React front-end.  The unconventional coding syntax were specific to my internship's internal style guide.

## Setup/Installation Requirements

- clone project
- Run $ _npm install_ in the PartnerScraper directory to install necessary packages
- Run $ _dotnet ef migrations add newMigration_ in the PartnerScraper directory
- Run $ _dotnet ef database update_ in the PartnerScraper directory to create the database
- Run $ _dotnet run_ to start the project on Local Server
- Navigate to https://localhost:5001/ in your browser
- Enter an album's UPC in the search bar to get that UPC's scrape history
- After searching click _SCRAPE NOW!_ to do a new scrape and see if it's currently live on iTunes

## Features

The iTunes Scraper will take an album's UPC and let you know if that album is live on iTunes.

## Known Bugs

- Clicking back in the browser does not refresh the data tables to the current UPC.

## Support and contact details

No further support of this tool is allowed after September 20, 2019.
brnhensley@gmail.com

## Technologies Used

- C#
- .NET Core 2.1
- Entity Framework Core 2
- SQLite
- Typescript
- React
- Webpack
- Node
- HTML
- CSS
- Material-UI

### License

This project can't be used for any commercial purposes and should not be forked.

Copyright (c) 2019 Brian Hensley & Megan Schulte