# Little Lemon Website

The **Little Lemon Website** was developed as part of the **Meta Back-End Developer Professional Certificate**, focusing on the *Back-End first* approach. This project combines the foundational principles of Django, Django Rest Framework (DRF), and secure token-based authentication to create a comprehensive restaurant management platform.

---

## Key Features

### 1. **Back-End API Development**
The project prioritizes robust server-side functionality, ensuring scalability and efficient resource utilization. Key components include:
- **Server-Side Logic**: Efficiently processes client requests and generates dynamic responses.
- **Database Interaction**: Integrated with **MySQL** for superior performance and scalability over Django's default SQLite.
- **RESTful API**: Built with DRF, adhering to simplicity, statelessness, and scalability.

#### **API Functionality**
- **Menu Management**:
  - List, create, update, or delete menu items.
  - Supports GET, POST, PUT, PATCH, and DELETE methods.
- **Reservation System**:
  - List all bookings or create new reservations via GET and POST.
- **User Management**:
  - User registration and retrieval with role-based access control.
  - Unauthorized users are restricted from accessing sensitive endpoints.

---

### 2. **Token-Based Authentication**
- Utilized **JWT (JSON Web Tokens)** for secure user authentication and session management.
- Ensures that only authenticated users can access protected resources.

---

### 3. **Front-End Integration with Django Templates**
Implemented a clean and maintainable front-end using:
- **Django Template Language (DTL)**: Simplified dynamic content rendering.
- **Modular Design**: Created reusable components such as:
  - **Base Template**: Includes navigation, header, and footer.
  - **Individual Page Templates**: Extends the base layout for pages like Menu, Booking, and About.

---

## Technical Highlights
- **Frameworks**: Django, Django Rest Framework (DRF).
- **Database**: MySQL for robust data handling.
- **Security**: Implemented token-based authentication and ensured API endpoints are secure.
- **Tools and Libraries**:
  - **Djoser**: Simplified user authentication workflows.
  - **Bleach**: Enhanced security by sanitizing user inputs.
  - **JWT**: Used for token authentication and session validation.

---

## Outcomes
This project demonstrates expertise in:
1. Building secure, scalable APIs.
2. Implementing robust authentication mechanisms.
3. Integrating a dynamic front-end with a robust back-end.
4. Utilizing industry-standard tools like DRF, JWT, and MySQL.

The **Little Lemon Website** serves as a practical application of advanced back-end development skills, combining API design, security, and dynamic web development.
