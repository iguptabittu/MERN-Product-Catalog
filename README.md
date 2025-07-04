
# 🚀 MERN Crash Course - Product Management App

A full-stack web application built with the MERN stack (MongoDB, Express.js, React, Node.js) to demonstrate proficiency in modern web development. This project is a **Product Management App** that allows users to **Create, Read, Update, and Delete (CRUD)** products—showcasing a responsive front-end, robust back-end API, and seamless database integration.

---
![My Screenshot](https://private-user-images.githubusercontent.com/120164449/459369704-159da4bb-f8a9-4670-b48f-e70fe1b9608a.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTA5MzQ3MDIsIm5iZiI6MTc1MDkzNDQwMiwicGF0aCI6Ii8xMjAxNjQ0NDkvNDU5MzY5NzA0LTE1OWRhNGJiLWY4YTktNDY3MC1iNDhmLWU3MGZlMWI5NjA4YS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNjI2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDYyNlQxMDQwMDJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT03MTM3OTYzNGNmN2ZlNmRlMWY4ZjY4NjE5MmVlYzA3OTBjYWVmMTdmODJmYTkxYmViZTFhMDc2N2E3YzhmYzY5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.IMa6tm2FMbiwhJhGPsqF8y725yb4P3nS1wJ-RuVpzDI)
## ✨ Features

- **Product CRUD Operations**: Add, view, update, and delete products with a user-friendly interface.
- **Responsive Design**: Built with React and Tailwind CSS for a mobile-first, responsive UI.
- **RESTful API**: Secure and scalable API endpoints built with Express.js and Node.js.
- **MongoDB Integration**: Efficient data storage and retrieval using MongoDB with Mongoose ODM.
- **State Management**: Utilizes Redux Toolkit for predictable state management in the front-end.
- **Form Validation**: Client-side and server-side validation for robust data handling.
- **Error Handling**: Comprehensive error handling for a smooth user experience.
- **Environment Configuration**: Secure management of environment variables using `.env` files.

---
![My Screenshot](https://private-user-images.githubusercontent.com/120164449/459369702-d35696e7-98ac-4d94-9ca6-d0ffca39c4c0.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTA5MzQ3MDIsIm5iZiI6MTc1MDkzNDQwMiwicGF0aCI6Ii8xMjAxNjQ0NDkvNDU5MzY5NzAyLWQzNTY5NmU3LTk4YWMtNGQ5NC05Y2E2LWQwZmZjYTM5YzRjMC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwNjI2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDYyNlQxMDQwMDJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xMTAyYTc0ZDZjODBlZDgwYTJmMTI4MDY2NDFiNjc0MjZhODZlMGFkNDZmZGExNjc1ZWIyMmE2OTk5ZjJkMDBmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.abtWbIq4ssAkeGCWeC9j5oVPxf-G1k6aLVcGhtz0Ejc)

## 🛠️ Tech Stack

| Layer       | Technologies                                     |
|------------|--------------------------------------------------|
| Frontend    | React, Redux Toolkit, Tailwind CSS, Axios        |
| Backend     | Node.js, Express.js                              |
| Database    | MongoDB, Mongoose                                |
| Tools       | Vite (Frontend Build), Postman (API Testing)     |
| Other       | JavaScript (ES6+), Git, dotenv                   |

---

## 📸 Screenshots

> Replace these paths with actual screenshots after adding them to the repository.

- **Home Page**  
  ![Home Page](https://github.com/user-attachments/assets/27c9e5c7-08c0-45cb-b284-2de454d913c8)



---

## 🏗️ Project Structure


```markdown
mern-crash-course/
├── backend/
│   ├── config/              # Database configuration
│   ├── models/              # Mongoose schemas (e.g., Product)
│   ├── routes/              # API routes
│   ├── controllers/         # Route handlers
│   ├── middleware/          # Custom middleware (e.g., error handling)
│   ├── server.js            # Entry point for the backend
│   └── .env                 # Environment variables
├── frontend/
│   ├── src/
│   │   ├── components/      # Reusable components (e.g., ProductCard, Navbar)
│   │   ├── pages/           # Page components (e.g., HomePage, CreatePage)
│   │   ├── store/           # Redux store and slices
│   │   ├── App.jsx          # Main App component
│   │   └── main.jsx         # Entry point for React
│   ├── public/              # Static assets
│   └── vite.config.js       # Vite configuration
├── .gitignore               # Files/folders to ignore
├── package.json             # Project metadata and scripts
└── README.md                # Project documentation

```

---

## 🔧 Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) (Local or MongoDB Atlas)
- [Git](https://git-scm.com/)

---

## ⚙️ Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/mern-crash-course.git
   cd mern-crash-course
  ```

2. **Install Backend Dependencies**

   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**

   ```bash
   cd ../frontend
   npm install
   ```

4. **Set Up Environment Variables**
   Create a `.env` file in the `backend/` directory and add:

   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   NODE_ENV=development
   ```

5. **Run the Backend**

   ```bash
   cd backend
   npm start
   ```

   Backend server runs at: [http://localhost:5000](http://localhost:5000)

6. **Run the Frontend**

   ```bash
   cd ../frontend
   npm run dev
   ```

   Frontend runs at: [http://localhost:5173](http://localhost:5173)

7. **Access the App**
   Open your browser and go to: [http://localhost:5173](http://localhost:5173)

---

## 🌐 API Endpoints

| Method | Endpoint            | Description            |
| ------ | ------------------- | ---------------------- |
| GET    | `/api/products`     | Fetch all products     |
| GET    | `/api/products/:id` | Fetch a product by ID  |
| POST   | `/api/products`     | Create a new product   |
| PUT    | `/api/products/:id` | Update a product by ID |
| DELETE | `/api/products/:id` | Delete a product by ID |

### 🔄 Example Request (POST)

```bash
curl -X POST http://localhost:5000/api/products \
-H "Content-Type: application/json" \
-d '{"name":"Sample Product","price":29.99,"description":"A sample product"}'
```

---

## 🧪 Testing the API

* Use [Postman](https://www.postman.com/) or a similar tool to test endpoints.
* Ensure the backend server is running.
* Test CRUD operations using the endpoints listed above.

---

## 📝 Lessons Learned

While building this project, I gained hands-on experience in:

* Designing and implementing a RESTful API with Express.js and MongoDB.
* Managing state efficiently in React using Redux Toolkit.
* Creating a responsive and intuitive UI with Tailwind CSS.
* Handling asynchronous operations with Axios and proper error management.
* Structuring a full-stack MERN application for scalability and maintainability.
* Writing clean, modular, and reusable code following best practices.

---


## 🤝 Contributing

Contributions are welcome!
To contribute:

1. Fork the repository
2. Create a new branch
   `git checkout -b feature/your-feature`
3. Commit your changes
   `git commit -m "Add your feature"`
4. Push to your branch
   `git push origin feature/your-feature`
5. Open a Pull Request

Please ensure your code follows the project's coding standards and includes relevant documentation.

---

## 📬 Contact

* **GitHub**: [iguptabittu] (https://github.com/iguptabittu)
* **Twitter**: [@iguptabittu](https://twitter.com/iguptabittu)

---

⭐ If you find this project helpful, **give it a star** on GitHub to show support and help others discover it!

```

---

Would you like me to save this as a downloadable file or push it to your GitHub directly (if linked)?
```
