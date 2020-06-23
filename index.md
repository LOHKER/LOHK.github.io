## Table of Contents
* [Overview](#overview)
* [Functionality Goals](#functionality-goals)
* [User Guide](#johnsonslist-walkthrough)
* [Installation](#installation-and-running)

## Overview

Johnslists list is a website utilizing semantic ui, react.js, meteor, and mongoDB to create a website that can be used by students to trade common goods. Community members of UH Manoa can add common goods, such as textbooks or appliances, that they no longer need and create listings with details about said item. 

For more information on the techstack used:
* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code. 
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [MongoDB](https://www.mongodb.com/) Backend Database for adding objects 

## Functionality Goals

* Two types of users: Regular and Admin (Both of which log in from the same page, but get directed to different home screens)
* Profiles can be customized to display a picture and a description of the person
* Add listing, edit listing, and view listings usability features (Regular users can only add/edit their own while admins can have functionality for all listings)
* Listings can be filtered depending on what specifically the user is looking for (Ex. textbooks specifically for biology)
* Users can flag or report listings that are not related to what the site's purpose is for to admins.

## Johnsonslist Walkthrough

Johnsonslist will feature a selection of pages for the user to comb through. There will be a screenshot of each page below with a description of usability.

## Landing/Home page

![](app/public/images/homepage.jpg)

The homepage will feature navigation to the multiple tabs. The user will be directed here upon start up of application and can navigate without logging in, however, will have limited usability.

![](app/public/images/dropdown.jpg)

The dropdown at the top left of the homepage will allow users to specifically be directed towards the page that they wish to see.
## Installation and Running

To intially run the application, [install Meteor](https://www.meteor.com/install).

```
$ meteor npm install
```

From there, one must do the following command to start up the application:

```
$ meteor npm run start
```

If done correctly, the application will appear at [http://localhost:3000](http://localhost:3000). 
