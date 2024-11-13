# User Management API 🚀

Simple and powerful REST API for user management built with modern technologies.

## 🛠️ Technologies

- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
- ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
- ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
- ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

## 🚀 Getting Started

1. Install dependencies:

npm install


2. Install development dependencies:

npm install nodemon --save-dev


3. Start the API with auto-reload:

npx nodemon server.js


4. Open Prisma Studio (Database GUI):

npx prisma studio


## 💻 Features

- Create users
- List all users
- Update user information
- Delete users

## 🔍 Prisma Studio

Prisma Studio is a visual database editor that gives you a clear view of your data. Running `npx prisma studio` opens up an intuitive interface where you can:

- Browse your database tables
- Create, update and delete records
- Filter and sort your data
- Manage relationships between tables

## 📡 API Endpoints

| Method | Endpoint       | Description         |
|--------|----------------|---------------------|
| POST   | /usuarios      | Create a new user   |
| GET    | /usuarios      | List all users      |
| PUT    | /usuarios/:id  | Update user by ID   |
| DELETE | /usuarios/:id  | Delete user by ID   |

## 🧪 Request Body Example


{
  "email": "user@example.com",
  "name": "John Doe",
  "age": 25
}


## 📝 License

This project is under the MIT license.

Made with ❤️ by Lucas Brum