# FORGERY NEWS TRACKER
→ [FORGERY NEWS TRACKER SITE](https://ramtinhaf.github.io/) ←


## Frontend
[FNT-Frontend](https://github.com/RamtinHaf/FNT-FRONTEND)
## Backend
[FNT-Backend](https://github.com/RamtinHaf/FNT-BACKEND-b)

## Problem
The task at hand was: "Given a claim or some fake news the application should track its coverage in various social media platforms." Input to the system would be a textual claim such as "Earth is flat", the expected output would be a visualization of analytics of the coverage in social networks such as Twitter and Reddit. Visualize how many users are sharing, liking, retweeting, how deep the message spreads etc. How does it compare to non-fake news about a similar topic? The main goal of this thesis is to visualize the data, the spread of the query, and compare two different queries. The project group was given the option to choose which languages and programs to achieve the given problem description.

## Goal
As fake news spreads in large numbers worldwide, there is also an increase in non-profit fact-checking organizations. Sites such as [Politifact](https://Politifact.com/) display viral posts and articles and, in turn, label them as false or true; however, Politifact does not show any spread or other analytics. Unlike many other fact checking websites our goal is not to tell the user whether or not a claim is true or false. When it comes to fake fact checking websites we want to contribute by developing a website that allows for users to type in a claim, visualize its spread, check the analytics of it, and compare two dierent claims.

## Technology
A combination of Vue.js, JavaScript, and Python is used to create FNT. This combination is a common practice for web development. JavaScript is used to handle the data that is being passed from the back-end, while Vue.js is the front-end JavaScript framework used to build and design the user interface. 

Python is the chosen language used for creating the back-end part of the application. The back-end uses Python for its framework named Flask. To make the back-end perform the required tasks, multiple external libraries had to be implemented; examples of these are "TextBlob" and "Geocoder." Python was chosen for the back-end part to handle tasks such as API calls, high-speed data sorting, and parsing the data. 

Vue.js framework is used to create components, route on different pages, and handle each search’s different states in the project. The use of components makes the application much more effective; They help extend essential HTML elements to encapsulate reusable code. This means that everything is connected; when routing on a page, the same navigation bar is used everywhere, and Vue knows its exact state using Vuex.
