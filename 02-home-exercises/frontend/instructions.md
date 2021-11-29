# 🥷 Frontend Product Exercises 🥷

```
TIMEBOX:    2-4 hours max. We mean it!
LANGUAGES:  Javascript/Typescript
FRAMEWORKS: React and any libraries you want
TESTS:      nice to have, but not mandatory
DOCS:       nice to have, but not mandatory
```

# Overview

This exercise is to implement the best possible solution to one of the exercises below in the time alloted. We're evaluating your ability to take a set of requirements and spike a holistic solution that demonstrates craftsmanship, thoughtfulness and attention to user experience. This is **NOT** a test of how well you know React or ES7+, nor should you try to impress us with overly clever and obtuse solutions. If you want to impress us, build something that is beautiful, intuitive and easy to debug/test/extend :smiley: .

Ideally your solution would have some way to run locally and visualize the results in a browser so we can fully analyze the experience and not just the source code.

## 🤠 Choose **One** Of the following 🤠 

--------------

## Exercise A: Use NASA's APOD REST API to create a photo gallery website

<p align="center">
  <img height="100" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/NASA_logo.svg/2449px-NASA_logo.svg.png">
</p>

In this exercise, you will use [NASA's APOD REST API](https://api.nasa.gov/) to create a photo gallery website. You can either create your own free account to obtain the API-key, or ask us for one. 



### As a visitor of the NASA image gallery, I want to 
* Be able to see the most recent images of the day in gallery format
  * Query the API and recieve image data, date and explanation for each day
  * Present the images in a gallery format with explanation and date
  * Implement pagination for every new month of images
* Be able to filter by date range, or get a random image
  * **stretch goal:** Allow the user to specify date range and view all images from the selected range
  * **stretch goal:** Allow the user to get a random image from the last year

### Visual reference for image gallery websites
<p align="center">
  <img height="600" src="https://uicookies.com/wp-content/uploads/2019/07/photo-gallery-website-templates-featured-image.jpg">
</p>

## Exercise B: Create a weather application using the MET API

<p align="center">
  <img height="100" src="https://info.nrk.no/wp-content/uploads/2019/09/YR_blaa_rgb.png">
</p>

In this exercise, you will use the [MET Weather REST API](https://api.met.no/) to create a weather forecasting website. The user should be able to enter coordinates for a location, and recieve the current weather and the forecast for the coming hours. You can either create your own free account to obtain the API-key, or ask us for one. 

### As a visitor of the weather application, I want to 
* Be able to see the current and future weather of the current day
  * Query the API and recieve weather data in the frontend
  * Create a form to input lat / lon coordinates for querying the API
  * Present the result of the API query visually in the frontend
  * **stretch goal:** Change the color of the website according to temperature, and add icons for different weather types
* Be able to compare the weather in two locations
  * **stretch goal:** Allow the user to query and compare two different locations

### Visual reference for the weather application
<p align="center">
  <img height="600" src="https://miro.medium.com/max/1015/1*q5KRHj8fOUW51y2sqFKW1w.png">
</p>
