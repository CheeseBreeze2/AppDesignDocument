 

App Design Document
AirBnP Bathroom Finder/ Restaurant Finder
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 

Created: April 11th, 2024
Developer:
Isaac Martinec
University of Pittsburgh at Bradford


Table of Contents 
Introduction
Purpose	
Scope
References
System Overview
System Components 
User Interfaces (GUI)
Detailed Design 
Pseudocode






























Introduction
Purpose 
The Software Design Document describes the design of the app whether it be an app to find bathrooms, or an app to find restaurants. If the app is AirBnP then the app will be used to help people who need a public bathroom be able to find public bathrooms. If the API does not allow bathrooms to be found the app will instead be used to find restaurants nearby which the API should be able to do.

The purpose of the project is to help people who need either a bathroom or a place to eat to be able to see nearby locations quickly rather than just hoping for a bathroom or googling in the case of a restaurant.

Scope 
The document will explain how the app runs, consisting of the app and API that powers it and how. Those along with React being able to find the location of the user make up the components of the app.

The app is planned to be quite simple, just showing a map and the nearby locations of what the app will be whether that be bathrooms or restaurants. It is planned to be created in about 3 weeks working one day a week, but if more time is needed, the schedule is flexible if done by April 24th.

References  
-Google Maps API
-React  
-https://docs.expo.dev/tutorial/introduction/
-Google Gemini 

System Overview 
The code creates the app and React was used to create the app and is used to be able to retrieve the location of the user using the user’s devices. After the app loads the user’s location then the API will place the user at the user’s location. Then the API will either show nearby bathrooms or restaurants depending on what app is created.

System Components 
The app is coded in VS Code using NodeJS and created using React. The app loads Google Maps using the Google Maps API. The code is generated using Google’s AI tool Gemini. 


User Interfaces (GUI) 
The User Interface for the app has not been designed yet, but I plan for after the user to be able to scroll around and zoom in and out to find nearby bathrooms or click on restaurants for information on them. If the restaurant app is done, then maybe I will try and make it so it shows nearby restaurants on the side of the user’s screen.

Detailed Design 
Pseudocode 
App shows default location on google maps 
Request default location information with Google’s API
Google returns default location 
Uses phone to get current location 
Request current location information from Google API
Google’s API returns current locations info 
App renders current location
