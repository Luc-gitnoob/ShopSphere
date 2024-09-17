# ShopSphere - E-commerce Web Application

Welcome to **ShopSphere**, an all-encompassing e-commerce web application built using the MERN stack (MongoDB, Express, React, Node.js). This project offers a dynamic shopping experience with payment gateway integration, responsive design, and efficient data management. You can explore the live version of the site at [ShopSphere](https://shopsphere-ovrw.onrender.com/).

## Features
- **Dynamic Front-End**: Built with React to provide a responsive, intuitive, and seamless user interface for a smooth shopping experience.
- **Robust Back-End**: Utilizes Express and Node.js to manage:
  - User authentication and authorization
  - Session management
  - Secure order processing
- **Payment Gateway Integration**: Fully integrated payment gateway for handling transactions securely and efficiently.
- **Flexible Data Management**: MongoDB provides scalable NoSQL database storage, enabling complex queries and flexible schema designs.

## Project Structure
- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Luc-gitnoob/ShopSphere.git
   cd shopsphere
   ```

2. **Install dependencies for both the server and client**:
   ```bash
   # For the server (back-end)
   cd server
   npm install

   # For the client (front-end)
   cd ../client
   npm install
   ```

3. **Create a `.env` file in the root directory** for environment variables (server side):
   ```
   MONGO_URI=your-mongo-uri
   JWT_SECRET=your-jwt-secret
   PAYMENT_GATEWAY_API_KEY=your-payment-gateway-api-key
   ```

4. **Run the application**:
   - To run the server:
     ```bash
     cd server
     npm start
     ```
   - To run the client:
     ```bash
     cd ../client
     npm start
     ```

5. **Access the application**:
   Open `http://localhost:3000` in your browser to explore the front-end.

## Technologies Used
- **MongoDB**: NoSQL database for flexible data storage.
- **Express.js**: Back-end framework for building APIs.
- **React**: Front-end library for building responsive user interfaces.
- **Node.js**: JavaScript runtime for back-end logic.
- **Payment Gateway**: Integrated for secure online transactions.

## Future Improvements
- Implement product reviews and ratings.
- Enhance security features with advanced encryption methods.

## Live Demo
You can check out the live version of the site at [ShopSphere](https://shopsphere-ovrw.onrender.com/).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
