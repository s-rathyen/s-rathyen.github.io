---
layout: essay
type: essay
title: "Final Project Idea: Fitness Finder"
date: 2020-03-31
labels:
  - Software Engineering
  - Meteor
---
# Project: Fitness Finder / Gym Genius
<img class="ui small right floated image" src="../images/athlete.png" alt="athlete">
## Overview
<i>The problem:</i> The freshman fifteen! So many students enter and go through college feeling too ashamed to go to the gym alone or feeling afraid to go on a run alone because of safety concerns.<br/><br/>
<i>The solution:</i> The Fitness Finder application allows students to log in to the application and create a profile which specifies things like their gender, interests (e.g. strength training, running, outdoors), level (e.g. just starting, intermediate), "looking for" (e.g. a mentor to help me improve, a friend to keep me company while running, spotter/gym buddy), and goals (e.g. run an 8 minute mile, squat 200 lbs, hike Stairway to Heaven). The app would pair the user with someone with matching/similar interests.<br/><br/>

Advanced implementation would also include the ability to document meetups (for safety or progress tracking), upload photos for each completed outing, and a feed where users can see the completed meetups/workouts their friends/matched users have done.<br/><br/>

<i>Notes on privacy and safety:</i> Users can only sign up if they are current UH students. The website would also warn users when setting up a meeting with a matched user to meet in advance in a public place, like the gym. In the "Beyond the Basics" section I go into detail on a scheduling/progress tracking feature that would allow users to document every single meeting, which should deter other users with dubious intentions.

## Mockup page ideas
Once a user creates his/her profile, the application will automatically match them with users who match their interests, sorted by more complete to less complete matches. A notification bubble will appear over the matched users page whenever new users join who have compatible interests.<br/><br/>

Users are able to contact a user found in the matched users page (or simply search the user by username) to ask if they want to meet up/if they would be interested in scheduling workouts.
 
* Landing page
* User home page
* Admin home page
* User profile page (top part devoted to user profile - interests, level, etc; bottom part devoted to progress tracking -- see "Beyond the basics" for more details)
* Matched users page
* Contact user page which provides user's info (email address, phone number, etc.) (accessible from "message" button on matched users page)

## Use case ideas
* New user: landing page; log in; home page; set up profile; click "find matches" (redirects to matched users page).
* Admin: landing page; log in; home page; edit site.
* Returning user: landing page; log in; matched users page; gets contact information from page.
* (Beyond the basics) returning user: landing page; log in; matched users page; messages user, hears back; schedules workout with user with scheduling feature.


## Beyond the basics
* SCHEDULING PAGE - Users can schedule workouts: If the other user agrees, to a proposed match, they can use a scheduling page to create a new scheduled workout (date, time, place). This workout will be visible to ONLY the two users it concerns to protect their privacy.
* PROGRESS TRACKING - Once the date/time passes for a scheduled workout, it will go into the user's "progress" section of their profile -- something like "(user1name) completed a 2.5 mile run with (user2name) on (date)." The user is then able to go in and edit the workout to add the time it was completed in, as well as add a picture that might have been taken on the run which they want to share. This will be posted to the friend feed if a "public" switch is toggled to on. Things like "place" can be toggled to "private" to protect the privacy of anyone who goes on recurring runs in the same place.
* Progress tracking, ctd: Progress tracking would have an "overall" card displaying your first workout vs. your most recent workout. For example, "first recorded bench press: 100 lb" and beneath it "most recent PR: 200 lbs with (spotterusername)".
* FRIEND FEED PAGE - All public progress cards are displayed for friends and matched users (maybe a feed which includes everyone on site?)
* Users can toggle match finding on/off if they find the perfect gym buddy, so they can instead use the site solely to record their progress.

