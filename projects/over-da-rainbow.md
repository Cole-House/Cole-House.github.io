---
layout: project
type: project
image: images/ODR-logo.png
title: Over Da Rainbow
date: 2022-05-10
labels:
  - Web Application
  - Software Engineering
  - Agile Project Management
  - Meteor
summary: Deployed Web Application made as final group project for ICS 314
---

<img class="ui large floated centered rounded image" src="/images/ODR-landing.png">

  Over Da Rainbow is the name of a meteor web application which used the [meteor-application-template-react](“https://ics-software-engineering.github.io/meteor-application-template-react/”) and was developed by Ruben Jacobo, Timothy Ro, Kevin Nahinu, and myself as our final project for our Software Engineering class. This app is designed to help University of Hawaii students step outside their dorms and classrooms to explore beautiful sceneries and destinations offered on Oahu responsibly with a sense of community. Along with information about locations across the island on the application you can learn about various campus spots, volunteer opportunities and leave reviews documenting your experiences for any location/spot in the database. You can learn more about our application and view the source code through our GitHub home page [here](“https://over-da-rainbow.github.io/”) and view our deployed site using Digital Ocean [here](“https://overdarainbow.xyz/#/”).

## My Contributions to the project:
* Came up with the name for the application
* Participated in constant issue driven project management with other group members. We were able to easily view what tasks needed to be done and what tasks everyone is working on through the use of a Project Board on Github. We also had team meeting face to face or on Discord at least twice a week.
* Logo Design (image enhancement help from friend Gage Minamoto)

* <img class="ui large centered rounded image" src="/images/ODR-logo.png">


* Helped with the research of different locations for data entry, obtaining all the info needed for the locations schema.
* Modifying the Signup Form to take info for the user's profile. I modified the semantic ui react _form_ to add forms and dropdowns that take the user's email/username, password, first and last name, class year, avatar choice, short bio, and their instagram username. These inputs are submitted and creates a new user with their information saved to their profile.

*  <img class="ui large centered rounded image" src="/images/ODR-signup.png">


* Built the User Profile Page that displays the user’s info. You can view this through a dropdown in the top right of navbar, where the username is displayed. 

* <img class="ui large centered rounded image" src="/images/ODR-profile.png">


* Used Semantic UI React to build Location Cards from the database records, displaying the specific location's information in card format and populating the Beach, Hikes, Views, Campus Spots, and Volunteer pages with all records in their respective collections.

* <img class="ui large centered rounded image" src="/images/ODR-cards.png">

* Developed the Review Modal Form which includes Review Collection and Schema. This feature is a button labeled "Review" and located on every location page, that once clicked pops up a modal form that intakes a user's experience at that location and a rating out of 5 stars. The user's review upon submitting will show up below the "Review" button for all logged in users to see. The modal was tricky to get working with the state changes, and the 5 star rating system was not working at first but through some guidance from my TA Branden Ogata we were able to get it working properly. 

* <img class="ui large centered rounded image" src="/images/ODR-review.png">

* Implement functionality of clicking on other user’s usernames and taking them to their profile. This feature can be used on both the "Event" and "Message Board" Pages of the Bulletin, and was also implemented for username's associated with reviews but that change has not been deployed yet.

## What I gained from this experience:

  This was my first ever web application project and the first one to be deployed online for the world to use! With this final project it was a very enjoyable expereince where we put in use almost all the software engineering concepts we learned in class. I got an intro to software project management with issue dirven project management 

