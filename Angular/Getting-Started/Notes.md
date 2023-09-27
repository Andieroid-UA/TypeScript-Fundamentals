# Quickstart for a New Angular Setup

npm install -g @angular/cli@latest

cd documents/github/[myprojectfolder]/Angular/[specificprojectname]

ng new my-first-app --no-strict

Choose "CSS"

npm install --save bootstrap@3

ng serve (to test)

## 1. What is Angular

- A JS framework that allows us to create reactive single-page reactions
- Much faster than just using JS, changes a single page instead of refreshing the whole thing and loading a different page
- Changes HTML code during runtime, only the currently loaded page

## 2. Angular vs Angular 2 vers

- Only Angular 1 and 2+ are different (Angular JS the OG and Angular), complete re-write. Other versions are just updated each 6 months but no real differences

## 3. Angular Setup & First App
#### My Notes:
- Need to run the server in my project's terminal!

npm install -g @angular/cli@latest

cd documents/github/TypeScript-Fundamentals/Angular

ng new my-first-app --no-strict (going to start in non-strict mode)

Choose n for "Angular Routing" for now

Choose CSS style sheet

cd my-first-app

ng serve (this will bring up a development server, so you can see the app in the browser!)

#### Notes from instructor:
To ensure that this works, for the moment, make sure that you have the LTS version of NodeJS installed, NOT the latest version (from https://nodejs.org/en/).

Especially double-check that you have npm version 6 installed - it's a tool that's installed together with NodeJS.

We need that tool to install the Angular CLI and create new Angular projects with that CLI.

Since npm v7 can cause issues, you should ensure that you use v6. Therefore, also run npm install -g npm@6 to ensure that you are using that version (on macOS, you might need to add sudo in front of that command).

Thereafter, you can proceed to creating a new Angular project.

If you want to dive deeper into the CLI and learn more about its usage, have a look at its official documentation: https://github.com/angular/angular-cli/wiki

You encountered issues during the installation of the CLI or setup of a new Angular project?

A lot of problems are solved by making sure you're using the latest version of NodeJS, npm and the CLI itself.

Updating NodeJS:

Go to nodejs.org and download the latest version - uninstall (all) installed versions on your machine first.

Updating npm:

Run [sudo] npm install -g npm (sudo is only required on Mac/ Linux)

Updating the CLI

[sudo] npm uninstall -g angular-cli @angular/cli 

npm cache clean 

[sudo] npm install -g @angular/cli 

Here are some common issues & solutions:

Creation of a new project takes forever (longer than 3 minutes)
That happens on Windows from time to time => Try running the command line as administrator
You get an EADDR error (Address already in use)
You might already have another ng serve process running - make sure to quit that or use ng serve --port ANOTHERPORT  to serve your project on a new port
My changes are not reflected in the browser (App is not compiling)
Check if the window running ng serve displays an error. If that's not the case, make sure you're using the latest CLI version and try restarting your CLI

#### 4. Editing the First App

Our IDE is going to be VSC (because it is free, and the add-ons are bomb)

Keep your project running on the server! If you are finished enter in the command:

ng serve

ctrl + c

- It allows us to mix static html code and dymanic things we want to mix with that code!
- Angular split into several sub-modules, sub-packages
- "App module" which pieces belong to our app

Yay! My first app is a text box where I can edit a line of text in real time!

#### 5. The Course Structure

Going to dive into the basics. Components and what did we do with 2-way data binding?

*Components and Databinding*
Angular... and things. Idk what this guy is talking about yet.

*Directives*
2 way databinding is an example of this. Depends on the commands you put in there.

*Services and Dependency Injection*
Centralize code, and manage state of app

*Routing*
Always on one page, but introduce management of URLS, so to the user it looks like multiple pages when it's just one

*Observables*
REALLY powerful...

*Forms*
Handling user input is the key task, this section takes a close look at it

*Pipes*
Easy to export the output at runtime and play

*Http*
If you need to reach out to a webserver/access to a server

*Authentication*
Security

*Optimization & Different Modules*

*Deployment*
How to get from local to the interwebs

*Animations & Testing*

#### 6. TypeScript

- TypeScript is a superset to JS, more than vanilla JS
- Define if a certain variable is a number, string, or something!

#### 7. Basic Project Setup Using Bootstrap for Styling

npm install --save bootstrap@3

Make Angular aware of the Bootstrap styling package in the "angular.json" file

