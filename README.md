<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/erinshien/weatherapp">
    <img src="icons/sun_1163662.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Weather App</h3>

  <p align="center">
    A weather app made with Albert Szupszynski and Ravi Kataria for the School of Code Week 3 Hackathon.
    </p>
   <p><a href="https://erinshien.github.io/weatherapp/">View Demo</a></p>
</div>

<!-- TABLE OF CONTENTS -->
   <details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#built-with">Built With</a></li>
          <li><a href="#our-process">Our Process</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

![screenshot of weather app live site](./sitepreview.png)

### Introduction

Our goal was to build a simple application leveraging a third-party weather API that displays weather data for the user to see in the browser.

### Built With

* <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white">
* <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white">
* <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E">

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Our Process

We planned out our process in a flow diagram, and then translated this into tickets that we took turns to fulfill.

![flow diagram of app build plan](./drawio.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Set Up
    - [x] Boiler plate code
    - [x] Create HTML elements for weather data
- [x] Fetch the data for 1 day of weather from 1 location
    - [x] Generate url by selecting relevant data on API website
    - [x] Assign url to variable
    - [x] Write async/await fetch function
- [x] Create functions to locate the relevant data and display in the DOM
    - [x] Locate element on the DOM
    - [x] Repeat for Temperature
    - [x] Repeat for Weather Type
    - [x] Repeat for Wind Speed
    - [x] Repeat for Sunrise/Sunset
    - [x] Add date
- [x] Replace text.content with matching data from API
- [x] Write Logic
    - [x] Write if statement that returns phrases based on weather code
    - [x] Convert sunrise/sunset strings into only the time
- [x] Styling
    - [x] Select background
    - [x] Create main container
    - [x] Style text - font, sizes, spacing
    - [x] Position text elements within container
- [ ] Stretch Goals
    - [x] Image that changes based on data
    - [x] More than 1 location
    - [ ] Buttons to show the data
    - [ ] Get location from lat/long data
    - [ ] Messages based on data (advice/funny comments)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Icons by iconixar](https://www.freepik.com/author/user8839173/icons/iconixar-flat_822?t=f&query=weather)
* [Open Meteo API](https://open-meteo.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


