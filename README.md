# What is it
This is a website with map and detail information for restaurants in the New York City area.

The base code for this website was provided by Udacity. This is a project I worked on while completing my Nanodegree in Front End Web Development.

The project was to make the website UI more compatible with different display sizes, accessible, and add a service worker to cache the site for offline usability.

# Where to get it
To access, download or clone from:

- https://github.com/feliciamdavis/mws-restaurant-stage-1

or

By following these steps in your terminal:

```
cd Desktop/(wherever you want this to be on your computer)

git clone https://github.com/feliciamdavis/mws-restaurant-stage-1
```

Open `index.html` in your web browser.

or

Just go to it directly using this link:

- https://feliciamdavis.github.io/mws-restaurant-stage-1/

# How to use it
Load the main page to see a map and a list of restaurants. You can filter using neighborhood or food type. Or you can scroll down through all of the restaurants. When you find a restaurant you are interested in, click 'View Details' for more information about the restaurant. If you want to go back to the main page, click the home button at the top left of the page.

# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
