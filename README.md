Made with Albert Szupszynski and Ravi Kataria for the School of Code Week 3 Hackathon.

Our goal was to build a simple application leveraging a third-party weather API that displays weather data for the user to see in the browser.

We planned out our process in a flow diagram, and then translated this into tickets that we took turns to fulfill.

![flow diagram] ([https://github.com/erinshien/weatherapp/Week3.drawio.png](https://github.com/erinshien/weatherapp/blob/main/Week3.drawio.png))

Ticket 1 ✅
    Set up boiler plate code
    Create HTML elements for weather data

Ticket 2 ✅
    Fetch the data for 1 day of weather from 1 location
        Generate url by selecting relevant data on API website
        Assign url to variable
        Write async/await fetch function

Ticket 3a ✅
    Create functions to locate the relevant data and display in the DOM
        Locate element on the DOM
        Repeat for:
        Temperature
        Weather Type
        Wind Speed
        Sunrise/Sunset
        Add Date

Ticket 3b ✅
    Replace text.content with matching data from AP

Ticket 3c ✅
    Write if statement that returns phrases based on weather code
    Convert sunrise/sunset strings into only the time

Ticket 4 ✅
    Style the elements on the page
        Select background
        Create main container
        Style text - font, sizes, spacing
        Position text elements within container

Ticket 5 - back in the dreamer room!
    Bonus elements:
    Image that change based on data ✅
    Buttons to show the data
    Get location from lat/long data
    Messages based on data (advice/funny comments)
    More than 1 location ✅
