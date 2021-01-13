# dscrt.ly

## Description

A couple of friends wanted to integrate a Twilio API into a simple Webflow application they had worked on, which they wanted to use to  gauge whether users would be interested in a social media app they wanted to build. One friend would send out links to the application, along with an invite code, to friends and they would navigate to the website, enter in the invite code, and then be prompted to provide in their phone numbers. The application would then save their phone numbers to a database and a follow-up text would be sent to their phones.

Since Twilio did not support Webflow, it was impossible to integrate the API without some finessing. Although Twilio did not support Webflow, I researched that it does support Node. And since Node does provide server-side rendering for CSS/HTML, and since I also learned I could export the Webflow application out of Webflow as CSS/HTML, I figured out how to create a Node application with server-side rendering, rendering the Webflow content, with a Twilio API integration.

Having created the Node application, I was then able to also integrate the Intl-Tel-Input API for phone number validations, a Firebase database for storing phone numbers. And I was able to deploy the application to Firebase.

Technologies: Nodejs, Webflow, Twilio API, Intl-Tel-Input API, Firebase Database, Firebase Hosting

## Goals

The following are what I learned on the project:
  
  <ol>
  <li>Gained additional practice working on view engine templating for server side rendering.</li>
  <li>Gained additional practice working with Nodejs.</li>
  <li>Worked with Twilio API</li>
  <li>Worked with Intl-Tel-Input API for validating phone numbers</li>
  <li>Worked with Firebase Database and hosting</li>
  </ol>

## Link to deployed application
Link: https://dscrt.ly

## Screen shots of the application

![Screen Shot 2020-08-13 at 3 59 23 PM](https://user-images.githubusercontent.com/46943342/90181477-837f5780-dd7e-11ea-9c1e-530ac9292f9a.png)
