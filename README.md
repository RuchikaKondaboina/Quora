# 📝 Quora Posts

A simple **Quora-like post management web application** built as part of the **Sigma Course by Apna College**.

This project demonstrates the basics of building a web application using **Node.js, Express.js, EJS, and CSS**, with CRUD operations for managing posts.

## ✨ Features

* 📋 View all posts
* ➕ Create a new post
* 🔍 View a post in detail
* ✏️ Edit an existing post
* 🗑️ Delete a post
* 🆔 Generate unique post IDs using UUID
* 🎨 Render dynamic pages using EJS
* 🔄 Support PATCH and DELETE requests using Method Override
* 💻 Basic CSS styling

## 🛠️ Technologies Used

* **Node.js**
* **Express.js**
* **EJS**
* **HTML**
* **CSS**
* **JavaScript**
* **UUID**
* **Method Override**

## 📁 Project Structure

```text
Quora/
│
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   ├── show.ejs
│   └── edit.ejs
│
├── public/
│   └── style.css
│
├── index.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## 🔄 CRUD Operations

| Operation | Method | Route        | Purpose                  |
| --------- | ------ | ------------ | ------------------------ |
| Create    | POST   | `/posts`     | Create a new post        |
| Read      | GET    | `/posts`     | Display all posts        |
| Read      | GET    | `/posts/:id` | Display a post in detail |
| Update    | PATCH  | `/posts/:id` | Edit a post              |
| Delete    | DELETE | `/posts/:id` | Delete a post            |

## ⚙️ How It Works

The application uses **Express.js** to handle server-side routes and **EJS** as the view engine.

Posts are currently stored in an **in-memory JavaScript array**, so the data resets whenever the server restarts.

Each post contains:

* `id`
* `username`
* `content`

A unique ID is generated for each post using the **UUID** package.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/RuchikaKondaboina/Quora.git
cd Quora
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the server

```bash
node index.js
```

### 4. Open the application

Visit:

```text
http://localhost:8080/posts
```

## 📚 Learning Outcomes

Through this project, I practiced:

* Creating an Express.js server
* Defining GET, POST, PATCH, and DELETE routes
* Working with route parameters
* Handling form data using `express.urlencoded()`
* Rendering dynamic pages using EJS
* Using `method-override`
* Generating unique IDs using UUID
* Organizing views and static files
* Implementing basic CRUD functionality

## 🔮 Future Improvements

* Add MongoDB for permanent data storage
* Add user authentication
* Add likes and comments
* Improve UI/UX
* Add input validation and error handling
* Deploy the application online

## 🎓 Course

Built as part of the **Sigma Course by Apna College** while learning full-stack web development.

---

⭐ **If you found this project useful, feel free to explore the repository!**
