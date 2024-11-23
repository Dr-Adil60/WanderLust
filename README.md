## ***Wanderlust - Airbnb-like Platform (MERN Stack)***
Wanderlust is a web application that mimics the core functionality of Airbnb. The platform allows users to sign in, sign out, list their properties, give reviews, and manage those reviews. Users can also view the exact location of listed properties via a map, which displays the location on the platform using Mapbox. Additionally, users can edit or delete their listings and reviews. The platform includes a special GST toggle button for better user experience. The website uses Cloudinary for image storage, Bootstrap for form validation, and Font Awesome for icons. The website is built using the MERN (MongoDB, Express.js, React, Node.js) stack, EJS for templating, and CSS for styling.

## ***Features***
User Authentication: Users can sign in and sign out.
Property Listings: Users can list their properties like on Airbnb.
Reviews and Ratings: Users can give reviews and ratings for properties.
Manage Reviews: Users can edit or delete reviews posted from their specific emails.
Manage Listings: Users can edit or delete their property listings.
Map Functionality: Each property listing is displayed with an exact location on the map, allowing users to view the specific address of the property using Mapbox API.
Image Storage: User-uploaded images are stored using Cloudinary, making it easy to manage and serve media files.
GST Toggle: A special button at the top of the page to toggle GST-related functionality.
Form Validation: Built-in form validation using Bootstrap to ensure proper data entry.
Icons: Font Awesome icons are used across the site for better UI/UX.
Laptop-Optimized: The website is fully optimized for laptops and has responsive settings for different screen sizes (mobile responsiveness is optional but not yet implemented).


## ***Technologies Used***

***Frontend:***
JavaScript
EJS (Embedded JavaScript templating engine)
CSS
Bootstrap (For form validation and responsive layout)
Font Awesome (For icons)
Mapbox API (For map functionality)

***Backend:***
Node.js
Express.js

***Database:***
MongoDB
Cloudinary (For image storage)
Authentication:
JWT (JSON Web Tokens)

***License:***
MIT License
Installation
To run this project locally, follow these steps:

## ***1. Clone the Repository***
bash
Copy code
git clone https://github.com/Adil60/WanderLust.git
cd wanderlust

## ***2. Install Dependencies***
Make sure you have Node.js and npm installed. Then, run the following command to install the required dependencies:


Copy code
npm install


## ***3. Set Up Environment Variables***
Create a .env file in the root directory of the project and add the following variables:

env
Copy code
DB_URI=mongodb://your-database-uri
JWT_SECRET=your-jwt-secret
PORT=3000
MAPBOX_API_KEY=your-mapbox-api-key
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret

## ***4. Run the Application***
To start the development server, use the following command:

bash
Copy code
npm start
The application should now be running at http://localhost:3000.

## ***Usage***
Sign In/Sign Up: Users can sign in to the platform with their email and password. They can also sign up to create a new account.
List a Property: After signing in, users can add their properties to the platform, including the location for map placement.
Review and Rate: Users can leave reviews and ratings for properties.
Edit/Delete Listings and Reviews: Users have the ability to manage their own listings and reviews.
Map Functionality: When listing a property, users can see their property displayed on a map with its exact location using Mapbox API. This feature allows users to view property locations in real time.
Image Upload: Users can upload images of their properties, which are stored on Cloudinary for easy access and management.
GST Toggle: The toggle at the top can be used to enable or disable the GST functionality.
Form Validation: Forms on the website, such as for listing properties or signing up, are validated using Bootstrap to ensure accurate data entry.
Icons: Font Awesome icons are used across the platform for better UI and visual appeal.
Mobile Responsiveness
Currently, the website is optimized for laptop screens. Mobile responsiveness is not yet implemented, but this can be an area for future improvement.

## ***License***
This project is licensed under the MIT License. See the LICENSE file for more details.

## ***Contributing***
Feel free to fork this repository, submit issues, or make pull requests. Contributions are always welcome!

