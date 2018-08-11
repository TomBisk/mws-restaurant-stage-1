# Restaurant Reviews App (Stage 1)

## Udacity Front-End Nanodegree Program project [6/8] (August 2018)

* [Project Overview](#project-overview)
* [How to run](#how-to-run)
* [Functionality](#functionality)
* [Dependencies](#dependencies)

### Project Overview
For the **Restaurant Reviews** project, general purpose was incrementally convert a static webpage to a mobile-ready web application.
The [provided code](https://github.com/udacity/mws-restaurant-stage-1) has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all.
 
In **Stage One**, project requires to:
* convert a static design to the design responsive on different sized displays;
* correct lacking accessibility for screen reader use (proper semantic elements and ARIA-labels, ARIA-roles, alt attributes for images);
* add a service worker to begin the process of creating a seamless offline experience for the users.

### How to run
To run static website:
* clone the repository  ```git@github.com:TomBisk/feed-reader-testing.git``` or download [zipped file](https://github.com/TomBisk/feed-reader-testing/archive/master.zip);
* from inside the project directory, launch a local client server using Python^ from your terminal: 
  * Python 2: ```python -m SimpleHTTPServer 8000``` ;
  * Python 3: ```python3 -m http.server 8000```;
* visit the site in your browser at ```http://localhost:8000```...

...or you can run [live version](https://tombisk.github.io/restaurant-reviews-app/).

^ You can check your Python version  by using python -V. If you don't have Python installed - download it and install from this [website](https://www.python.org/). 

### Functionality
All reguired functionalities have been tested with the following tools:

To testing responsiveness:
* Chrome DevTools' Device Mode
* my own smartphone :)

To testing accessibility:
* NVDA screenreader and `tab` key.

To testing  service worker:
* `offline` mode for registered service worker in `Application` tab of Chrome DevTools;
* offline mode in my own smartphone :)

To testing general functionality:
* Chrome
* Chrome Canary
* Firefox
* Puffin for Android

### Dependencies
The following resources have been used in this project:

Website:
*  Udacity's [starter code]( https://github.com/udacity/mws-restaurant-stage-1 )

Map:
* [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/)

Service Worker:
* [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API/Using_Service_Workers)
* [Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
* [mickl.net](https://mickl.net/2016/10/24/czym-sa-progressive-web-apps-i-do-czego-mozna-uzyc-service-worker-ow/) (PL)


