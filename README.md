# AOP Programming Example

This repository contains a simple **Spring Boot** project demonstrating the use of **Aspect-Oriented Programming (AOP)** in Java. It focuses on modularizing cross-cutting concerns such as logging, performance tracking, and method execution monitoring using **Spring AOP**.

## 🚀 Technologies Used

- Java 17+
- Spring Boot
- Spring AOP
- Maven

## 📌 Project Structure

```
src/
└── main/
    ├── java/
    │   └── com.example.aop/
    │       ├── aspect/         # AOP logic (e.g., logging, method tracking)
    │       ├── controller/     # REST Controllers
    │       ├── service/        # Business logic
    │       └── Application.java
    └── resources/
        └── application.properties
```

## 🎯 Features

- Custom `@LogExecutionTime` annotation to measure method execution duration.
- Separation of concerns using aspects.
- Console-based logging of method entry, exit, and execution time.

## ✅ How to Run

```bash
# Clone the repository
git clone https://github.com/eminyavuz/aop-programming-example.git

# Navigate into the project directory
cd aop-programming-example

# Run the application
./mvnw spring-boot:run
```

Then go to `http://localhost:8080` and access available endpoints.

## 📚 Example Use Case

The project can be used as a base for:
- Logging user activity
- Monitoring performance bottlenecks
- Adding security/authentication checks before method execution

## 🧑‍💻 Author

Developed by **[Emin Yavuz](https://github.com/eminyavuz)** as part of a Spring Boot learning exercise.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
