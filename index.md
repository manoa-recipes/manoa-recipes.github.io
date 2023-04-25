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

## User Guide
### Landing Page
![landing page](/doc/landing.png)

### Sign In
![sign in page](/doc/sign-in.png)

### Sign Up
![sign up page](/doc/sign-up.png)

### User Profile Page
![user profile page](/doc/user-profile-page.png)

### User Home Page
![user home page](/doc/user-home-page.png)

### Add Recipe Page
![add recipe page](/doc/add-recipe.png)

### Admin Page
![admin page](/doc/admin.png)

### Deployed Page
Here is a [link](http://137.184.30.50/) to our deployed page.


## Developer Guide
1. [Install Meteor](https://docs.meteor.com/install.html)
2. [Download a copy of Manoa Recipes.](https://github.com/manoa-recipes/manoa-recipes-application)
3. cd into the app directory and download the required libraries with:

```$meteor npm install```
4. Once the libraries are installed, you can run the application by invoking:

```$meteor npm run start```

**NOTE:** the first time you run the app, it will create some default users and data.

5. You can run ESLint over the code in the imports directory with:

```$meteor npm run lint```


## [GitHub Organization](https://github.com/manoa-recipes)

## [Team Contract](https://docs.google.com/document/d/1MJt64tX4oWzQhcEswiNezfdqCrEvjX_fnbmLACwksA0/edit?usp=sharing)

## Projects
- [M1 Project Page](https://github.com/orgs/manoa-recipes/projects/4)
- [M2 Project Page](https://github.com/orgs/manoa-recipes/projects/6)
- [M3 Project Page](https://github.com/orgs/manoa-recipes/projects/7)
