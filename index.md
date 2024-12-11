---
layout: default
---
# **Introduction**

## <u>Table of Contents<u>

# **Professional Self-Assessment**

# **Original Artifact & Code Review**
The artifact that will be enhanced is a full-stack web application called Travlr Getaways. It is built using the MEAN stack which stands for the JavaScript technologies MongoDB, Express.js, Angular, and Node.js. It is designed as a travel booking site for customers to browse and book travel packages. Customers can create accounts and look through travel locations, rooms, and more. There is also an admin-only SPA for maintaining customer accounts, travel packages, and items within. This application was created as a college project from 09/2024 to 11/2024.

This full-stack web application was selected for my ePortfolio because it represents an accumulation of skills acquired through the computer science program. The program presents full-stack web app development, API integration, database management, and using frameworks for front-end and back-end like Angular and Express. The database management component displays working with MongoDB to store and query data on trips, user logins, and more. The API integration component involves using Node.js and Express.js to process requests for data and retrieve them from the database. Using the different frameworks in the MEAN stack, like Angular and Express, also shows efficiency in handling endpoints and HTTP methods so that data can be processed from the front-end to back-end and back.

# **Enhancements**

## **Software Engineering and Design**
The artifact was improved with the implementation of the mailing service. This service allows a user to enter their email in the homepage to receive a welcome email from Travlr Getaways. Once the user enters their email, a JavaScript sends a POST request to the RESTful API after validating the data. This request is validated on the back-end Node.js server as well then calls the mailing service to send an email using NodeMailer. A response on is sent back to the front-end to confirm to user if the email was successful. For a testing and debugging environment, emails are captured using mailtrap.

## **Algorithms and Data Structures**
The artifact was enhanced to add the sorting functionality for the travel page displayed to the user. The original artifact retrieved a list of all trips to be displayed to the user. With the new sorting function, the user can choose the preferred way to list the trips through alphabetically (A-Z) or pricing (Low to High). The sorting options are presented to the user in a dropdown menu.

## **Databases**
The artifact was expanded with this third enhancement focusing on databases. This enhancement took the previous mailing service enhancement and added even more functionality. The general function added is a reservation system which allows users to submit a reservation form and receive confirmation the form was received. The server takes the submitted form, validates and sanitizes it, and then saves the reservation to the database. The server then generates and sends an email containing a read-back of the reservation to the user’s submitted email, as well as a confirmation message within the user’s browser.
