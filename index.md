# Table of contents

* [About RCL808](#about-rcl808)
* [Installation](#installation)
* [Application design](#application-design)
  * [Directory structure](#directory-structure)
* [Development History](#development-history)
  * [Milestone 1](#milestone-1)
  * [Milestone 2](#milestone-2)

# Links
[Link to Webpage](https://rcl808.meteorapp.com/)  
[Link to GitHub Repository](https://github.com/rcl808/rcl808)  

# About RCL

Rad Club List (RCL) is a web application which offers a comprehensive listing of all clubs and organizations on the University of Hawaii at Manoa Campus. RCL only contains registered independent organizations (RIO) at the University of Hawaii at Manoa. Clubs are list by categories and contain information such as details about club activities, social media links, contact information and other information about the clubs. Users can create their own accounts and favorite and add themselves to organizations which they are a part of. Leaders of clubs will also have editing privileges to their own club and can modify their club pages.

# Application Walkthrough

#### Landing Page

When users first visit the website, they are first greeted by the landing page. If the user is not logged in, the user will be greeted by a login banner and an option to explore popular club categories.

<img src="./img/landing-page-m2.jpg" />

The homepage of RCL808 features a top menu bar where users can login. In the main section of the page, several clubs will be featured using cards and popular categories are also listed with cards below. Users are also able to search for particular clubs and can create a club if they are logged in.

<img src="./img/create-a-club-page-mockup-m1.png" />

Users can navigate to The create a club page where users can obtain all of the documents to create a club at the University of Hawaii at Manoa. Once this club is registered, the website will be updated from the official club list.

<img src="./img/explore-by-category-page-mockup.png" />

Users can search for a club using the search menu. An alternative way to find clubs is to sort the clubs by category.

<img src="./img/club-page-mockup-m1.png" />

Once a user has found a club that they are interested in, users can navigate to the club's page and view information about the club.

# Installation

Installation of this application requires the meteor framework, npm and node.  

#### Installing meteor:  
```
choco install meteor
```
#### Updating NPM:
```
Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force
npm install -g npm-windows-upgrade
npm-windows-upgrade
```
#### Running the Application:
```
meteor npm install
meteor npm run start
```

# Application Design

## The backend structure

Our application is created by a combination of meteor, galaxy, and mlab. Galaxy and mlab are used to host and store database. Meteor is used as the main framework to build and design RCL808. The structure of the application is showned below:

```
client/
  main.html         # Contains the headings for the application and background color
  main.js           # Import all the files in this application for it to run smoothly
  style.css         # Front-end customizations

imports/
  api/              # Create schema for the database of the application
  startup/          # Contains the codes to run what the system starts
  ui/               # Contains all the codes for all the front-end component of the application
                    # to interaction with the users and with each other.

node_modules/       # Contains the roots of Meteor.

public/             # Contains all the images to be used on the front-end.
  images/
```

# Development History

## Milestone 1

Upon completing this milestone, there would be various mockup HTML pages to be used on our application.

Milestone 1 has a total of 10 issues. All of them are managed [here](https://github.com/rcl808/rcl808/projects/1)
Below is a screenshot of this milestone.

<img src="./img/milestone1.png" />

The issues are first created in the "Backlog" column. Each member chooses what he would like to work on by dragging the chosen issue into the "In Progress" column. Whenever the issue is resolved, the member can drag it to "Done" column and close it.

The html pages we created for this milestone are:

* Landing page

* Login page

* Home Page

* Create Club Page

* Edit Club Page

* Create Event Page

* Edit Event Page

## Milestone 2
[Link to Milestone 2](https://github.com/rcl808/rcl808/projects/2)
