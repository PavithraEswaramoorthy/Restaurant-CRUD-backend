# Restaurant Ordering System

This project is a full-stack restaurant ordering system that allows users to order items, view the menu, and manage their orders using a React frontend and an Express/MongoDB backend.

## Features
- **Frontend:** Built with React and Material-UI
- **Backend:** Express.js with MongoDB for data storage
- **CRUD Operations:** Users can create, read, update, and delete orders
- **Routing:** React Router for navigation
- **State Management:** useState and useEffect for managing component state

## Frontend Repository
[Frontend Repository](https://github.com/PavithraEswaramoorthy/Restaurant-CRUD-frontend)

## Backend Repository
[Backend Repository](https://github.com/PavithraEswaramoorthy/Restaurant-CRUD-backend)

## Installation & Setup

### Frontend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/PavithraEswaramoorthy/Restaurant-CRUD-frontend.git
   cd Restaurant-CRUD-frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```

### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/PavithraEswaramoorthy/Restaurant-CRUD-backend.git
   cd Restaurant-CRUD-backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the backend server:
   ```sh
   node server.js
   ```

## API Endpoints
### Create Order
- **POST** `/posting`
  - Body: `{ "todo": "Order details" }`

### Get Orders
- **GET** `/getting`

### Update Order
- **PUT** `/updating/:id`
  - Body: `{ "todo": "Updated order details" }`

### Delete Order
- **DELETE** `/deleting/:id`

## Technologies Used
- **Frontend:** React, Material-UI, React Router, Axios
- **Backend:** Node.js, Express.js, MongoDB, Mongoose

## License
This project is licensed under the [GNU GENERAL PUBLIC LICENSE](LICENSE).

