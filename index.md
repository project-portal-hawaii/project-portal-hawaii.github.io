---
title: "Project Portal Hawaii"
date: 2024-04-04
---
# Project Portal Hawaii
## Team
Adam Bell, Adriel White, Dmitry Gordeev, Gabriel White, and Tim Lum.

[Project Portal Hawaii GitHub Organization](https://github.com/project-portal-hawaii)   
[Team Contract](team-contract.md)   

## Overview
* The problem: For students at UH Manoa, it can be difficult to find interesting projects that will improve the quality of their professional portfolios, or generally improve their skills related to their field of study. 
* The solution: A web application that enables professors or fellow students to post project ideas, and allows students to find the ideal project for gaining experience or earning credit for their classes.   

## Deployment
The application will be deployed on a web server, and will be accessible to anyone with an internet connection and available at address: [Project Portal Hawaii](https://project-portal.live/)   

## Current Functionality
Our App is based on [Bowfolio](https://bowfolios.github.io) template, and currently has the functioning pages: Landing, Sign-up, Sign-in, Avaiable Projects, Single Project, Showcase Projects, Add Project, and Edit Profile.

## User Guide
When entering the application for the first time, select the sign up option from the drop down menu in the top right. Doing so will bring you to this page where you can enter your email and password to register an account.   

### Landing Page
<img src="./images/landing.png" />

When intitially arriving to our site, you will be greeting by our landing page. From here you can make an account, login, or acess other pages.

### Sign-up Page
<img src="./images/sign-up.png" />    

After signing up for an account, you will prompted to create a profile. This can be edited at a later time by visiting the Edit Profile page.   

### Edit Profile Page
<img src="./images/edit-profile.png" />   

If you already have an account, use the same drop down menu and select the sign in option. This will prompt you to enter your email address and password associated with your account.   

### Sign-in Page
<img src="./images/sign-in.png" />   

After signing in, you are able to view different pages that highlight different projects. The Available Projects page lists all projects that are open to students.   

### Available Projects Page
<img src="./images/available-projects.png" />   

If there are too many options to pick from, you can also view a randomized single project using the View a Random Project page.   

### View a Single Project Page
<img src="./images/single-project.png" />   

If you would like to see projects that have been completed in the past, you can do so using the Showcase Projects page.   

### View Showcase Projects Page
<img src="./images/showcase.png" />   

Finally, if you are interested in proposing a project for other students, click on the Add Project page where you can input information for a potential project.   

### Add Project Page
<img src="./images/add-project.png" />   

## Developer Guide
If you are interested in downloading, installing, running, and/or modifying this application, here is the guide to set up your development environment.   

### Clone the Repository
First, clone the repository locally to your computer via our [GitHub Project Portal Hawaii Repository](https://github.com/project-portal-hawaii/pph). Click on the green "<> Code" dropdown menu and clone the repositoy using any prefered method.   

<img src="./images/github-clone.png" />   

## Install Node, Metor, and MongoSH.
Running, editing, and modifying the application requires downloading:
* [Node for JavaScript](https://nodejs.org/en/download)
* [Meteor](https://docs.meteor.com/install.html)
* [MongoSH](https://www.mongodb.com/docs/mongodb-shell/install/)   

## Install packages
Once you have the repository cloned and the required downloades, install packages by navigating to your app directory within pph, and run the following command:   

```meteor npm install```   

<img src="./images/meteor-npm-install.png" />   

## Start Application
After installing the required packages, while in your app/ directory, run the following command to view the application in real time on your local environment:   

```meteor npm run start```   

<img src="./images/meteor-npm-run-start.png" />   

## Begin Modifying
At this point, you can make changes within your IDE of choice and the changes will be displayed immediately by opening the following url in your web browser:    

[http://localhost:3000/](http://localhost:3000/)   


## Development History
The development process for BowFolios conformed to Issue Driven Project Management practices. In a nutshell:

* Development consists of a sequence of milestones M1, M2, and M3; all done on GitHub Project boards.
* Each Milestone is considered as checkpoints that allow for goal oriented actionable items.
* Each task is described using a GitHub Issue, and is assigned to a single developer to complete.
* Each task is estimated and typically separated by most effectively completed by an individual.
* Tasks are arranged by git branch names “issue-XX”, where XX is replaced by the issue number.
* At completion of a task, there is communication with the team in order to mitigate conflict and promote good practice.
* The following sections document the development history of BowFolios.

## Milestone 1: Structure and Understanding
The goal of Milestone 1 was to create the HTML shell of the website and prepare the team with an understanding of the requirements for functionality.

<img src="./images/ssm1.png" />   

## Milestone 2: Data Model Development
The goal of Milestone 2 was to begin adding functionality, build additional superficial design components, and arrange the data model.

<img src="./images/ssm2.png" />   

## Milestone 3: Complete Operational Functionality 
The goal of Milestone 3 is to complete final pieces of functionality, clean up the code, and add the special sauce if time allows.

<img src="./images/ssm3.png" />   

## Project Progress
* [Milestone 1](https://github.com/orgs/project-portal-hawaii/projects/1)
* [Milestone 2](https://github.com/orgs/project-portal-hawaii/projects/2)
* [Milestone 3](https://github.com/orgs/project-portal-hawaii/projects/6)   
  
![ci-badge](https://github.com/project-portal-hawaii/pph/workflows/ci-project-portal/badge.svg)

## Deployed Live Site
<a href="https://project-portal.live/">Project Portal Hawaii</a>

## Testimonials
Claudia Mena-Rieke (CS Major second year):
“I love the site! I can definitely see myself using this in the future. Though, some of the design and colors could use a little adjusting. Other than that its great!”
* Sign up page, mobile UI issue
* “One last thing, this page doesn’t make it obvious to what’s required for upload ()”referencing Add Project page”
* “And the image doesn’t change sizes to fit the new screen size ok, I’m done now” referencing ‘random project page’

Maddie Hatanaka (Micro-Bio major second year):
* “I think it’s cool. It looks professional. I would use it.”
* “I hate being late for an exam!” Runs off after rigorous studying

Ken Munekata (Economics major third year):
“So, this is to open opportunities and promote successful ones? The concept is great! It seems easy enough to understand and use. I am curious about some parts of information though.” 
* Form boxes, unsure of what to input

Jenny Brown (Electrical Engineering major third year):
“Love the idea, issues that stick out is not being able to expand on the discriptions and maybe filtering for the types of projects I want to see. Also maybe add photos or expand more if the person wants to onto the project? Lmk if this is enough-thanks for thinking of me”

Kyla Lee (CS major 3/4 year):
“I like that the showcase platform can show you the past project boards. Thats a very valuable tool because others can get ideas. The fonts are a little different regarding scientific standards queue rant on fine details Overall, very cool.
