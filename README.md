# Wanderlust

## Description

Wanderlust is a Node.js, Express, and MongoDB-based web application that allows users to create, view, edit, and delete travel accommodation listings.  
The app features a responsive UI using EJS templates and Bootstrap, and supports full CRUD operations for listings, including title, description, image, price, location, and country fields.

**Features:**
- Add new accommodation listings
- View all listings in a card-based layout
- Edit and delete existing listings
- Responsive design with Bootstrap
- Data validation and error handling

**Technologies Used:**
- Node.js
- Express.js
- MongoDB & Mongoose
- EJS Templating
- Bootstrap 5

---

## 🚀 How to Run This Project

### 1. **Clone the repository**
```sh
git clone https://github.com/yourusername/wanderlust.git
cd wanderlust
```

### 2. **Install dependencies**
```sh
npm install
```

### 3. **Start MongoDB**
Make sure MongoDB is running locally.  
On Windows, you can run:
```sh
mongod
```
Or use MongoDB Compass or Docker if you prefer.

### 4. **Run the application**
```sh
node app.js
```
Or, if you have nodemon installed:
```sh
npx nodemon app.js
```

### 5. **Open your browser and visit**
[http://localhost:8080](http://localhost:8080)

---

## 📚 Useful Links

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Bootstrap](https://getbootstrap.com/)
- [EJS](https://ejs.co/)
- [Mongoose](https://mongoosejs.com/)

---

## 📁 Project Structure

```
major_project/
│
├── models/
│   └── listing.js
├── public/
│   └── css/
│       └── style.css
├── views/
│   ├── includes/
│   │   └── navbar.ejs
│   ├── layouts/
│   │   └── boilerplate.ejs
│   └── listings/
│       ├── index.ejs
│       ├── new.ejs
│       ├── edit.ejs
│       └── show.ejs
├── app.js
└── package.json
```

---
