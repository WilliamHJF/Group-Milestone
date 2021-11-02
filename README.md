Original App Design Project - README Template
===

# GAME LINE

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
[Description of your app]
An app that allows users to browse video games that are popular now and create an account to leave comments on the game page. It could be potentially used as an app for making friends with games

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Social Networking / Game
- **Mobile:** This app would be primarily developed for mobile. Functionality wouldn't be limited to mobile devices, however mobile version could potentially have more features.
- **Story:** Give users a list of popular games and categorize them. Users can also leave comments under the game introduction page so that it gives users a chance to communicate with each other and even become game friends.
- **Market:** Anyone who likes to play video games can choose to use this app. 
- **Habit:** The app can be used as often or unoften as the user wanted depending on when they need to buy a new game or when a new game is announced. 
- **Scope:** We will analyze the types of games people like and taste, and then maybe evolve into a game communication application to expand its use. Great potential for collaborating with Discord or other game communication applications.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User logs in to access previous comments on video games. 
* User can view and scroll through a list of video games that are popular now.
* User can view the video games posters in each row.
* User can view and leave comments on the game page.

**Optional Nice-to-have Stories**

* Users can have chat windows to get to know each other.
* Profile pages for each user.
* Add a tab bar to allow users to view video games in a grid view (Collection View)

### 2. Screen Archetypes

* Login
* Register - User signs up or logs into their account
   * Upon Download/Reopening of the application, the user is prompted to log in to gain access to their profile information to be properly matched with another person.
* Games List Screen
   * Allows users to scroll through a list of video games. 
   * Shows a brief introduction and poster of each video games in each row. 
* Game Details Screen
   * Allows users to get more information about a particular video game. 
   * Allows users to add comments under the introduction article.  
* Comment Screen
   * Allows users to create comment

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Video Games Selection
* Collection View

**Flow Navigation** (Screen to Screen)

* Log-in
  * Register - Account creation if users choose sign up
* Games List/Selection
  * Jump to Game Details Screen when users choose a particular video game. 
  * Then jump to Comment Screen if users choose to add comments. 
* Log-out
  * Go back to Log-in page. 

## Wireframes
<img src="https://user-images.githubusercontent.com/78678541/139945367-90f79431-b674-47d1-b4be-3e7b5d844144.jpeg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
