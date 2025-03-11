
---


# Node.js Project - First App with MongoDB and Express

![GitHub](https://img.shields.io/badge/license-MIT-blue)
![GitHub last commit](https://img.shields.io/github/last-commit/yosriharraby/Node-Js-Project)
![GitHub repo size](https://img.shields.io/github/repo-size/yosriharraby/Node-Js-Project)

Welcome to the **Node.js Project**! This is a simple web application built with **Node.js**, **Express**, and **MongoDB**. It serves as a starting point for building scalable and efficient web applications using modern JavaScript technologies.

---

## **Features**

- **Express.js**: A fast and minimalist web framework for Node.js.
- **MongoDB**: A NoSQL database for storing and managing data.
- **Environment Variables**: Secure configuration using `.env`.
- **RESTful API**: Basic CRUD operations implemented.
- **Modular Structure**: Organized codebase for easy maintenance and scalability.

---

## **Prerequisites**

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) (or a MongoDB Atlas account)
- [Git](https://git-scm.com/)

---

## **Installation**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yosriharraby/Node-Js-Project.git
   cd Node-Js-Project
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the root directory.
   - Add your MongoDB connection string:
     ```
     mongodb+srv://yosri:*****@cluster0.sniim.mongodb.net/     PORT=7000
     ```

4. **Start the server**:
   ```bash
   npm start
   ```

5. **Access the application**:
   - Open your browser and navigate to `http://localhost:7000`.

---

## **Project Structure**

```
Node-Js-Project/
├── node_modules/
├── public/
│   └── index.html
├── models/
│   └── user.js
├── .env
├── package.json
├── package-lock.json
├── server.js
└── README.md
```

---

## **Usage**

- **Create a new user**: Send a POST request to `/api/users` with a JSON body containing `name`, `email`, and `age`.
- **Get all users**: Send a GET request to `/api/users`.
- **Update a user**: Send a PUT request to `/api/users/:id` with the updated data.
- **Delete a user**: Send a DELETE request to `/api/users/:id`.

---

## **Contributing**

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**

- Special thanks to the Node.js and Express.js communities for their amazing documentation.
- MongoDB Atlas for providing a free-tier database service.

---

## **Contact**

If you have any questions or suggestions, feel free to reach out:

- **Author**: Yosri Harraby
- **Email**: yosriharrabi92@gmail.com
- **GitHub**: [yosriharraby](https://github.com/yosriharraby)
```

