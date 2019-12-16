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
![landing](images/Landing-Description.PNG)
![landing](images/Landing-TopChoices.PNG)

The Landing page is the homepage for all users. It has a summary of the purpose of UHM Food Mood and a section that shows what student's "top picks", or most highly rated food options are. This is based on the average of the ratings (score of 1 - 5, 5 being the highest) in the reviews of each food option. Click Login at the top right corner to log into your existing account or to create a new account.

See the Landing page <a href = "http://uhmfoodmood.meteorapp.com/#/">here</a>.

#### Food Options Page:
![options](images/FoodOptions.PNG)
Without logging in, you can still view all the food options available. Each card shown displays the name, image, vendor, availability, style, and price of the food. There is also an option to "favorite" the food by clicking on the heart button, but you must be logged in for this function to work.

You can also use the search bar to search through the food options. Search by the name of the food:
![search!](images/FoodOptions-Name.PNG)
Or by the style of the food:
![search!](images/FoodOptions-Style.PNG)
Or by vendor:
![search!](images/FoodOptions-Vendor.PNG)
Or if it's vegan:
![search](images/FoodOptions-Vegan.PNG)
Or even a mixture of both:
![search](images/FoodOptions-Vendor-Name.PNG)

You can also see which food is available right now by clicking the "Food Available Now" button. When it is active, the button will turn green. If you want to show all food options available, just click the "Food Available Now" button again.

![available](images/FoodOptions-FoodAvailableNow.PNG)

You can also sort the food options by the highest rated food options by clicking the "Sort by Rating" button. Like the "Food Available Now" button, when this button is active, it will turn green. If you want it to revert back to the unsorted order, just click the "Sort By Rating" button again.

![sorted](images/FoodOptions-Rating.PNG)

In addition, you can have both buttons active at once, showing you the food options available right now, sorted by highest rating.

![sortedavailable](images/FoodOptions-FoodAvailableNowRated.PNG)

As a regular user (logged in user), you can favorite items from this page by clicking the heart button on the food option card. Once this button is clicked, the heart button will turn red, indicating that you have favorited this food option. You will also receive an alert confirming that you have added this item to your favorites.

![favorites](images/FoodOptionsUser-AddFavorite.PNG)

See the Food Options Page <a href="http://uhmfoodmood.meteorapp.com/#/allListings">here</a>.

#### Reviews Page

![reviews](images/FoodOptions-Review.PNG)

In addition, each food option has a review page. You can view these reviews by clicking on the "See Reviews" link at the bottom of the food option card. Each review shows the username of the user who created the review, their rating (1 - 5, 5 being the highest) in stars, and their description for the review.

As a regular user (logged in), you can edit or remove your review if you have created a review for this food option.

![yourreview](images/FoodOptionsUser-Review.PNG) 

See the Reviews Page of a food option (Eggplant Parmesan) here: <a href="http://uhmfoodmood.meteorapp.com/#/review/82bE4Z73wqSPRt5Td">here</a>.

#### Vendors Page

![listings](images/Vendors-Listings.PNG)

The Vendors page showcases all of our vendors, it displays their logo, name, and a short description of what they are. Like the Food Options page, you do not need to be logged in to view this page.

You can click the "See their food options" button to view all their food options.

![VendorOptions](images/Vendors-FoodOptions.PNG)

It has the same search and sorting functionality as the Food Options page, so you can search by name, vendor, style, whether it's vegan. You can also use the "Food Available Now" and "Sort by rating" buttons to view food that's available now or to sort the food options by rating.

See the Food Listings page <a href="http://uhmfoodmood.meteorapp.com/#/listings">here</a>.

#### User Favorites Page:
![homepage](images/Favorites.PNG)

As a regular user, you can favorite your favorite foods from the Food Options. These favorited foods will appear in your Favorites page. If you want to delete any of your favorites, you just need to click on the "Remove" button at the bottom left of the card. Like the Food Options page, you have the same search functionality using the search bar at the top left.

