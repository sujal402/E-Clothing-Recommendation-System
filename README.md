
# 🛒 E-Commerce Website

This project is a full-featured E-Commerce website built using **React** for the front-end and **Spring Boot** for the back-end. The application allows users to browse products, manage their shopping cart, place orders, and perform various e-commerce-related actions. Admin functionalities are also included for managing products, categories, and orders.

## 🖥️ Technologies Used

### Front-End
- **React**: A popular JavaScript library for building user interfaces, particularly single-page applications (SPAs).
- **Redux**: For state management, ensuring that the app's state is predictable and consistent.
- **React Router**: Used for handling in-app routing, enabling navigation between different pages.
- **Axios**: To make HTTP requests from the React front-end to the Spring Boot back-end.
- **Bootstrap**: For responsive design and a clean, modern UI.

### Back-End
- **Spring Boot**: A robust Java framework used to create the RESTful API and manage the business logic.
- **Spring Security**: For handling authentication and authorization, ensuring that the app's endpoints are secure.
- **JPA/Hibernate**: For data persistence, managing the database with an ORM (Object Relational Mapping) approach.
- **MySQL/PostgreSQL**: As the database system to store user, product, order, and other relevant data.
- **Maven**: For project management and dependency management.

### Features
- **User Authentication**: Secure sign-up, login, and logout functionality.
- **Product Catalog**: Browse and search for products by category or keyword.
- **Shopping Cart**: Add, remove, and update quantities of products.
- **Order Management**: Place orders, view order history, and manage shipping information.
- **Admin Panel**: Admins can manage products, categories, orders, and users.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## 🚀 Getting Started

### Prerequisites
- **Node.js** and **npm**: Required for running the React front-end.
- **Java JDK**: Required for running the Spring Boot back-end.
- **MySQL/PostgreSQL**: Required for the database.

### Running the Project

#### Front-End (React)
1. Navigate to the `frontend` directory:
   \`\`\`bash
   cd frontend
   \`\`\`
2. Install dependencies:
   \`\`\`bash
   npm install
   \`\`\`
3. Start the development server:
   \`\`\`bash
   npm start
   \`\`\`
4. Open your browser and visit `http://localhost:3000`.

#### Back-End (Spring Boot)
1. Navigate to the `backend` directory:
   \`\`\`bash
   cd backend
   \`\`\`
2. Configure the database connection in the `application.properties` file.
3. Build the project using Maven:
   \`\`\`bash
   mvn clean install
   \`\`\`
4. Run the Spring Boot application:
   \`\`\`bash
   mvn spring-boot:run
   \`\`\`
5. The back-end will be available at `http://localhost:8080`.

### API Documentation
The API documentation is provided via **Swagger** and can be accessed at `http://localhost:8080/swagger-ui.html` after starting the Spring Boot application.

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue to improve the project.


