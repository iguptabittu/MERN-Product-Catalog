MERN Crash Course - Product Management App
  
A full-stack web application built with the MERN stack (MongoDB, Express.js, React, Node.js) to demonstrate proficiency in modern web development. This project is a Product Management App that allows users to create, read, update, and delete (CRUD) products, showcasing a responsive front-end, a robust back-end API, and seamless database integration.
🚀 Features

Product CRUD Operations: Add, view, update, and delete products with a user-friendly interface.
Responsive Design: Built with React and Tailwind CSS for a mobile-first, responsive UI.
RESTful API: Secure and scalable API endpoints built with Express.js and Node.js.
MongoDB Integration: Efficient data storage and retrieval using MongoDB with Mongoose ODM.
State Management: Utilizes Redux Toolkit for predictable state management in the front-end.
Form Validation: Client-side and server-side validation for robust data handling.
Error Handling: Comprehensive error handling for a smooth user experience.
Environment Configuration: Secure management of environment variables using .env files.

🛠️ Tech Stack



Layer
Technologies



Frontend
React, Redux Toolkit, Tailwind CSS, Axios


Backend
Node.js, Express.js


Database
MongoDB, Mongoose


Tools
Vite (Frontend Build), Postman (API Testing)


Other
JavaScript (ES6+), Git, dotenv


📸 Screenshots



Home Page
Create Product







(Note: Replace screenshots/home.png and screenshots/create.png with actual screenshot paths after adding them to the repository.)
🏗️ Project Structure
mern-crash-course/
├── backend/
│   ├── config/              # Database configuration
│   ├── models/              # Mongoose schemas (e.g., Product)
│   ├── routes/              # API routes
│   ├── controllers/         # Route handlers
│   ├── middleware/          # Custom middleware (e.g., error handling)
│   ├── server.js            # Entry point for the backend
│   └── .env                # Environment variables
├── frontend/
│   ├── src/
│   │   ├── components/      # Reusable components (e.g., ProductCard, Navbar)
│   │   ├── pages/           # Page components (e.g., HomePage, CreatePage)
│   │   ├── store/           # Redux store and slices (e.g., product.js)
│   │   ├── App.jsx          # Main App component
│   │   └── main.jsx         # Entry point for React
│   ├── public/              # Static assets
│   └── vite.config.js       # Vite configuration
├── .gitignore              # Files/folders to ignore
├── package.json            # Project metadata and scripts
└── README.md               # Project documentation

🔧 Prerequisites
Before running the project, ensure you have the following installed:

Node.js (v16 or higher)
MongoDB (Local or MongoDB Atlas)
Git

⚙️ Installation

Clone the Repository:
git clone https://github.com/iguptabittu/mern-crash-course.git
cd mern-crash-course


Install Backend Dependencies:
cd backend
npm install


Install Frontend Dependencies:
cd ../frontend
npm install


Set Up Environment Variables:

Create a .env file in the backend/ directory.
Add the following variables:MONGO_URI=your_mongodb_connection_string
PORT=5000
NODE_ENV=development




Run the Backend:
cd backend
npm start

The server will run on http://localhost:5000.

Run the Frontend:
cd frontend
npm run dev

The React app will run on http://localhost:5173.

Access the App:Open your browser and navigate to http://localhost:5173.


🌐 API Endpoints



Method
Endpoint
Description



GET
/api/products
Fetch all products


GET
/api/products/:id
Fetch a single product by ID


POST
/api/products
Create a new product


PUT
/api/products/:id
Update a product by ID


DELETE
/api/products/:id
Delete a product by ID


Example Request (POST):
curl -X POST http://localhost:5000/api/products \
-H "Content-Type: application/json" \
-d '{"name":"Sample Product","price":29.99,"description":"A sample product"}'

🧪 Testing the API

Use Postman or a similar tool to test the API endpoints.
Ensure the backend server is running (npm start in the backend/ directory).
Test CRUD operations using the endpoints listed above.

📝 Lessons Learned
While building this project, I gained hands-on experience in:

Designing and implementing a RESTful API with Express.js and MongoDB.
Managing state efficiently in React using Redux Toolkit.
Creating a responsive and intuitive UI with Tailwind CSS.
Handling asynchronous operations with Axios and proper error management.
Structuring a full-stack MERN application for scalability and maintainability.
Writing clean, modular, and reusable code following best practices.

🚀 Future Enhancements

Authentication: Implement JWT-based user authentication for secure access.
Search and Filter: Add search functionality and category-based filtering for products.
Image Uploads: Enable product image uploads using Cloudinary or Multer.
Pagination: Add pagination for the product list to improve performance.
Testing: Integrate Jest and React Testing Library for unit and integration tests.

🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.

Please ensure your code follows the project's coding standards and includes relevant documentation.
📜 License
This project is licensed under the MIT License.
📬 Contact

GitHub: @iguptabittu
Twitter: @iguptabittu


⭐ If you find this project helpful, please give it a star on GitHub! It helps showcase the project to others and motivates further development.
