# Progressive-Web-Applications-PWA-Challenge-Text-Editor

Description:

The motivation was to build a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. I learnt about using IndexedDB database, idb, IndexedDB API and Render.

User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
Acceptance Criteria
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
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application

Installation:
For make this application work you shoul instalated Render, where also you deployed it.
 You can take a look to the application here: https://pwa-text-editor-xj19.onrender.com/
If you want to run this application locally you can do:

1) Clone this repository to your computer.
2) Run "npm install" && "npm run" build in your CLI to download the npm package dependencies.
3) Run "npm run start" to start up the backend and serve the client.
4) Navigate to http://localhost:3000 on your local web browser to use the application.

Dependencies:

It`s requires the following npm package dependencies, which are included in client/package.json:
![image](https://github.com/YuliiaPylypiv/Progressive-Web-Applications-PWA-Challenge-Text-Editor/assets/155758070/0aa07f36-fec8-47a6-955f-204460c0a45b)



Getting Started:
Then the text editor, IndexedDB willcreate a database storage and the user will be presented with the main page, depicted below.

![image](https://github.com/YuliiaPylypiv/Progressive-Web-Applications-PWA-Challenge-Text-Editor/assets/155758070/4953c3d0-fa11-4a18-aec3-e41285e21e1c)


After go to Chrome DevTools, you'll see the app details for the registered service worker, manfifest file, and pre-cached static assets.


![image](https://github.com/YuliiaPylypiv/Progressive-Web-Applications-PWA-Challenge-Text-Editor/assets/155758070/28681e3b-f16b-4e65-9184-182fcb40ecbc)


![image](https://github.com/YuliiaPylypiv/Progressive-Web-Applications-PWA-Challenge-Text-Editor/assets/155758070/bcdf77f1-4107-4e99-8045-0541d8f5b5b9)


![image](https://github.com/YuliiaPylypiv/Progressive-Web-Applications-PWA-Challenge-Text-Editor/assets/155758070/58b0607a-a8f4-4214-b10f-0703f6a308ed)


When you pressing the Install button, J.A.T.E. will be downloaded as a Chrome App and can be accessed directly as a desktop shortcut.


![image](https://github.com/YuliiaPylypiv/Progressive-Web-Applications-PWA-Challenge-Text-Editor/assets/155758070/59ee5c54-679d-4c66-88e4-51d05ca94591)


My GitHub link: 
https://github.com/YuliiaPylypiv/Progressive-Web-Applications-PWA-Challenge-Text-Editor.git

Yuliia Pylypiv
