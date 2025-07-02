


#Wanderlust

Wanderlust is a full-stack rental platform inspired by Airbnb, built using the **MERN stack** (MongoDB, Express.js, React, Node.js) and EJS templating in earlier phases. This platform allows users to browse listings, create their own, and interact with properties in a dynamic and scalable way.

##  Project Status

Currently in active development.  
Phase 1 completed – Core listing functionality, RESTful routes, UI setup, database integration.

##  Features Implemented

- Listing Model with title, description, price, image, location
- MongoDB setup and sample data insertion
- RESTful routes:
  - `GET` all listings (Index)
  - `GET` single listing (Show)
  - `POST` new listing (Create)
  - `PUT` listing (Update)
  - `DELETE` listing (Destroy)
- Basic error handling and validation
- EJS templates with reusable layouts using `ejs-mate`
- Bootstrap-based styling
- Form UI for new/edit listing pages

##  Technologies Used

- Node.js  
- Express.js  
- MongoDB & Mongoose  
- EJS & ejs-mate  
- Bootstrap 5  
- Method-Override  
- Express-Session & Connect-Flash  
- Joi for backend validation

##  Folder Structure

```

wanderlust/
│
├── models/          # Mongoose schemas
├── public/          # Static files (CSS, JS)
├── routes/          # Route handlers
├── views/           # EJS templates
├── utils/           # Utility modules
├── app.js           # Entry point
└── package.json

````

##  Getting Started Locally

### 1. Clone the Repo

```bash
git clone https://github.com/Vishnu-8349/wanderlust.git
cd wanderlust
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Set up MongoDB

Make sure MongoDB is running locally or use MongoDB Atlas. You may need a `.env` file to store DB connection strings and secrets.

### 4. Run the Server

```bash
node app.js
```

##  Future Plans

* Integrate a smart chatbot for enhanced user interaction and support
* Add real-time messaging between users and property owners
* Implement map-based location filtering for listings
* Enhance accessibility and SEO optimization
* Deploy the application to a cloud platform with CI/CD

---

## Acknowledgements

* Inspired by Colt Steele's "YelpCamp" and Airbnb
* Built as part of a full-stack developer learning journey

