# PWA-Text-Editor

The task in this project was to build a text editor that runs in the browser. The app was to be a single-page application that meets the PWA criteria. Additionally, it had to feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application had to also function offline.

To build this text editor, we were to start with an existing application and implement methods for getting and storing data to an IndexedDB database. we were required to use a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

The app was to finally be deployed to Heroku

# A) The user Story for the app was:

AS A developer

I WANT to create notes or code snippets with or without an internet connection

SO THAT I can reliably retrieve them for later use

# B) The Acceptance Criteria for the app was:

GIVEN a text editor web application

WHEN I open my application in my editor

THEN I should see a client server folder structure

WHEN I run `npm run start` from the root directory

THEN I find that my application should start up the backend and serve the client

WHEN I run the text editor application from my terminal

THEN I find that my JavaScript files have been bundled using webpack

WHEN I run my webpack plugins

THEN I find that I have a generated HTML file, service worker, and a manifest file

WHEN I use next-gen JavaScript in my application

THEN I find that the text editor still functions in the browser without errors

WHEN I open the text editor

THEN I find that IndexedDB has immediately created a database storage

WHEN I enter content and subsequently click off of the DOM window

THEN I find that the content in the text editor has been saved with IndexedDB

WHEN I reopen the text editor after closing it

THEN I find that the content in the text editor has been retrieved from our IndexedDB

WHEN I click on the Install button

THEN I download my web application as an icon on my desktop

WHEN I load my web application

THEN I should have a registered service worker using workbox

WHEN I register a service worker

THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets

WHEN I deploy to Heroku

THEN I should have proper build scripts for a webpack application

# C) A mock-up demonstrating the expected functionality of the app:

![19-pwa-homework-demo-01](https://user-images.githubusercontent.com/108309963/207440123-0471c6d6-6768-4c1d-97d0-048472450ca5.gif)

# D) The link to the app deployed on Heroku which demonstrates the final functionality of the app:

