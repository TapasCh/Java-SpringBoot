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
 git clone https://github.com/TapasCh/Java-SpringBoot.git  
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


![Screenshot (64)](https://github.com/user-attachments/assets/0dc5dfd8-d8a1-4e92-b805-0cfb4f8a1a4b)
![Screenshot (65)](https://github.com/user-attachments/assets/25f5bc09-76c6-4841-92d6-8665f7c6285a)
![Screenshot 1](https://github.com/user-attachments/assets/f40f7b82-d976-4188-b3d5-23c779df32c5)
![s1](https://github.com/user-attachments/assets/24f4b956-a7c9-4c6c-86aa-9ebabc3c5ab2)
![s2](https://github.com/user-attachments/assets/868e95c9-1151-4638-8f32-1d8d413b0d8e)
![Screenshot (71)](https://github.com/user-attachments/assets/aede4981-6810-4afc-a05a-11c76b8e0875)
![Screenshot (72)](https://github.com/user-attachments/assets/d7a9cce0-d32a-4175-a730-d1bcede82444)
![Screenshot (66)](https://github.com/user-attachments/assets/ca11c0ba-26b8-48fd-b0c5-3bcf2f40ac13)
![Screenshot (67)](https://github.com/user-attachments/assets/58514e0a-354a-4621-a064-cf737d4f97b6)
![Screenshot (68)](https://github.com/user-attachments/assets/fc71ca6a-6911-4eb2-879a-a95df0e1ca92)
![Screenshot (69)](https://github.com/user-attachments/assets/82a84893-fcc3-4485-af33-edad638211c0)
![Screenshot (70)](https://github.com/user-attachments/assets/6c42a189-9490-495c-b2b5-ccaeff4e2a40)
   
![Screenshot (63)](https://github.com/user-attachments/assets/3a845044-6346-4d28-b87d-2245ac0cad28)


