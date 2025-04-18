# YelpCamp

YelpCamp is a full-stack campground review web application. It allows users to browse, create, and review campgrounds, with full authentication and interactive maps.


**Live Demo:** [https://yelpcamp-9cid.onrender.com](https://yelpcamp-9cid.onrender.com)
⚠️ _Note: The app might take a few seconds to load as the server may spin up from sleep._


## Features

- Create, edit, and delete campgrounds with descriptions and images.
- Leave reviews and ratings for campgrounds.
- User authentication and authorization for secure access.
- Interactive map displaying all campgrounds with clustering.
- Image uploads using Cloudinary.
- Fully responsive design for better accessibility.


## Tech Stack

**Client:** HTML, CSS, JavaScript, EJS  
**Server:** Node.js, Express.js, MongoDB  
**Other:** Passport.js (Authentication), Cloudinary (Image Upload), MapTiler (Map Integration), Render (Deployment)


## Run Locally

Clone the project and install dependencies:

```bash
git clone https://github.com/JayitaL/YelpCamp.git
cd YelpCamp
npm install
```


## Add environment variables

Create a .env file in the root directory and add your environment variables

```bash
DB_URL = your_mongodb_uri
CLOUDINARY_CLOUD_NAME = your_cloud_name
CLOUDINARY_KEY = your_api_key
CLOUDINARY_SECRET = your_api_secret
MAPTILER_KEY = your_maptiler_api_key
SECRET = your_session_secret
```


## Start the app

```bash
node app.js
```
