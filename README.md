# My-yelpcamp-project

*node_modules is not added in repo because of it's huge size(i.e. more than 100 files).

Features:-

Authentication: User login with username and password, Admin sign-up with admin code

Authorization: One cannot manage posts and view user profile without being authenticated , One cannot edit or delete posts and comments created by other users
, Admin can manage all posts and comments
, Manage campground posts with basic functionalities:
, Create, edit and delete posts and comments
, Upload campground photos
, Display campground location on Google Maps
, Search existing campgrounds


Getting Started:-
This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.

Clone or download this repository:
https://github.com/Neha21mishra/My-yelpcamp-project.git

Install dependencies:-

npm install

Run it locally:-

. Install mongodb

. Create a cloudinary account to get an API key and secret code

. Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

DATABASEURL='<url>'
  
API_KEY=''<key>
  
API_SECRET='<secret>'
  
Run mongod in another terminal and node app.js in the terminal with the project.

Then go to localhost:3000.