Before removing a favorite, a user will be sent an alert to confirm that they want to remove the favorite.

![remove](images/Favorites-RemoveWarning.PNG)

Once confirmed, they will receive an alert that the removal was successful.

![removed](images/Favorites-Remove.PNG)

See the Favorites page (must be logged in) <a href = "http://uhmfoodmood.meteorapp.com/#/list">here</a>

####Your Reviews Page

![yourreviews](images/YourReviews.PNG)

Regular (logged in) users can also manage their reviews by going to the Your Reviews page. It lists the name of the food they reviewed, the vendor the food is from, the rating they gave the food, and the description associated with the review. They also have the ability to edit or delete reviews.

If they delete a review, they will first be asked to confirm the deletion:
![deletereview](images/YourReviews-DeleteReview.PNG)
Once confirmed, they will receive an alert letting them know their review has been deleted:
![deletedreview](images/YourReviews-DeleteReviewConfirm.PNG)

See Your Reviews page <a href="http://uhmfoodmood.meteorapp.com/#/reviews">here</a>.

#### Vendors - Your Listings Page:
![vendor](images/VendorListings.PNG)

As a vendor, you can add new listings and edit or delete your existing listings. Your listings will all be shown in Your Listings page. To add a new listing, you will need to click on the "Add Menu Item" button at the top right of the page. To edit an existing listing, click on the Edit link in the row containing the listing. To delete a listing, click the trash can button in the row containing the listing. You also have the same search functionality for your own listings, using the search bar at the top left corner.

See Your Listings page <a href = "http://uhmfoodmood.meteorapp.com/#/vendor">here</a>

#### Vendor/Admin Add Listing Page:

![add listing](images/AddVendor.PNG)

As an admin/vendor, you can utilize the Add Listing Page to add new food listings. You will need to enter the name of the food, the URL to the image of the food, the name of the vendor, the price, whether the food is vegan, the style of the food, the date when the food will be available from, and the times when students can purchase the food. Click the submit button and it will create a new listing with the provided information. 
![added](images/AddVendorListingSuccess.PNG)

See the Vendor/Admin Add Listing Page <a href = "http://uhmfoodmood.meteorapp.com/#/add/">here</a>

#### Vendor/Admin Edit Listing Page:

![edit](images/EditVendorListing.PNG)
As an admin/vendor, you are also given the ability to use the Edit Listing Page to edit food listings. All the previous information about the food listing is already filled in, all you need to do is edit the parts that you would like to change. Once you have finished making your changes, click submit.
![changed](images/EditVendorListingSuccess.PNG)

If you have received this notification, you have successfully edited the menu item.

See an example of a Vendor/Admin Edit Listing Page (each menu item has a unique URL for their edit page) <a href="http://uhmfoodmood.meteorapp.com/#/edit/4u9kNpbJJNCn4PBKE">here</a>.

#### Admin - Manage Listings Page
![listings](images/AdminListings.PNG)

As an admin, you can edit, remove, and add new food listings. Admins can also view all food listings from all vendors. In addition, you can search through all these listings using the search bar at the top left corner.

See the Manage Listings Page <a href = "http://uhmfoodmood.meteorapp.com/#/admin">here</a>

Note that to get to this page as an admin, you will need to click on Manage > Manage Listings in the menu.

#### Admin - Manage Favorites Page

![favorites](images/AdminFavorites.PNG)

As an Admin, you can also view and delete favorites of all users. The Manage Favorites page displays the owner, food name, and vendor of the favorite. You can also search through all the favorites by using the search bar at the top left corner (owner, food name, or vendor work). In addition, admins can delete a favorite from a user by clicking on the red trash can icon in the Remove column.

See the Manage Favorites Page <a href = "http://uhmfoodmood.meteorapp.com/#/listFavorites">here</a>.

#### Admin - Manage Users Page

![users](images/AdminUsers.PNG)

