## Welcome to UHM Food Mood

UHM Food Mood is the solution to the ever-growing number of meal choices at UH Manoa. Once you log into your UHM Food Mood app, you can learn what menu items are available today and keep track of which of your food favorites are available today.

See our GitHub Organization <a href = "https://github.com/uhm-food-mood">here</a> and our deployed app on Galaxy <a href = "http://uhmfoodmood.meteorapp.com/#/">here</a>. Also see our GitHub repository for our UHM Food Mood website <a href = "https://github.com/uhm-food-mood/uhm-food-mood">here</a> and the GitHub repository for this website <a href = "https://github.com/uhm-food-mood/uhm-food-mood.github.io">here</a>.

In addition, see our M1 Project page <a href = "https://github.com/orgs/uhm-food-mood/projects/1">here</a>, our M2 Project page <a href = "https://github.com/orgs/uhm-food-mood/projects/2">here</a>, and our M3 Project page <a href = "https://github.com/orgs/uhm-food-mood/projects/3">here</a>.

### Goals

The main goals of UHM Food Mood are to:
- Provide a consolidated directory of UHM menu items from UHM Food Vendors and Manoa Dining Services
- Give students a way to easily find their favorite foods on campus
- Give students food suggestions that they might like on campus

### What this app will provide

Ultimately, we hope that the app will provide the following:
- Users will be able to log in and find their favorite foods on campus
- Vendors will be able to change menu items depending on their weekly/daily menu

### Overview

UHM Food Mood aims to provide a consolidated catalog of food options at UH Manoa. Although there are existing catalogs of food options on campus, such as <a href = "http://manoa.hawaii.edu/food/">UHM Food Vendors</a> and <a href = "https://uhm.sodexomyway.com/">Manoa Dining Services</a>, there are no catalogs that contain every food option on campus. We aim to make UHM Food Mood the website you look to for food options whenever you're hungry on campus. Eventually, we would like to give users the ability to rate food options so other students will know what's popular on campus.

### User Guide

Here is a guide through our existing mockup pages on our deployed website.

#### Landing page:
![landing](images/Landing.png)

The Landing page is the homepage for all users. It has a summary of the purpose of UHM Food Mood and a section that shows what student's "top picks", or most highly rated food options are. Currently, the top picks are just static data, as we have not implemented the review system yet. Click Login at the top right corner to log into your existing account or to create a new account.

See the Landing page <a href = "http://uhmfoodmood.meteorapp.com/#/">here</a>.

#### Food Options Page:
![options](images/FoodOptions.PNG)
Without logging in, you can still view all the food options available. Each card shown displays the name, image, vendor, availability, style, and price of the food. There is also an option to "favorite" the food by clicking on the heart button, but you must be logged in for this function to work.

You can also use the search bar to search through the food options. Search by the name of the food:
![search!](images/NameSearch.PNG)
Or by the style of the food:
![search!](images/EthnicitySearch.PNG)
Or by vendor:
![search!](images/VendorSearch.PNG)
Or if it's vegan:
![search](images/VeganSearch.PNG)
Or even a mixture of both:
![search](images/NameStyleSearch.PNG)

See the Food Options Page <a href="http://uhmfoodmood.meteorapp.com/#/allListings">here</a>.

#### Food Listings Page

![listings](images/FoodListings.PNG)

The Food Listings page showcases all of our vendors. Like the Food Options page, you do not need to be logged in to view this page.

See the Food Listings page <a href="http://uhmfoodmood.meteorapp.com/#/listings">here</a>.

#### User Favorites Page:
![homepage](images/Favorites.PNG)

As a regular user, you can favorite your favorite foods from the Food Options. These favorited foods will appear in your Favorites page. If you want to delete any of your favorites, you just need to click on the trash can button at the bottom left of the card. Like the Food Options page, you have the same search functionality using the search bar at the top left. In the future, we will ensure that the foods that are available right now will appear at the top of your favorites.

See the Favorites page <a href = "http://uhmfoodmood.meteorapp.com/#/list">here</a>

#### Vendor Listing Page:
![vendor](images/VendorListings.PNG)

As a vendor, you can add new listings and edit or delete your existing listings. Your listings will all be shown in the Vendor Listings page. To add a new listing, you will need to click on the "Add Another" link at the bottom of the page. To edit an existing listing, click on the Edit link at the bottom left corner of the card containing the listing. To delete a listing, click "Remove" at the bottom of the card. You also have the same search functionality for your own listings, using the search bar at the top left corner.

See the Vendor Listings page <a href = "http://uhmfoodmood.meteorapp.com/#/vendor">here</a>

#### Vendor/Admin Add Listing Page:

