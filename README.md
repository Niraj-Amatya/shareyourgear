# ShutterShare

Completed as Term 2 Ruby on Rails assessment at [Coder Academy's](https://coderacademy.edu.au/) GenTech 2019 Bootcamp.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Important Links](#important-links)
* [Description](#description)
    - [Purpose](#purpose)
    - [Features](#features)
    - [Sitemap](#sitemap)
    - [Screenshots](#screenshots)
    - [Target Audience](#target-audience)
    - [Tech stack](#tech-stack)
* [User Stories](#user-stories)
* [Wireframes](#wireframes)
* [ERD Diagram](#erd-diagram)
* [Components](#components)
* [Third Party Services](#third-party-services)
* [Models and Associations](#models-and-associations)
* [Database Relations](#database-relations)
* [Database Schema](#database-schema)
* [Project Management](#project-management)

<!-- R7	Identification of the problem you are trying to solve by building this particular marketplace app. -->
<!-- R8	Why is it a problem that needs solving? -->

 ([Back to Table of Contents](#table-of-contents))
## Problem Statement

- What

    To get started with photography a photographer not only requires to have a decent camera but plethora of accessories and lenses. For example, a typical professional level photo shoot requires a good camera body, at least two to three fast aperature lenses, a couple of lights (strobes or speed lights), light modifiers, light stands etc... Therefore it would be very costly to own all the gear when someone starts with the photography. In another use case there are situations where a specific kind of lens is required ony for specific kind of photography genre and it's not very practical to buy a new lens for one off use.
    
    In the kind of situations described above it would be very convenient to be able to get rent someone else's equipment, use and return it when done.
    
    The biggest problem is that due to the niche involved there are very few places who rent out equipment and due to the lack of competition the demand drives the prices which does not work well for small time individual photographers.
    
    Therefore it would add a lot value by creating an online platform that would bring photography community together that can help each other by sharing the gear and make some extra money.

- Why
    
    The platform needs to be online because in online space there are even less providers that encourages sharing the photography gear among the photographers. The options that exists are limited to specific camera brand, or are not two sided, or are mainly focused on big production houses or otherwise does not operate in Australia.
    
    Therefore it is important have an online platform which is brand independent and caters to individual photographers within Australia. Moreover having an online platform gives scalability to bring photography community from different locations to come together and cater to each other's photographic equipment requirements.

 ([Back to Table of Contents](#table-of-contents))

<!-- R9	A link (URL) to your deployed app (i.e. website)
R10	A link to your GitHub repository (repo). -->

## Important Links

- Project: https://shuttershare.herokuapp.com/

- GitHub Repo: https://github.com/hirengondhiya/shuttershare

<!-- R11	Description of your marketplace app (website), including:
- Purpose
- Functionality / features
- Sitemap
- Screenshots
- Target audience
- Tech stack (e.g. html, css, deployment platform, etc) -->
 ([Back to Table of Contents](#table-of-contents))

## Description
    
- ### Purpose

    The purpose of this app is to create a two sided online marketplace for photographer to rent out their camera gear. 

- ### Features
- ### Sitemap
- ### Screenshots
- ### Target Audience
    Target audience of this app is any photographer who would like to rent someone else's photo gear and/or rent out their own photography equipment. This way the person renting someone's equipment can avoids costs associated with owning the gear that is not frequently used and the users renting out can have more value out of their investment. 
- ### Tech stack
    * Ruby on Rails
    * HTML
    * CSS
    * SASS
    * Bootstrap 4
    * Bootstrap Studio
    * Heroku
    * Amazon S3
    * 

([Back to Table of Contents](#table-of-contents))
<!-- R12	User stories for your app -->

## User Stories

* ### User Management
    
    #### Features
    
    - **Sign up**:
    
        As a site visitor, I should be able to sign up with my email id and create a password.
        
    - **Sign in**:
    
        As an existing user, when I am not signed in, I should be able to sign in using the credentials that I signed up with.
        
    - **Sign out**:
    
        As a Signed in User, I should be able to Sign out of my signed in account. 
        
     
* ### Profile Management

    #### Features
    - **Edit Profile**:
        
        As a signed in user, I should be able to update my public information which is visible on my profile.
    - **Upload Profile Pic**:
        
        As a signed in user, I should be able to upload my profile picture that is visible to other users.
    - **Delete Profile Pic**:
        
        As a signed in user, I should be able to delete my profile picture.
    - **View Profile**:
    
        As a signed in user, I should be able to view my profile and any of the listing owner's profile.
* ### Listing Management
    #### Features
    - **Create listing**:
        
        As a signed in user, I should be able to create a new listing for my gear.
    - **Update listing:**
        
        As a signed in listing owner, I should be able to update previously created listing.
    - **Delete listing**:
        
        As a signed in listing owner, I should be able to delete previously created listing.
    - **Upload photos for listing**:
        
        As a signed in user, I should be able to upload photos to the listing created by me.
    - **View individual listing**:
        
        As a site visitor, I should be able to view an individual listing.
    - **View all listings**:
        
        As a site visitor, I should be able to view all the listings on the site. 
* ### Lease Management
    #### Features
    
    - **Request for lease**:
    
        As a signed in user, I should be able to send one and only one lease request per listing from all users except my own listings.
        
    - **Cancel lease request**:
        
        As a signed in lease request owner, I should be able to cancel lease request when it's pending for listing owner's approval.
        
    - **Accept or Reject**:
    
        As a listing owner, I should be able to accept or reject the lease request on my own listings only.
        
    - **View all lease requests received**:
        
        As a listing owner, I should be able to view all lease requests received on my listings.
    - **View all lease requests made**:
    
        As a signed in user, I should be able to view all lease requests that I made on someone else' listing.
            
 ([Back to Table of Contents](#table-of-contents))

<!-- R13	Wire frames for your app -->

## Wireframes

 ([Back to Table of Contents](#table-of-contents))

<!-- R14	An ERD for your app -->

## ERD Diagram

![ER Diagram](./docs/er-diagram.svg)

([Back to Table of Contents](#table-of-contents))

<!-- R15	Explain the different high-level components (abstractions) in your app -->

## Components

([Back to Table of Contents](#table-of-contents))

<!-- R16	Detail any third party services that your app will use -->

## Third Party Services

The app uses following third party services,

- Amazon S3: 
    
    A cloud based blob storage service, provided by Amazon AWS, to hold all the images uploaded by the users of the app.
- Heroku: 

    A cloud based hosting provider to be able to deploy the app on cloud and access it using the internet. 

([Back to Table of Contents](#table-of-contents))

<!-- R17	Describe your projects models in terms of the relationships (active record associations) they have with each 
other -->

## Models and Associations

([Back to Table of Contents](#table-of-contents))
<!-- R18	Discuss the database relations to be implemented in your application -->

## Database Relations

([Back to Table of Contents](#table-of-contents))
<!-- R19	Provide your database schema design -->

## Database Schema

([Back to Table of Contents](#table-of-contents))
<!-- R20	Describe the way tasks are allocated and tracked in your project -->

## Project Management

([Back to Table of Contents](#table-of-contents))