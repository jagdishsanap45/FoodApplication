## 🧰 Tech Stack

> The project is built using modern Java backend technologies and follows a modular microservices architecture for scalability and maintainability.

### ⚙️ Core Technologies

- ☕ **Java 17+**: The primary programming language.
- 🚀 **Spring Boot**: For building RESTful APIs and microservices.
- 🗃 **Spring Data JPA**: ORM layer for database operations.
- 🔐 **Spring Security**: Authentication and role-based access control.
- 📩 **Apache Kafka**: Event-driven architecture for handling asynchronous order and notification events.
- ✨ **Lombok**: Reduces boilerplate code with annotations like `@Getter`, `@Setter`, etc.
- 🔄 **Jackson**: JSON serialization and deserialization.
- 🗺 **Google Maps API**: Enables geocoding and other location-based features.
- 🔧 **Hibernate**: JPA provider for object-relational mapping.
- 📦 **JSON Simple**: Lightweight JSON creation and parsing.
- 🔗 **RestTemplate**: Used for inter-service REST API calls and external API integration.

---

## 🧱 Modular Microservices Architecture

The system is split into multiple **domain-driven microservices** to ensure separation of concerns, better scalability, and independent deployment.

### 🧩 Microservices Included:

- 👤 **User Service** – Manages user registration, login, profile, and authentication.
- 🛒 **Merchant Service** – Handles merchant-related data such as shop details and inventory.
- 🚚 **Driver Service** – Manages delivery drivers, status updates, and assignments.
- 🧰 **Utility Service** – Contains shared components/utilities used across all services.

> Each service is independently developed and deployed, communicates via REST and Kafka, and is secured with JWT authentication.