![add listing](images/AddPage.PNG)

As an admin/vendor, you can utilize the Add Listing Page to add new food listings. You will need to enter the name of the food, the URL to the image of the food, the name of the vendor, the price, whether the food is vegan, the style of the food, the date when the food will be available from, and the times when students can purchase the food. Click the submit button and it will create a new listing with the provided information. 
![added](images/AddSuccess.PNG)

See the Vendor/Admin Add Listing Page <a href = "http://uhmfoodmood.meteorapp.com/#/add/">here</a>

#### Vendor/Admin Edit Listing Page:

![edit](images/EditPage.PNG)
As an admin/vendor, you are also given the ability to use the Edit Listing Page to edit food listings. All the previous information about the food listing is already filled in, all you need to do is edit the parts that you would like to change. Once you have finished making your changes, click submit.
![changed](images/EditSuccess.PNG)

If you have received this notification, you have successfully edited the menu item.

See an example of a Vendor/Admin Edit Listing Page (each menu item has a unique URL for their edit page) <a href="http://uhmfoodmood.meteorapp.com/#/edit/4u9kNpbJJNCn4PBKE">here</a>.

#### Admin Listings:
![listings](images/Admin.PNG)

As an admin, you can edit, remove, and add new food listings. Admins can also view all food listings from all vendors. In addition, you can search through all these listings using the search bar at the top left corner.

See the Admin Listings Page <a href = "http://uhmfoodmood.meteorapp.com/#/admin">here</a>

#### Review Page
![review](images/Review.PNG)
In addition, we have added a mockup of our Review page for M3. This Review page will give users the ability to review a menu item, which will be shown publicly to encourage (or discourage) other users to try the food in question.

See the Add Review Page <a href = "http://uhmfoodmood.meteorapp.com/#/review">here</a>.

### Community Feedback

We have gotten a couple of students to review our prototype so far. Many students believe that a consolidated menu of all food options on campus would be a very helpful resource. 

A few possible improvements mentioned by these students are mainly regarding the User Interface, such as using lighter typefaces and varying the font size.

In the future, as we implement more functionality, we intend to carry out further tests with students - especially regarding the user interface and navigation.

### Developer Guide

#### Installation
The first thing you will need to is install <a href="https://www.meteor.com/install">Meteor</a>. 

Next, download <a href="https://github.com/uhm-food-mood/uhm-food-mood">UHM Food Mood</a>. 

