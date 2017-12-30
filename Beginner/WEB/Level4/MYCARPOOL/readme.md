# Module 

Title : MyCarPool App
Version : 1

## Introduction
---
You are engaged by a web agency that provides full service to non-governmental organizations with an environmental or social focus. The current customer needs a platform for car sharing. Your task is to implement the backend persistence and interaction logic. They will provide you with a design and template for the frontend later. Until then you just use the logo provided together with really simple HTML-code as provided by the framework of your choice.

## Description of project
---
Using car sharing, people that travel a certain route (driver) can offer to give a lift to other people (passenger). The system should cover the following user stories / test cases:

##### Basic features

>- A user (driver or passenger) can login (and logout) into the system on the start page of the application.
>- After login there are the following links to sub-pages: “Available offers”, “Requested routes”, “My routes offered” (as driver), “My routes booked” (as passenger).
>- These links are always visible on the top part of the page while logged in.
>- For each user a field indicating the state (locked, inactive, active) can be stored in the database.

##### Available routes features

>- On a page called “Available offers” the user (driver or passenger) will see a list of all available routes (including their own): date and time, source location, target location, name of driver, average rating and number of ratings given.
>- This list only shows the routes available (not booked routes) from the current date and into the future.
>- The user (driver) can add a route they would like to offer (form below the list).
>- The user (passenger) can book a route (link on right to the list entry).

##### Request routes features

>- On a page called “Requested routes” the users will see all routes that are requested by themselves or by others: date and time, source location, target location, name of driver, average rating and number of ratings given.
>- This list only shows the routes requested (booked routes) from the current date and into the future.
>- The user (passenger) can add a route they would like to request (form below the list).
>- The user (driver) can book a route they want to drive and give a lift to someone (link on right to the list entry).

##### My routes features

>- On a page called “My routes offered” the user will see all routes they have offered as a driver and are/were booked/used by another user: date and time (future in bold, past normal), source location, target location, name of passenger, rating given.
>- They will be able to rate that user (passenger) on a scale from 0 to 5.

##### My booked routes features

>- On a page called “My routes booked” they user will see all routes they have booked as a passenger: date and time, source location, target location, name of driver, rating given.
>- The user (passenger) will be able to rate the user (driver) on a scale from 0 to 5.

## Notes
---
- Time always reflects full hours only (no minutes)

## Requirement
---
- Any PHP framework (recomended : Laravel & Yii )
- Any SQL Database (recomended : Mysql, Oracle, Sqlite)

## References
---
```
Will update later - [nexxa](https://github.com/neonexxa) (or can request directly from the author)
```

## Contributors & Authors
---
1. [Neonexxa](https://github.com/neonexxa)
