# FlickShareUI

### Intro

A simple multi-user web application to manage personal video collections.

### The Problem

There are many individuals who have amassed large collection of DVDs and VHS. Friends and families borrow these from time to time, but owners do not have an easy way manage their libraries nor an easy way to convey/share what they have with friends and families.

### Relevance and Rationale

This web application provides a way to manage video libraries. Facilitates the physical sharing of video libraries collected over the years by different individuals.  These allows a small circle of friends and family members logistically located within driving distance from each other, to share all their video collection in single repository that is searchable and accessible through the web.  

### Target Users

Any groups of individuals that want to share their video libraries or borrow from others. These typically are close friends, family members and neighbors of all ages and background who share a common love for movies.  Typically, these users are within close driving distance as this is not a digital resource sharing app but a physical copy sharing app.

### Overview

The application is intended to be deployed as SaaS.   The initial user has ability to self-register and create a “FlickCircle” where invitations are sent to friends, family and neighbors to register.  Future plans include a mobile version.  

Users will mainly interact with the application using a web browser, and in the future, a mobile application.  The web application will provide a registration page for each new instance of this web application.  The first user becomes the owner/organizer of this instance.  Additional users will be added via an email link sent by the organizer that contains a unique key that has a limited validity time period.  Once registered, each user can add their own videos that they own into the application.

Video information don’t have to be enterer by hand, although an option. They are retrieved via public APIs that can easily be imported into this application.  This will mitigate the daunting task of typing in all the information by hand for hundreds or thousands of videos.

# REST APIs

This project use REST APIs from https://github.com/no3putts/FlickShareService
