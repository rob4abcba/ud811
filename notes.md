
Key Chapters/Sections from Intro to Progressive Web Apps Udacity Course

## L1.4 Technologies behind Progressive Web Apps:

https://classroom.udacity.com/courses/ud811/lessons/8086102617/concepts/80897065570923

Service Workers
- Act as a client-side proxy written in JavaScript
- Can cache assets locally, so no matter what kind of network connection you have, apps load near instantly
- 1:10 Don't even rely on app being open in a browser.
- 1:20 Give PWA's the power to live beyond browsers.


Web App Manifest
- 1:25
- Gives you ability to control appearance

## L1.6 Why use an App Shell

https://classroom.udacity.com/courses/ud811/lessons/8086102617/concepts/80897065590923

Web Page Test : https://www.webpagetest.org/

## L1.9 Weather App Shell

https://classroom.udacity.com/courses/ud811/lessons/8086102617/concepts/80897065640923

The HTML contains:
- header
- empty forecast card
- dialog for adding new cities
- loading indicator

0:18 The forecast card and dialog-container are hidden by default.
The loading indicator is visible.

0:30 Also need to include the styles and any images our app needs to run.

0:45 We could delay the loading of the new city dialog until after displaying 

## L1.10 Start Your Project

https://classroom.udacity.com/courses/ud811/lessons/8086102617/concepts/80897065650923

You can get the project's application code from 1-12-skeleton folder in this course's Github repository: https://www.github.com/udacity/ud811.

If you don't already have a web server installed to serve your project from, the Web Server for Chrome extension can make this simple to do.

0:20 Since Service workers do not work when served from the file system, make sure you working from a local web server in your dev environment.

0:30 Service workers must be served over HTTPS (secure), but to make development easier, that requirement is waived when served from local host.  


## L1.11 Quiz: Update Your Project

https://classroom.udacity.com/courses/ud811/lessons/8086102617/concepts/80897065660923

You can get the project's application code from 1-12-skeleton folder in this course's Github repository: https://www.github.com/udacity/ud811.

0:03 In index.html, 
add a link to hook up stylesheet 

  <!-- Insert link to stylesheet here -->
  <link rel="stylesheet" type="text/css" href="/styles/ud811.css">
  
  <!-- Insert link to app.js here -->
  <script src="/scripts/app.js"></script>
  
0:10 Use WebServer for Chrome, Python Simple, or Apache to serve files

## L1.14. Server-side rendering vs. 
## L1.15. AJAX request vs. 
## L1.16. Injecting Data into JavaScript


