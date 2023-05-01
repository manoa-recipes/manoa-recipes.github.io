# Manoa Recipes

## Overview

The purpose of this application is to provide college students (on-campus or off) easy access to learn and share recipes that:
- Can be made using minimal kitchen facilities (at a minimum, a toaster oven).
- Can be made out of ingredients that are available within walking distance of UH.
- Suit local taste sensibilities.
- Can be filtered via dietary restrictions (gluten-free, vegan, etc).
- Have an estimated cost per serving.
- Has an estimated number of servings per recipe.
- Has an estimate of how long it takes to make.

## Goal
The goal of this site is to help improve the nutritional content and variety of foods eaten by students and help them limit the use of vending machines or fast food products by providing tasty, realistic alternatives.

There are three roles in this system: students, vendors, and admins.

Students can both search for and contribute recipes. Recipes not only include the typical description of how to prepare the food and a picture of the completed food, but also information on where to obtain each ingredient and how much each ingredient costs. The recipe also indicates typical dietary restrictions for students (vegan, gluten-free, etc.).

Students do not necessarily have to determine the price associated with each item. Instead, there is another interface to the system for vendors. Vendors (local grocery stores and/or farmer’s markets) can login and establish a profile including their location and hours. Then, for each ingredient defined in the system, they can indicate:
- Whether they stock the item.
- How much it costs to buy the item.
- What is the size of the item.

From this information, the system can automatically calculate for each recipe:
- All of the places near campus where each ingredient can be found.
- What the prices are for each ingredient at each place.

Information on ingredient price and availability can be contributed either by vendors or by students.

There is also an admin role. Admins can edit all content in the system, remove inappropriate content, and establish users as having the vendor role.


## Developer Guide
1. [Install Meteor](https://docs.meteor.com/install.html)
2. [Download a copy of Manoa Recipes.](https://github.com/manoa-recipes/manoa-recipes-application)
3. cd into the app directory and download the required libraries with: ```$meteor npm install```
4. Once the libraries are installed, you can run the application by invoking: ```$meteor npm run start```
5. You can run ESLint over the code in the imports directory with: ```$meteor npm run lint```

**NOTE:** the first time you run the app, it will create some default users and data.


## User Guide
### Landing Page
When you first bring up the application, you will see the landing page that provides a brief introduction to Manoa Recipes.
![landing page](/doc/landing-page.png)

### Sign In
Click on "Login", then on "Sign In" to bring up the Sign In page.  This will allow you to login to the application. 
![sign in page](/doc/sign-in-page.png)

### Sign Up
If you do not yet have an account, you can register by clicking on "Login", then "Sign Up."  You have the option of registering as either a regular user or a vendor.  Depending on which role you choose, different features will be available to you.
![sign up page](/doc/sign-up-page.png)

### User Home Page
After successfully logging in, you now have access to your home page featuring a randomly selected recipe.  You now also have access to the Add Recipe, List Recipe, Vendor and your Profile pages.
![user home page](/doc/user-home-page.png)

### Add Recipe Page
Clicking on the Add Recipe link allows you to add your own recipe to the application.
![add recipe page](/doc/add-recipe-page.png)

### List Recipe Page
Clicking on the List Recipe link brings up a page that lists all of the recipes uploaded to the application.
![list recipe page](/doc/list-recipe-page.png)

#### Recipe Description
Clicking on one of the recipe cards will bring up the instruction page for that particular recipe.
![recipe description](/doc/recipe-description-page.png)

### Vendor Page
Clicking on the Vendor link brings up a page that lists all of the vendors currently registered in the application.
![list vendor page](/doc/list-vendors-page.png)

### User Profile Page
If you are a user, you have access to a user profile page that lists your allergies and whether you're vegan and/or gluten-free.
![user profile page](/doc/user-profile-page.png)

#### Edit User Profile
From the User Profile page, you can click "Edit" to alter the information shown in your profile.
![edit user profile page](/doc/edit-profile-page.png)

### Vendor Profile Page
If you are a vendor, you have access to a vendor profile page that lists your address, hours and the products you sell.
![vendor profile page](/doc/vendor-profile-page.png)

### Admin Mode
It is possible to designate one or more users as "Admins" through the settings file.  When a user has the Admin role, they have access to a special Admin page that lists all of the data uploaded to the application (ex. ingredients, profiles, etc).
![admin page](/doc/admin-page.png)

### Deployed Page
Here is a [link](https://manoa-recipes.site/) to our deployed page.

### Testface
![testface](/doc/Testcafe.jpeg)

### Github action
[![manoa-recipe](https://github.com/manoa-recipes/manoa-recipes-application/actions/workflows/ci.yml/badge.svg)](https://github.com/manoa-recipes/manoa-recipes-application/actions/workflows/ci.yml)


## Community Feedback


## [GitHub Organization](https://github.com/manoa-recipes)

## [Team Contract](https://docs.google.com/document/d/1MJt64tX4oWzQhcEswiNezfdqCrEvjX_fnbmLACwksA0/edit?usp=sharing)

## Projects
- [M1 Project Page](https://github.com/orgs/manoa-recipes/projects/4)
- [M2 Project Page](https://github.com/orgs/manoa-recipes/projects/6)
- [M3 Project Page](https://github.com/orgs/manoa-recipes/projects/7)
