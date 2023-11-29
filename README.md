# CA3 - ASP.Net Core - Blazor WASM Project

### Project Brief

A Blazor WASM application is required which provides simple interactive functionality to display, visualise and interact with data (JSON) from a public API. One to two pages will suffice for the application. 

Maybe the app has a search capability, or sorting, or paging, or graphing/charting of data, or maybe a calculation of some sort. 

*** 

### Project Description

**API used**: [Open Brewery DB](https://www.openbrewerydb.org/)

**IDE used**: Visual Studio 2022

**UI E2E Testing**: Selenium IDE

**Deployment**: The app is hosted on Azure and can be found [here](https://orange-stone-09d917710.4.azurestaticapps.net/)

**What does this web app do?**

This blazor app displays a list of breweries in Ireland. The list is displayed in a Quick Grid with pagination. The list can be sorted by Brewery Name and can be filtered by county. 

When the more details button is clicked, the user is navigated to the details page for that brewery. On the brewery details page, there is a photo banner displayed at the top of the page, lists some of the brewery details and includes an ìframe` to display a google map of the location for the brewery.


