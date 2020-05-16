---
layout: project
type: project
image: images/mff-logo.png
title: Manoa Fitness Finder
permalink: projects/witch-hunt
# All dates must be YYYY-MM-DD format!
date: 2020-05-13
labels:
  - web app
  - react
summary: Group web application built with Semantic UI React/Meteor.
---
<a href="https://manoafitnessfinder.github.io/"><i class="large github icon"></i>MFF Project Page</a>

<a href="https://github.com/manoafitnessfinder/app"><i class="large github icon"></i>MFF Repository @ GitHub</a>

## Manoa Fitness Finder: Overview
<img class="ui medium right floated rounded image" src="../images/mff-home.png">
MFF is a web application that helps college students stay motivated with their fitness goals. The site functionality
includes:
* Users can input their fitness interests, goals, and what they are seeking
* Users can find others, view their profiles, and add them as a friend if their interests align
* Users can comment on each other's profiles to connect and plan workouts
* Users can schedule workouts using the 'events' tab; the events are organized into past/future
* Users can join events that their friends have created
Our site facilitates making fitness connections so students can have a gym buddy, running partner, or friend to
help them stay on track and achieve their fitness goals.

## My Contributions
<img class="ui medium left floated rounded image" src="../images/mff-events.png">
The contribution I'm most proud of for the site was creating and organizing the Event cards for the 'My Events' page.
This required me to first create a new Events collection. Then, I had to create the sidebar using Autoforms so that
users are able to create an Event. This was more work than anticipated; in order to keep Events organized into past/future,
I ended up having to use the "moment.js" library to use actual dates and times to make the page more user-friendly.
This was my first venture into using packages, and I'm glad I learned how to do it!

Once the scheduling sidebar was finished, I moved on to organizing Events into two categories, past and future. This
required me to fetch from the Events collection by date, but I had to adjust the times because the time zones were off.

Other than the Event cards, which were used on multiple pages (My Events, Friend Events, User Landing), I also helped
with designing and tweaking the site appearance (colors, buttons, fonts, cards), as well as testing and bug fixing.
Additionally, I designed the user profile pages and worked on the edit pages for user profiles and events.

## My Takeaway
<img class="ui medium right floated rounded image" src="../images/mff-logo.png">
I really enjoyed working on this project. I think that my most important takeaway was learning
a lot about MongoDB Collections. I had to learn how to subscribe and fetch things from a collection, which were the
most confusing parts of the project. I'm happy that I was able to contribute to a major part of the back end and not
just the UI, which I spent a lot of time working on as well. 

I also learned a lot about Issue Driven Project Management (see my essay "What My First Web App Taught Me" for more info)
and how much it helps to manage software projects with a small team. I learned that it took a lot of coordination
and communication to ensure that all of our tasks were being completed and merged smoothly.