Then, cd into the app/ directory of your local copy of the repo and install third party libraries with:
```
meteor npm install
```
You will also need to install Moment using:
```
npm install moment
```
Once you've installed the libraries, run the application with the following command:
```
meteor npm run start
```
The first time you run the app, it will create some default users and data. This is the output:
```
C:\Users\Kelli\Documents\GitHub\uhm-food-mood\app>meteor npm run start

> meteor-application-template-react@ start C:\Users\Kelli\Documents\GitHub\uhm-food-mood\app
> meteor --no-release-check --settings ../config/settings.development.json

[[[[[ C:\Users\Kelli\Documents\GitHub\uhm-food-mood\app ]]]]]

=> Started proxy.
=> Started MongoDB.
W20191203-20:28:53.339(-10)? (STDERR) Note: you are using a pure-JavaScript implementation of bcrypt.
W20191203-20:28:53.413(-10)? (STDERR) While this implementation will work correctly, it is known to be
W20191203-20:28:53.414(-10)? (STDERR) approximately three times slower than the native implementation.
W20191203-20:28:53.428(-10)? (STDERR) In order to use the native implementation instead, run
W20191203-20:28:53.432(-10)? (STDERR)
W20191203-20:28:53.445(-10)? (STDERR)   meteor npm install --save bcrypt
W20191203-20:28:53.449(-10)? (STDERR)
W20191203-20:28:53.462(-10)? (STDERR) in the root directory of your application.
I20191203-20:28:53.978(-10)? Creating the default user(s)
I20191203-20:28:53.983(-10)?   Creating user admin@foo.com.
I20191203-20:28:54.310(-10)?   Creating user john@foo.com.
I20191203-20:28:54.636(-10)?   Creating user vendor@foo.com.
I20191203-20:28:55.170(-10)? Creating default data.
I20191203-20:28:55.180(-10)?   Adding: Eggplant Parmesan (vendor@foo.com)
I20191203-20:28:55.203(-10)?   Adding: Moussakka (vendor@foo.com)
I20191203-20:28:55.212(-10)?   Adding: Thai Green Vegetable Curry (vendor@foo.com)
I20191203-20:28:55.229(-10)?   Adding: Thai Red Vegetable Curry (vendor@foo.com)
I20191203-20:28:55.234(-10)?   Adding: Lamb/Beef/Chicken Wrap (vendor@foo.com)
I20191203-20:28:55.254(-10)?   Adding: Lamb/Beef/Chicken Plate (vendor@foo.com)
I20191203-20:28:55.260(-10)?   Adding: Lamb/Beef/Chicken Salad (vendor@foo.com)
I20191203-20:28:55.281(-10)?   Adding: Garlic Yogurt Sauce (vendor@foo.com)
I20191203-20:28:55.286(-10)?   Adding: Coffee (Hot/Cold/Blended) (vendor@foo.com)
I20191203-20:28:55.290(-10)?   Adding: Donuts (vendor@foo.com)
I20191203-20:28:55.341(-10)?   Adding: Lunch Sandwiches (vendor@foo.com)
I20191203-20:28:55.342(-10)?   Adding: Breakfast (vendor@foo.com)
I20191203-20:28:55.344(-10)?   Adding: Khichdi (vendor@foo.com)
I20191203-20:28:55.345(-10)?   Adding: Strawberry Halava (vendor@foo.com)
I20191203-20:28:55.346(-10)?   Adding: Peanut Butter Halava (vendor@foo.com)
I20191203-20:28:55.348(-10)?   Adding: Pineapple Coconut Halava (vendor@foo.com)
I20191203-20:28:55.349(-10)?   Adding: Tuna Melt Panini (vendor@foo.com)
I20191203-20:28:55.380(-10)?   Adding: Grilled Cheese Panini (vendor@foo.com)
I20191203-20:28:55.384(-10)?   Adding: Chicken Chipotle Panini (vendor@foo.com)
I20191203-20:28:55.406(-10)?   Adding: Turkey Avocado Panini (vendor@foo.com)
I20191203-20:28:55.411(-10)?   Adding: Corn Tacos (vendor@foo.com)
I20191203-20:28:55.432(-10)?   Adding: Burritos (vendor@foo.com)
I20191203-20:28:55.464(-10)?   Adding: Quesadillas (vendor@foo.com)
I20191203-20:28:55.468(-10)?   Adding: Tamales (vendor@foo.com)
I20191203-20:28:55.488(-10)?   Adding: Shave Ice (vendor@foo.com)
I20191203-20:28:55.493(-10)?   Adding: Sorbet Bowls (vendor@foo.com)
I20191203-20:28:55.517(-10)?   Adding: Poke Nachos (vendor@foo.com)
I20191203-20:28:55.517(-10)?   Adding: Acai Bowls (vendor@foo.com)
I20191203-20:28:55.539(-10)?   Adding: Beefy Miso Ramen (vendor@foo.com)
I20191203-20:28:55.544(-10)?   Adding: Beefy Spicy Ramen (vendor@foo.com)
I20191203-20:28:55.565(-10)?   Adding: Beefy Wild Ramen (vendor@foo.com)
I20191203-20:28:55.568(-10)?   Adding: Pork Gyoza (vendor@foo.com)
I20191203-20:28:55.589(-10)?   Adding: Chicken Katsu (vendor@foo.com)
I20191203-20:28:55.594(-10)?   Adding: Loco Moco (vendor@foo.com)
I20191203-20:28:55.613(-10)?   Adding: BBQ Chicken (vendor@foo.com)
I20191203-20:28:55.618(-10)?   Adding: Grilled Garlic Ahi (vendor@foo.com)
I20191203-20:28:55.640(-10)?   Adding: Egg Masala (vendor@foo.com)
I20191203-20:28:55.644(-10)?   Adding: Vegetable Masala (vendor@foo.com)
I20191203-20:28:55.664(-10)?   Adding: Tofu Sambal (vendor@foo.com)
I20191203-20:28:55.811(-10)?   Adding: Vegetable Sambal (vendor@foo.com)
I20191203-20:28:55.816(-10)?   Adding: Cheese Louise (vendor@foo.com)
I20191203-20:28:55.837(-10)?   Adding: Pesto- Pesto (vendor@foo.com)
I20191203-20:28:55.842(-10)?   Adding: Nutella (vendor@foo.com)
I20191203-20:28:55.864(-10)?   Adding: Shoyu Ahi Poke Bowl (vendor@foo.com)
I20191203-20:28:55.868(-10)?   Adding: Shoyu Tako Poke Bowl (vendor@foo.com)
I20191203-20:28:55.890(-10)?   Adding: Miso Ahi Poke Bowl (vendor@foo.com)
I20191203-20:28:55.896(-10)?   Adding: Miso Tako Poke Bowl (vendor@foo.com)
I20191203-20:28:55.917(-10)?   Adding: Orange Chicken (vendor@foo.com)
I20191203-20:28:55.941(-10)?   Adding: Beef Broccoli (vendor@foo.com)
I20191203-20:28:55.946(-10)?   Adding: Mushroom Chicken (vendor@foo.com)
I20191203-20:28:55.967(-10)?   Adding: Honey Walnut Shrimp (vendor@foo.com)
I20191203-20:28:55.991(-10)?   Adding: Black/Green Iced Tea (vendor@foo.com)
I20191203-20:28:55.995(-10)?   Adding: Hot Cocoa (vendor@foo.com)
I20191203-20:28:56.017(-10)?   Adding: Cold Cereal w/Fruit (vendor@foo.com)
I20191203-20:28:56.052(-10)?   Adding: Ice Cream Sundae (vendor@foo.com)
I20191203-20:28:56.057(-10)?   Adding: Fish Jun Plate (vendor@foo.com)
I20191203-20:28:56.091(-10)?   Adding: Kalbi Bibimbap (vendor@foo.com)
I20191203-20:28:56.116(-10)?   Adding: Steak Plate (vendor@foo.com)
I20191203-20:28:56.141(-10)?   Adding: Homemade Kimchi (vendor@foo.com)
I20191203-20:28:56.145(-10)?   Adding: Cappuccino (vendor@foo.com)
I20191203-20:28:56.145(-10)?   Adding: Macchiato (vendor@foo.com)
I20191203-20:28:56.176(-10)?   Adding: Latte (vendor@foo.com)
I20191203-20:28:56.179(-10)?   Adding: Mocha (vendor@foo.com)
I20191203-20:28:56.201(-10)?   Adding: Pho (vendor@foo.com)
I20191203-20:28:56.226(-10)?   Adding: Pad Thai (vendor@foo.com)
I20191203-20:28:56.230(-10)?   Adding: Banh Mi Sandwiches (vendor@foo.com)
I20191203-20:28:56.251(-10)?   Adding: Spring Rolls (vendor@foo.com)
I20191203-20:28:56.274(-10)?   Adding: Smoothies (vendor@foo.com)
I20191203-20:28:56.278(-10)?   Adding: Oatmeal Bowl (vendor@foo.com)
I20191203-20:28:56.278(-10)?   Adding: Apple Cinnamon Pretzel (vendor@foo.com)
I20191203-20:28:56.304(-10)?   Adding: Banana Toast (vendor@foo.com)
I20191203-20:28:56.324(-10)? Creating default reviews.
I20191203-20:28:56.328(-10)?   Adding Review: Nachos (john@foo.com)
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.
```
#### Viewing UHM Food Mood
If the app was installed correctly, you will be able to view it at http://localhost:3000/. You can login using the credentials in <a href="https://github.com/uhm-food-mood/uhm-food-mood/blob/master/config/settings.development.json">settings.development.json</a>.
### Development History
#### Milestone 1
In Milestone 1, we created the Landing page and four mockup pages - the User Favorites page, the Vendor Listings page, the Vendor/Admin Add Listing page, and the Admin Listings page. We added a small amount of functionality to the Admin Listings page, as admins are able to remove listings from the Admin Listings page. We also set up the schema for and MongoDB collection of food options (MenuItems Collection), so all of the information on the cards that appear on our app is pulled from our database.
#### Milestone 2
For Milestone 2, we greatly improved the functionality of our website. All users can search through the Food Options page by name, vendor, style of food, or even whether a food is vegan. Regular users are now able to use the "favorite" function so that the foods they favorite will show up in their "Favorites" page. Vendors are able to add new listings and edit/remove existing listings that they own. Admins possess the same abilities of vendors, but are able to use these abilities on all listings, including ones they do not own. We also added an immense amount of default data, 72 menu items - 4 sample food items from 18 vendors. In addition, we set up the Review collection to prepare for the addition of Reviews in Milestone 3.
#### Milestone 3
For Milestone 3, we intend to improve upon the functionality we provided in Milestone 2. We will add functionality to the Reviews collection, so that users will be able to add reviews to their menu items. We will also add a page (or sort the existing search page) to see all a menu items that are available right now. Adding to that, we will improve upon the availability function, as currently it shows that an item is available regardless of day, as long as it is within the hours it is available. We will also make significant updates to the UI, changing the color scheme (testers noted that the background was at times, overwhelming) and improving the interface of specific pages, like the Food Listings and Sign in/Register pages. More issues are expected to come up as we go through with user testing next week.


### Contact Us
The developers of this website are: Michael Johnson, Brandon Won, and Kelli Tamashiro. If you have any questions about our system, please feel free to contact us at kellikt@hawaii.edu.
