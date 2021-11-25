# YelpCamp

## Try the [Demo](https://yelpcamp-marko.herokuapp.com/)

A Node.js web application project from the Udemy course - The Web Developer Bootcamp by Colt Steele. It is a web application designed to add, rate and review different campgrounds, different users(read campers) can put in their comments and concerns, so that it is a well informed and well prepared camping trip for other users.

## Features
Authentication:

User login with username and password
Authorization

One cannot manage posts and view user profile without being authenticated
One cannot edit or delete posts and comments created by other users
Manage campground posts with basic functionalities:

Create, edit and delete posts and comments

Upload campground photos

Display campground location on Google Maps (working on it)

Search existing campgrounds

Manage user account with basic functionalities

Flash messages responding to users' interaction with the app

Responsive web design

Custom Enhancements (under construction)

Update campground photos when editing campgrounds

Update personal information on profile page


 ## Built with
### Front-end
- ejs
- Mapbox
- Bootstrap
### Back-end
- express
- mongoDB
- mongoose
- passport
- passport-local
- express-session
- method-override
- Heroku
- Cloudinary
- helmet
- joi

## Installation

1. Install mongodb
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/himanshup/yelpcamp.git
cd yelpcamp
npm install
```
Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```
Run mongod in another terminal and node app.js in the terminal with the project.

Then go to [localhost:3000](https://localhosts/3000).





