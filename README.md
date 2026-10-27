# Event Registration System

A web-based Event Registration System that allows users to register for events and helps manage event registration details efficiently.

## 🚀 Features

- User Registration
- Event Listing and Details
- Event Registration Management
- Input Validation
- Organized and User-Friendly Interface

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot
- **Database:** MySQL
- **ORM:** Spring Data JPA / Hibernate
- **API:** REST API
- **Tools:** Maven, Git, GitHub

## 📁 Project Structure

```text
Event-Registration-System/
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│   └── test/
├── pom.xml
└── README.md
```

## ⚙️ Getting Started

### Prerequisites

Make sure you have installed:

- Java JDK
- Maven
- MySQL
- IntelliJ IDEA or Eclipse

### Installation

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Navigate to the project directory:

   ```bash
   cd Event-Registration-System
   ```

3. Configure your database credentials in `application.properties`.

4. Build and run the application:

   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

## 🔧 Configuration

Configure your MySQL database in `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/event_registration
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

## 🧪 Testing

Run the test suite using:

```bash
mvn test
```

## 🔮 Future Improvements

- User Authentication and Authorization
- Admin Dashboard
- Event Capacity Management
- Email Confirmation
- Online Payment Integration

## 👨‍💻 Author

**Aditya Saini**

- GitHub: [adityaasaini](https://github.com/adityaasaini)

## 📄 License

This project is available for educational and learning purposes.
