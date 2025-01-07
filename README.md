# Chat Application

This is a full-stack chat application that enables real-time communication using WebSockets and PostgreSQL for message persistence. The application includes a Spring Boot backend and a Next.js/React frontend.

## Features

- Real-time chat functionality
- Message persistence using PostgreSQL
- Modern UI built with Next.js and React
- Responsive design for desktop and mobile

---

## Backend

The backend is built with Spring Boot and handles real-time communication, message persistence, and API endpoints for the frontend.

### Technologies Used

- **Spring Boot**: Framework for building the backend
- **Spring Data JPA**: For interacting with the PostgreSQL database
- **PostgreSQL**: Database for storing messages
- **WebSockets**: For real-time communication

### Dependencies

The backend includes the following dependencies:

- `spring-boot-starter-data-jpa`: For Spring Data JPA support
- `spring-boot-starter-web`: For building web applications
- `postgresql`: PostgreSQL JDBC driver (runtime scope)
- `spring-boot-starter-test`: For testing support (test scope)

### Getting Started (Backend)

#### Prerequisites

- Java 17 or higher
- Maven
- PostgreSQL database

#### Installation

1. Clone the repository:

    ```sh
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```sh
    cd <backend-project-directory>
    ```

3. Update the `application.properties` file with your PostgreSQL database credentials:

    ```properties
    spring.datasource.url=jdbc:postgresql://localhost:5432/your-database
    spring.datasource.username=your-username
    spring.datasource.password=your-password
    ```

4. Build the project:

    ```sh
    mvn clean install
    ```

5. Run the application:

    ```sh
    mvn spring-boot:run
    ```

---

## Frontend

The frontend is built with Next.js and React, providing a modern and responsive user interface for the chat application.

### Technologies Used

- **Next.js**: Framework for building the frontend
- **React**: Library for building user interfaces
- **Tailwind CSS**: For styling and responsive design
- **WebSockets**: For real-time communication with the backend

### Getting Started (Frontend)

#### Prerequisites

- Node.js 16 or higher
- npm or yarn

#### Installation

1. Navigate to the frontend project directory:

    ```sh
    cd <frontend-project-directory>
    ```

2. Install dependencies:

    ```sh
    npm install
    ```

3. Configure the `.env.local` file to point to the backend server:

    ```env
    NEXT_PUBLIC_BACKEND_URL=http://localhost:8080
    ```

4. Run the development server:

    ```sh
    npm run dev
    ```

5. Open your browser and navigate to `http://localhost:3000` to access the frontend.

---

## Usage

1. Start the backend server as per the backend instructions.
2. Start the frontend development server as per the frontend instructions.
3. Open the frontend in your browser to start using the chat application.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

---


