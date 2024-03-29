# Agenda-WebApp

## Requirements for the Agenda Web App
### Purpose

The main objective of this web app is to provide users with a tool for daily activity planning and management.

## Functional Requirements
### User Registration

Users should be able to create an account using an email address and a password. (User)

It should be possible to log in with the registered credentials. (User)

### Event Creation
- Users should be able to create events by specifying a title, date, and time. (User)
- The option to add additional details to the event, such as description, location, and categories, should be provided. (User)

### Viewing and Managing Events
- Users should be able to view a list of scheduled events. (User)
- It must be possible to edit or delete previously created events. (User)
- Events should be sorted by date and time. (System)

### Notifications
- Users should be able to set notifications for events, with options for email or in-app notifications. (User)

### Search and Filters
- The web app should allow users to search for events by date, title, or category. (User)
- Filter options should be provided to simplify event viewing. (User)

## Non-Functional Requirements
### Security
- The web app must ensure the security and protection of user data. (System)
- User passwords must be encrypted during storage. (System)

### Usability
- The application should have an intuitive and user-friendly user interface. (User)
- The interface design should be responsive to support desktop and mobile devices. (System)


### Backup and Restore
- A periodic data backup system for user data should be implemented. (System)
- Users should be able to restore data in case of loss or errors. (User)


### Database
- A database management system should be used to store user data and events. (System)



# UML Diagram

![alt text](http://yuml.me/f16ec5ae.jpg)

# WBS

![alt text](Wbs.png)

# User Stories

## User Registration
* As a user, I want to be able to create a new account using my email address and a password so that I can access the web app.

* As a user, I want to log in with the credentials I provided during registration to access my personalized account.

## Event Creation

* As a user, I want to create events by specifying a title, date, and time to plan my daily activities.

* As a user, I want the option to add additional details to my events, such as description, location, and categories, for better organization.

## Viewing and Managing Events

* As a user, I want to view a list of my scheduled events sorted by date and time.

* As a user, I want to be able to edit or delete events I have created.

* As a user, I want to set notifications for my events, with options for email or in-app notifications, to stay informed about my planned activities.

## Search and Filters

* As a user, I want to search for events by date, title, or category to quickly find the information I need.

* As a user, I want filter options to simplify the viewing of events based on specific criteria.
