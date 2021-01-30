## YelpCamp_BootcampProject
[See the project live](https://guarded-spire-08903.herokuapp.com/) 

YelpCamp is a website where users can create and review campgrounds. 
In order to review or create a campground, you must be logged in. 
This project was part of Colt Steele's web dev course on udemy.

___
### YelpCamp project was created using 
* Node.js, uses EJS template engine over Express.js, 
* MongoDB, 
* Passport.js was used to handle authentication,
* Bootstrap and Cloudinary, Mapbox. 
* Deployed on Heroku.

___
### Features
⋅⋅⋅Users can create, edit, and remove campgrounds

⋅⋅⋅Users can review campgrounds, edit or remove their review

___
### To run the app on your localhost, follow the following steps:

- Install mongodb
- Create a cloudinary account to get an API key and secret code
- Create a mapbox account to get API access token

___
git clone https://github.com/alive2020/YelpCamp_BootcampProject.git

cd YelpCamp_BootcampProject

`npm install`
___
Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

 `CLOUDINARY_CLOUD_NAME='<name>'`
 
 `CLOUDINARY_KEY='<key>'`
 
 `CLOUDINARY_KEY_SECRET='<secret>'`
 
 `MAPBOX_TOKEN= '<token>'`
 
 `DB_URL='<url>'`
 
 ___

Run mongod in another terminal and node app.js in the terminal with the project.
Then go to `localhost:3000`.