Additionally, Admins can also view and manage all users in the Manage Users page. Admins can search through users using the search bar at the top left corner (search by name). Admins can also add users as admins or vendors by clicking on the green "Add as Admin" button or the green "Add as Vendor" button. They can also remove users as admins or vendors by clicking on the red "Remove as Admin" button or the red "Remove as Vendor" button. They can also remove users by clicking on the red trash can icon in the Remove column.

See the Manage Users Page <a href = "http://uhmfoodmood.meteorapp.com/#/users">here</a>.

### Community Feedback

We have gotten several students to try out our website. For each of these students, we had them try to carry out several tasks on our website, such as:

- Search for Donuts in the Food Options page.
- Look at the reviews of Lunch Sandwiches
- Register for an account.
- Add food to your favorites.
- Add a food item that is Chinese to your favorites
- Add a food item from Jamba to your favorites
- Add Donuts to your favorites
- Add a review to one of your favorites.
- Look at food that’s available right now.
- Look at food that’s available right now in your favorites.
- Delete a favorite.
- Delete a review.

Vendor Testing

- Sign in as jamba@foo.com
- Add a menu item to your listings
- Edit the menu item in your listings
- Remove the menu item from your listings

Admin testing

- Sign in as admin@foo.com
- Edit a review from another user.
- Delete a review from another user.
- Change yourself to a vendor
- Change yourself to an admin
- Delete your user

From here, we observed how our testers interacted with our website while attempting to carry out these tasks. 

#### Raymond
 ![raymond](images/raymond.jpg)

Raymond is a student at UH Manoa who helped test out our website. When testing our website with Raymond, we found that it was hard to tell when the "Food available now" button was active. As such, occasionally he would search without knowing it was only showing the food currently available. We addressed this issue by making the "Food available now" button green when it is active.

#### Desmond
![desmond](images/desmond.jpg)

Desmond is another student at UH Manoa who helped test out our website. Desmond offered some advice on improving the User Interface, such as increasing padding on certain areas (Login page, create space above the header) as well as hiding buttons that certain users could not use (ex. hiding the Add Review button for users not logged in). From Desmond's suggestions, we made numerous UI updates.

#### Jackie, Monica, Jacob
![jackie](images/jackie.jpg)
![monica](images/monica.jpg)
![jacob](images/jacob.jpg)

We combined the summary of our findings for Jackie, Monica, and Jacob, as we found that the issues they ran into were pretty similar. All three of them did not know what they could search in the searchbar (vegan, name of food, style of food, vendor) to find food options. In addition, they wanted to see some kind of connection between the ratings in the reviews of the food option and the food option listed on the Food Options page. From this feedback, we decided to create instructions for the search bars and had the average of the ratings in the reviews of the food option displayed on the food option.


### Developer Guide

#### Installation
The first thing you will need to is install <a href="https://www.meteor.com/install">Meteor</a>. 

Next, download <a href="https://github.com/uhm-food-mood/uhm-food-mood">UHM Food Mood</a>. 

