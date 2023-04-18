# Text Editor Starter Code
<h1 align="center"> Progressive Web Application (PWA) </h1>
  
<p align="center">
    <img src="https://img.shields.io/github/languages/top/jwLeamy/text-editor" />
   
</p>

## Description

Your very own downloadable Text Editor. Use it to add, edit, manipulate text as you please.

## Preview 

![chrome-capture-2023-3-18](https://user-images.githubusercontent.com/111401066/232912299-6085d916-bf9e-4bfa-a1ab-195e0cbe72e4.gif)

## User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```
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
```

## Installation
After cloning the repo to yur local text editor, download dependencies using ```npm i```, and start up the application with ```npm start```. Once opened on localhost:3000 in your browser, you will be able to download the app directly to your computer and enjoy its uses without needed a browser at all. 

  
## Usage
Once installed, you can add and delete text to your liking. Nothing will be deleted unless you want it to, meaning you can close the app completely and your text will remain upon reopening it. 

## DEMO
After starting up the application in your browser (localhost3000), click install to download the app to your personal device. 
![Screen Shot 2023-04-18 at 2 45 07 PM](https://user-images.githubusercontent.com/111401066/232912715-5657b2f3-e35e-4bb5-b610-bbc5ce1f081c.png)
<br />
The following image shows the application's ```manifest.json``` file:
<br />
![Screen Shot 2023-04-18 at 2 38 57 PM](https://user-images.githubusercontent.com/111401066/232912555-68fe2502-26ec-4f98-9596-767799e70812.png)
The following image shows the application's registered service worker:
<br />
![Screen Shot 2023-04-18 at 2 39 15 PM](https://user-images.githubusercontent.com/111401066/232912590-38ba34f4-e4cb-48cb-9bd2-65cfb0e33af2.png)
The following image shows the application's IndexedDB storage:
<br />
![Screen Shot 2023-04-18 at 2 39 33 PM](https://user-images.githubusercontent.com/111401066/232912502-575300f5-a4b8-40fe-98fb-c83faa026f25.png)
