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

## Templates for the Mockup Pages
### Landing Page
![landing page template](/doc/landing.png)

### User Home Page
![user home page template](/doc/userHomePage.png)

### Admin Home Page
![admin landing page template](/doc/adminHome.png)

### Vendor Home Page
![vendor home page template](/doc/landing-after-login-page.png)

### User Profile Page
![user profile page template](/doc/list-stuff-page.png)

### Search Recipe Page
![search recipe page template](/doc/list-stuff-page.png)

### Individual Recipe Page
![individual recipe page template](/doc/list-stuff-page.png)