Then, cd into the app/ directory of your local copy of the repo and install third party libraries with:
```
meteor npm install
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
W20191212-20:26:25.720(-10)? (STDERR) Note: you are using a pure-JavaScript implementation of bcrypt.
W20191212-20:26:26.124(-10)? (STDERR) While this implementation will work correctly, it is known to be
W20191212-20:26:26.125(-10)? (STDERR) approximately three times slower than the native implementation.
W20191212-20:26:26.138(-10)? (STDERR) In order to use the native implementation instead, run
W20191212-20:26:26.143(-10)? (STDERR)
W20191212-20:26:26.156(-10)? (STDERR)   meteor npm install --save bcrypt
W20191212-20:26:26.160(-10)? (STDERR)
W20191212-20:26:26.173(-10)? (STDERR) in the root directory of your application.
I20191212-20:26:26.576(-10)? Creating the default user(s)
I20191212-20:26:26.580(-10)?   Creating user admin@foo.com.
I20191212-20:26:26.881(-10)?   Creating user john@foo.com.
I20191212-20:26:27.167(-10)?   Creating user vendor@foo.com.
I20191212-20:26:27.449(-10)?   Creating user daspot@foo.com.
I20191212-20:26:27.714(-10)?   Creating user doner@foo.com.
I20191212-20:26:27.972(-10)?   Creating user dunkin@foo.com.
I20191212-20:26:28.229(-10)?   Creating user govinda@foo.com.
I20191212-20:26:28.488(-10)?   Creating user holoholo@foo.com.
I20191212-20:26:28.745(-10)?   Creating user hottacos@foo.com.
I20191212-20:26:29.002(-10)?   Creating user justice@foo.com.
I20191212-20:26:29.255(-10)?   Creating user kamitoku@foo.com.
I20191212-20:26:29.485(-10)?   Creating user landl@foo.com.
I20191212-20:26:29.703(-10)?   Creating user lasoon@foo.com.
I20191212-20:26:29.914(-10)?   Creating user lecrepe@foo.com.
I20191212-20:26:30.122(-10)?   Creating user ono@foo.com.
I20191212-20:26:30.327(-10)?   Creating user panda@foo.com.
I20191212-20:26:30.532(-10)?   Creating user rocket@foo.com.
I20191212-20:26:30.738(-10)?   Creating user sistah@foo.com.
I20191212-20:26:30.944(-10)?   Creating user bean@foo.com.
I20191212-20:26:31.144(-10)?   Creating user baale@foo.com.
I20191212-20:26:31.347(-10)?   Creating user jamba@foo.com.
I20191212-20:26:31.564(-10)? Creating default data.
I20191212-20:26:31.568(-10)?   Adding: Eggplant Parmesan (daspot@foo.com)
I20191212-20:26:31.588(-10)?   Adding: Moussakka (daspot@foo.com)
I20191212-20:26:31.610(-10)?   Adding: Thai Green Vegetable Curry (daspot@foo.com)
I20191212-20:26:31.611(-10)?   Adding: Thai Red Vegetable Curry (daspot@foo.com)
I20191212-20:26:31.612(-10)?   Adding: Lamb/Beef/Chicken Wrap (doner@foo.com)
I20191212-20:26:31.613(-10)?   Adding: Lamb/Beef/Chicken Plate (doner@foo.com)
I20191212-20:26:31.614(-10)?   Adding: Lamb/Beef/Chicken Salad (doner@foo.com)
I20191212-20:26:31.615(-10)?   Adding: Garlic Yogurt Sauce (doner@foo.com)
I20191212-20:26:31.616(-10)?   Adding: Coffee (Hot/Cold/Blended) (dunkin@foo.com)
I20191212-20:26:31.618(-10)?   Adding: Donuts (dunkin@foo.com)
I20191212-20:26:31.619(-10)?   Adding: Lunch Sandwiches (dunkin@foo.com)
I20191212-20:26:31.625(-10)?   Adding: Breakfast (dunkin@foo.com)
I20191212-20:26:31.625(-10)?   Adding: Khichdi (govinda@foo.com)
I20191212-20:26:31.637(-10)?   Adding: Strawberry Halava (govinda@foo.com)
I20191212-20:26:31.641(-10)?   Adding: Peanut Butter Halava (govinda@foo.com)
I20191212-20:26:31.641(-10)?   Adding: Pineapple Coconut Halava (govinda@foo.com)
I20191212-20:26:31.654(-10)?   Adding: Tuna Melt Panini (holoholo@foo.com)
I20191212-20:26:31.658(-10)?   Adding: Grilled Cheese Panini (holoholo@foo.com)
I20191212-20:26:31.671(-10)?   Adding: Chicken Chipotle Panini (holoholo@foo.com)
I20191212-20:26:31.675(-10)?   Adding: Turkey Avocado Panini (holoholo@foo.com)
I20191212-20:26:31.687(-10)?   Adding: Corn Tacos (hottacos@foo.com)
I20191212-20:26:31.692(-10)?   Adding: Burritos (hottacos@foo.com)
I20191212-20:26:31.704(-10)?   Adding: Quesadillas (hottacos@foo.com)
I20191212-20:26:31.709(-10)?   Adding: Tamales (hottacos@foo.com)
I20191212-20:26:31.721(-10)?   Adding: Shave Ice (justice@foo.com)
I20191212-20:26:31.726(-10)?   Adding: Sorbet Bowls (justice@foo.com)
I20191212-20:26:31.738(-10)?   Adding: Poke Nachos (justice@foo.com)
I20191212-20:26:31.741(-10)?   Adding: Acai Bowls (justice@foo.com)
I20191212-20:26:31.754(-10)?   Adding: Beefy Miso Ramen (kamitoku@foo.com)
I20191212-20:26:31.758(-10)?   Adding: Beefy Spicy Ramen (kamitoku@foo.com)
I20191212-20:26:31.771(-10)?   Adding: Beefy Wild Ramen (kamitoku@foo.com)
I20191212-20:26:31.774(-10)?   Adding: Pork Gyoza (kamitoku@foo.com)
I20191212-20:26:31.787(-10)?   Adding: Chicken Katsu (landl@foo.com)
I20191212-20:26:31.792(-10)?   Adding: Loco Moco (landl@foo.com)
I20191212-20:26:31.805(-10)?   Adding: BBQ Chicken (landl@foo.com)
I20191212-20:26:31.808(-10)?   Adding: Grilled Garlic Ahi (landl@foo.com)
I20191212-20:26:31.821(-10)?   Adding: Egg Masala (lasoon@foo.com)
I20191212-20:26:31.825(-10)?   Adding: Vegetable Masala (lasoon@foo.com)
I20191212-20:26:31.838(-10)?   Adding: Tofu Sambal (lasoon@foo.com)
I20191212-20:26:31.842(-10)?   Adding: Vegetable Sambal (lasoon@foo.com)
I20191212-20:26:31.855(-10)?   Adding: Cheese Louise (lecrepe@foo.com)
I20191212-20:26:31.859(-10)?   Adding: Crepe Monsieur (lecrepe@foo.com)
I20191212-20:26:31.859(-10)?   Adding: Pesto- Pesto (lecrepe@foo.com)
I20191212-20:26:31.876(-10)?   Adding: Nutella (lecrepe@foo.com)
I20191212-20:26:31.877(-10)?   Adding: Shoyu Ahi Poke Bowl (ono@foo.com)
I20191212-20:26:31.891(-10)?   Adding: Shoyu Tako Poke Bowl (ono@foo.com)
I20191212-20:26:31.895(-10)?   Adding: Miso Ahi Poke Bowl (ono@foo.com)
I20191212-20:26:31.908(-10)?   Adding: Miso Tako Poke Bowl (ono@foo.com)
I20191212-20:26:31.912(-10)?   Adding: Orange Chicken (panda@foo.com)
I20191212-20:26:31.925(-10)?   Adding: Beef Broccoli (panda@foo.com)
I20191212-20:26:31.929(-10)?   Adding: Mushroom Chicken (panda@foo.com)
I20191212-20:26:31.941(-10)?   Adding: Honey Walnut Shrimp (panda@foo.com)
I20191212-20:26:31.945(-10)?   Adding: Black/Green Iced Tea (rocket@foo.com)
I20191212-20:26:31.955(-10)?   Adding: Hot Cocoa (rocket@foo.com)
I20191212-20:26:31.959(-10)?   Adding: Cold Cereal w/Fruit (rocket@foo.com)
I20191212-20:26:31.971(-10)?   Adding: Ice Cream Sundae (rocket@foo.com)
I20191212-20:26:31.975(-10)?   Adding: Fish Jun Plate (sistah@foo.com)
I20191212-20:26:31.987(-10)?   Adding: Kalbi Bibimbap (sistah@foo.com)
I20191212-20:26:31.991(-10)?   Adding: Steak Plate (sistah@foo.com)
I20191212-20:26:32.002(-10)?   Adding: Homemade Kimchi (sistah@foo.com)
I20191212-20:26:32.006(-10)?   Adding: Cappuccino (bean@foo.com)
I20191212-20:26:32.017(-10)?   Adding: Macchiato (bean@foo.com)
I20191212-20:26:32.021(-10)?   Adding: Latte (bean@foo.com)
I20191212-20:26:32.033(-10)?   Adding: Mocha (bean@foo.com)
I20191212-20:26:32.037(-10)?   Adding: Pho (baale@foo.com)
I20191212-20:26:32.049(-10)?   Adding: Pad Thai (baale@foo.com)
I20191212-20:26:32.060(-10)?   Adding: Banh Mi Sandwiches (baale@foo.com)
I20191212-20:26:32.072(-10)?   Adding: Spring Rolls (baale@foo.com)
I20191212-20:26:32.082(-10)?   Adding: Smoothies (jamba@foo.com)
I20191212-20:26:32.093(-10)?   Adding: Oatmeal Bowl (jamba@foo.com)
I20191212-20:26:32.098(-10)?   Adding: Apple Cinnamon Pretzel (jamba@foo.com)
I20191212-20:26:32.115(-10)?   Adding: Banana Toast (jamba@foo.com)
I20191212-20:26:32.127(-10)?  Adding: name: Vendor for vendor@foo.com
I20191212-20:26:32.129(-10)?  Adding: name: Da Spot for daspot@foo.com
I20191212-20:26:32.142(-10)?  Adding: name: Doner Shack for doner@foo.com
I20191212-20:26:32.146(-10)?  Adding: name: Dunkin' Donuts for dunkin@foo.com
I20191212-20:26:32.158(-10)?  Adding: name: Govinda's for govinda@foo.com
I20191212-20:26:32.161(-10)?  Adding: name: Holoholo Grill for holoholo@foo.com
I20191212-20:26:32.174(-10)?  Adding: name: Hot Tacos for hottacos@foo.com
I20191212-20:26:32.178(-10)?  Adding: name: Just Ice for justice@foo.com
I20191212-20:26:32.190(-10)?  Adding: name: Kamitoku Ramen for kamitoku@foo.com
I20191212-20:26:32.194(-10)?  Adding: name: L&L Hawaiian Barbecue for landl@foo.com
I20191212-20:26:32.206(-10)?  Adding: name: Lasoon for lasoon@foo.com
I20191212-20:26:32.210(-10)?  Adding: name: Le Crêpe Café for lecrepe@foo.com
I20191212-20:26:32.222(-10)?  Adding: name: Ono Seafood for ono@foo.com
I20191212-20:26:32.232(-10)?  Adding: name: Panda Express for panda@foo.com
I20191212-20:26:32.233(-10)?  Adding: name: Rocket Coffee for rocket@foo.com
I20191212-20:26:32.243(-10)?  Adding: name: Sistah Truck for sistah@foo.com
I20191212-20:26:32.244(-10)?  Adding: name: The Bean Counter for bean@foo.com
I20191212-20:26:32.256(-10)?  Adding: name: Ba-Le for baale@foo.com
I20191212-20:26:32.259(-10)?  Adding: name: Jamba Juice for jamba@foo.com
I20191212-20:26:32.271(-10)?  Adding: Vendor listing: Da Spot for daspot@foo.com
I20191212-20:26:32.274(-10)?  Adding: Vendor listing: Doner Shack for doner@foo.com
I20191212-20:26:32.287(-10)?  Adding: Vendor listing: Dunkin' Donuts for dunkin@foo.com
I20191212-20:26:32.290(-10)?  Adding: Vendor listing: Govinda's for govinda@foo.com
I20191212-20:26:32.304(-10)?  Adding: Vendor listing: Holoholo Grill for holoholo@foo.com
I20191212-20:26:32.308(-10)?  Adding: Vendor listing: Hot Tacos for hottacos@foo.com
I20191212-20:26:32.321(-10)?  Adding: Vendor listing: Just Ice for justice@foo.com
I20191212-20:26:32.325(-10)?  Adding: Vendor listing: Kamitoku Ramen for kamitoku@foo.com
I20191212-20:26:32.338(-10)?  Adding: Vendor listing: L&L Hawaiian Barbecue for landl@foo.com
I20191212-20:26:32.343(-10)?  Adding: Vendor listing: Lasoon for lasoon@foo.com
I20191212-20:26:32.357(-10)?  Adding: Vendor listing: Le Crêpe Café for lecrepe@foo.com
I20191212-20:26:32.361(-10)?  Adding: Vendor listing: Ono Seafood for ono@foo.com
I20191212-20:26:32.374(-10)?  Adding: Vendor listing: Panda Express for panda@foo.com
I20191212-20:26:32.379(-10)?  Adding: Vendor listing: Rocket Coffee for rocket@foo.com
I20191212-20:26:32.393(-10)?  Adding: Vendor listing: Sistah Truck for sistah@foo.com
I20191212-20:26:32.411(-10)?  Adding: Vendor listing: The Bean Counter for bean@foo.com
I20191212-20:26:32.428(-10)?  Adding: Vendor listing: Ba-Le for baale@foo.com
I20191212-20:26:32.444(-10)?  Adding: Vendor listing: Jamba Juice for jamba@foo.com
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.
```
#### Viewing UHM Food Mood
If the app was installed correctly, you will be able to view it at http://localhost:3000/. You can login using the credentials in <a href="https://github.com/uhm-food-mood/uhm-food-mood/blob/master/app/private/defaultAccounts.json">defaultAccounts.json</a>.
### Development History
#### Milestone 1
In Milestone 1, we created the Landing page and four mockup pages - the User Favorites page, the Vendor Listings page, the Vendor/Admin Add Listing page, and the Admin Listings page. We added a small amount of functionality to the Admin Listings page, as admins are able to remove listings from the Admin Listings page. We also set up the schema for and MongoDB collection of food options (MenuItems Collection), so all of the information on the cards that appear on our app is pulled from our database.
#### Milestone 2
For Milestone 2, we greatly improved the functionality of our website. All users can search through the Food Options page by name, vendor, style of food, or even whether a food is vegan. Regular users are now able to use the "favorite" function so that the foods they favorite will show up in their "Favorites" page. Vendors are able to add new listings and edit/remove existing listings that they own. Admins possess the same abilities of vendors, but are able to use these abilities on all listings, including ones they do not own. We also added an immense amount of default data, 72 menu items - 4 sample food items from 18 vendors. In addition, we set up the Review collection to prepare for the addition of Reviews in Milestone 3.
#### Milestone 3

For Milestone 3, we greatly improved upon the functionality we provided in Milestone 2. We added functionality to Reviews, users can now add and edit reviews for food options. In addition, the average of the ratings (1-5) is displayed on the food option cards. We added the ability to only show available food options and the ability to sort by highest rating to the Food Options and Favorites pages. We also fixed the availability function so that an item only shows as "available" when it is within the correct day and correct hour. In addition, we made numerous changes to the UI, such as changing the background color, adding search instructions, adding indicators when certain buttons are active (Food Available Now and Sort by Rating), and adding padding to certain pages. We also gave Admins more functionality, they can now manage all favorites, all users, and all reviews (along with all food options). We were also able to get feedback from several community members and adjusted our website according to their feedback, as noted in the Community Feedback section. 

### Contact Us
The developers of this website are: <a href="https://michaeljohnson127.github.io/">Michael Johnson</a>, <a href="https://wonbk.github.io/">Brandon Won</a>, and <a href="https://kellikt.github.io/">Kelli Tamashiro</a>. If you have any questions about our system, please feel free to contact us at kellikt@hawaii.edu.
