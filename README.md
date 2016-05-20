![Logo](https://github.com/DaveShaffer/WDI6-outFttr/blob/master/images/outFttr.png)
# outfttr
### PROJECT 3
#### General Assembly
##### Web Development Immersive
##### Cohort 6
##### Developers: Brad Hughes, Dave Shaffer, Gatina Foy and Sydney Smith
#
###### Atlanta, GA, USA
#
#

For project three, we formed teams to draft, design and create a full-stack server-side JavaScript API (Application Program Interface) using Node.js, MongoDB and Express.js.  We practiced Git flow (project version control) on GitHub and communicated on Trello and Slack to manage team collaboration.

Deployed App: <https://outfttr.herokuapp.com/>

## TECHNOLOGIES AND TOOLS
 - MongoDB relational NoSQL database
 - Mongoosejs mongoDB object modeling for node.js
 - Three related models: User, Items of clothing and an Outfit
 - All major CRUD (Create, Read, Update and Delete) functions
 - Express.js JavaScript framework
 - Node.js JavaScript runtime
 - ReSTful (Representational State Transfer) practices
 - AJAX (Asynchronous JavaScript and XML) XMLHttpRequest object
 - Bootstrap framework
 - clean and well-formatted CSS (Cascading Style Sheets)
 - Heroku cloud app hosting
 - GitHub software repository
 - AWS-SDK module with Amazon S3 (Simple Storage Service) cloud storage
 - Authentication and Authorization stategies with Passportjs middleware
 - Trello project manager
 - Slack messaging app
 - OpenWeatherMap weather API
 - IP-API Geolocation API

## GENERAL APPROACH
When we first met, we presented project proposals and voted on the best.  Next, we brainstormed some our models for our project on the white board then pitched our idea to our instructors.  After receiving their feedback, we sketched out our plans on Trello.  Over the weekend we started individual tasks: a new git repo was created with a basic express framework and models, the logo sketch was submitted to an artist, image hosting was setup on S3 and began security coding with Passport.  On Monday we began creating routes and views and started bootstrap integration, sketched wireframes, researched the OpenWeatherMap API and finished passport security.

## INSTALLATION INSTRUCTIONS
New users create an account and build a database (closet) of pant, shirts, dresses and shoes.  Then they can check the weather forecast, scroll through their closet and create an outfit.  When each item is displayed, there will be a checkbox letting the user know if it is clean and when was the last time the item was worn.

## USER STORIES
> Wendy Waxler is about to be late for work.  She has to be in her car and driving to work in less than an hour or she'll hit peak rush-hour traffic.  If only there was some way for her to look through her closet and put an outfit together while she was eating breakfast and putting on makeup.  Along comes outfttr and her prayers are answered.  With her smart phone she can see today's forecast, which items of clothes need to cleaned and when each item was last worn.  She knows it should rain later today, so she plans to wear boots instead of sandals.  Since the high temperature is predicted to only be 45, she is going to wear her wool blazer, except it is at the cleaners.  So she picks out a sweater instead.  When she's ready to get dressed, she has already decided what to wear, she grabs each item and gets ready to rule the day.

>Outfttr makes a great travel companion.  Denny Donner went to downtown Denver for a Downton Abbey Final Episode Donnybrook.  Thanks to outfttr's cutting edge geolocation and weather forecasting technologies, he was prepared for the 90 degree temperatures and 50 mph winds that day by choosing to wear a t-shirt and shorts, but no hat.  As a result, Denny Donner made the Denver Downton Downtown Donnybrook without breaking a sweat or losing his hat and met his future wife, Diedre.

## SITE MAP

![Site Map](https://github.com/DaveShaffer/WDI6-outFttr/blob/master/images/SiteMap.png)

## WIREFRAMES

![Signup Page](https://github.com/DaveShaffer/WDI6-outFttr/blob/master/images/SignupPage.png)

![Home Page](https://github.com/DaveShaffer/WDI6-outFttr/blob/master/images/HomePage.png)

![Create an Outfit](https://github.com/DaveShaffer/WDI6-outFttr/blob/master/images/CreateOutfit.png)

![View Outfits](https://github.com/DaveShaffer/WDI6-outFttr/blob/master/images/MyOutfits.png)


## MAJOR HURDLES
 - routing
 - Heroku hosting
 - AWS hosting
 - displaying the Items
 - displaying User info because of Passport
 - styling with Bootstrap
 - OpenWeatherMap API working on Heroku
 - Responsiveness

## FUTURE VISION
 - Make the app more mobile-friendly and responsive
