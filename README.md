# E-Commerce Website  

This is a fully functional **E-Commerce Website** built using **Java Spring Boot** for the backend and **Thymeleaf**, **HTML**, **CSS**, and **Bootstrap** for the frontend. The website includes essential features like product browsing, category management, user authentication, shopping cart functionality, and admin panel for complete control over the system.  

## Features  

### Public/User Panel  
- **Home Page**:  
  - Carousel banner highlighting the latest or featured products.  
  - Display of product categories and latest products.  
- **Product Page**:  
  - A list of all available products with details.  
- **Category Page**:  
  - View all products filtered by categories.  
- **Product Details**:  
  - View detailed information about a product.  
- **Shopping Cart**:  
  - Add products to the cart for purchase.  
  - View and update cart items.  

### Admin Panel  
- **Manage Categories**:  
  - Add, edit, view, and delete product categories.  
- **Manage Products**:  
  - Add, edit, view, and delete products.  
- **Manage Users**:  
  - View and manage registered users.  
- **Manage Admins**:  
  - Add and manage other admin users.  

### User Authentication  
- Login and Register pages for user authentication.  
- Secure access to admin features based on role-based authentication.  

### Additional Features  
- Responsive design for mobile, tablet, and desktop screens.  
- Data persistence using a relational database.  
- CRUD operations for all entities (Products, Categories, Users, Admins).  

## Technology Stack  

### Backend  
- **Java Spring Boot**  
  - RESTful APIs for handling backend logic.  
  - Spring Security for authentication and authorization.  
- **Database**:  
  - MySQL. 

### Frontend  
- **Thymeleaf**  
- **HTML5**, **CSS3**, **JAVASCRIPT**, **Bootstrap**  

### Tools  
- **Maven**: For dependency management.  
- **Spring Data JPA**: For database interaction.  
- **Git/GitHub**: For version control.  

## Installation and Setup  

1. Clone the repository:  
   ```bash  
 git clone https://github.com/your-username/e-commerce-website.git  
   cd e-commerce-website

 2. Configure the database in application.properties:

   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce  
   spring.datasource.username=your_db_username  
    spring.datasource.password=your_db_password  
    spring.jpa.hibernate.ddl-auto=update

   
 3. **Build and run the application:**
     mvn clean install  
     mvn spring-boot:run

  4. Access the application in your browser:
      http://localhost:8080




   


