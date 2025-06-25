# BookMyShow

BookMyShow is a Spring Boot application that allows users to book movie tickets online. This project serves as a platform for users to browse available movies, view showtimes, and make bookings seamlessly.

## Features

- User registration and authentication
- Browse movies and showtimes
- Book tickets for selected movies
- View booking history
- Admin panel for managing movies and bookings

## Technologies Used

- Spring Boot
- Spring Data JPA
- H2 Database (for development)
- Maven
- Thymeleaf (for rendering views)

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/BookMyShow.git
   ```

2. Navigate to the project directory:
   ```
   cd BookMyShow
   ```

3. Build the project using Maven:
   ```
   mvn clean install
   ```

4. Run the application:
   ```
   mvn spring-boot:run
   ```

### Accessing the Application

Once the application is running, you can access it at:
```
http://localhost:8080
```

## Directory Structure

```
BookMyShow
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── bookmyshow
│   │   │           ├── BookMyShowApplication.java
│   │   │           ├── controller
│   │   │           ├── model
│   │   │           ├── repository
│   │   │           └── service
│   │   └── resources
│   │       ├── application.properties
│   │       └── static
│   └── test
│       └── java
│           └── com
│               └── bookmyshow
│                   └── BookMyShowApplicationTests.java
├── pom.xml
└── README.md
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.