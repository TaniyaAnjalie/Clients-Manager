# 👥 Clients Manager - Spring Boot Web Application

A simple **Spring Boot CRUD application** for managing client information. Built with **Thymeleaf**, **Spring MVC**, **Spring Data JPA**, and **MySQL**. This project showcases form validation, DTO usage, and a user-friendly Bootstrap-based UI.

---

## 🚀 Features

- 🧾 Add new clients with validation
- 📝 Edit client details
- ❌ Delete clients
- 🔍 View all clients in descending order
- 📧 Email uniqueness check
- 🧱 MVC architecture with layered structure

---

## 🧰 Technologies Used

- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **Thymeleaf**
- **Bootstrap 5**
- **MySQL**
- **Maven**

---

## 🗂 Project Structure

```

src/
├── main/
│   ├── java/com/bmt/webapp/
│   │   ├── controllers/
│   │   │   ├── HomeController.java
│   │   │   └── ClientsController.java
│   │   ├── models/
│   │   │   ├── Client.java
│   │   │   └── ClientDto.java
│   │   ├── repositories/
│   │   │   └── ClientRepository.java
│   │   └── WebappApplication.java
│   └── resources/
│       ├── templates/clients/
│       │   ├── index.html
│       │   ├── create.html
│       │   └── edit.html
│       └── application.properties

````

---

## 🛠 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/clients-manager.git
   cd clients-manager````

2. **Configure Database**

   * Create a MySQL database called `clientsdb`
   * Set port: `3308` (or change in `application.properties`)
   * No password for root user (or update credentials in the config)

3. **application.properties**

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3308/clientsdb
   spring.datasource.username=root
   spring.datasource.password=
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true```

4. **Run the app**
   You can use your IDE or:

   ```bash
   mvn spring-boot:run ```

5. **Visit**

   ```
   http://localhost:8080/
   ```

---

```

> ✅ Let me know if you want help uploading this to GitHub or generating screenshots to include!
```

