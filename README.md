🏬 The Mall of Lahore — Mall Management System

A desktop-based **Mall Management System** built with **Java Swing** and **MySQL**, designed to digitize and streamline the day-to-day operations of a shopping mall — from shop and owner records to product inventory, orders, employees, suppliers, maintenance, and customer feedback.


📌 Overview

This system provides a centralized dashboard for mall administrators to manage all core operational entities through a clean, form-based desktop interface. It follows a layered architecture (UI → Service → DAO → Database) for maintainability and separation of concerns.

✨ Features

- 🔐 **Secure Login System** — authenticated access to the management dashboard
- 🏢 **Shop Management** — add, update, delete, and view shop records
- 📦 **Product Management** — manage product listings linked to shops
- 👤 **Owner Management** — maintain shop owner details
- 🧾 **Order Management** — track customer orders and totals
- 👷 **Employee Management** — manage staff records and designations
- 🚚 **Supplier Management** — maintain supplier contact information
- 🛠️ **Mall Maintenance Tracking** — log maintenance activities and costs per shop
- 📊 **Reports & Analytics** — view sales summaries per shop
- 💬 **Customer Feedback** — capture and review customer ratings and comments
- 🪵 **Error Logging** — backend logging utility for tracking system errors

---

## 🛠️ Tech Stack

| Layer            | Technology                     |
|-------------------|--------------------------------|
| Language          | Java                           |
| UI Framework      | Java Swing                     |
| Database          | MySQL                          |
| DB Connectivity   | MySQL Connector/J (JDBC)       |
| Architecture      | DAO + Service + UI layered design |
| IDE               | IntelliJ IDEA                  |


📁 Project Structure

DATABASE/
├── src/
│   ├── dao/            # Data Access Objects (ShopDAO, UserDAO, etc.)
│   ├── model/           # Data models (Shop, etc.)
│   ├── service/         # Business logic layer (ShopService, OrderService)
│   ├── ui/               # Swing UI forms (LoginForm, Dashboard, ShopForm, etc.)
│   ├── util/             # Utilities (DBConnection, LoggerUtil)
│   ├── image/            # UI assets (logo, login banner)
│   └── TestConnection.java  # Standalone DB connectivity test
├── DATABASE.iml
└── README.md


⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MOAZZAM-ALI-07/MALL-MANAGEMENT-SYSTEM_MY-SQL.git
   ```
2. **Set up the MySQL database**
   - Create a database and import the provided SQL schema.
   - Update your database credentials in `src/util/DBConnection.java`.
3. **Add the MySQL Connector/J dependency**
   - Ensure `mysql-connector-j-*.jar` is added to your project's classpath/libraries.
4. **Run the application**
   - Open the project in IntelliJ IDEA (or any Java IDE).
   - Run `LoginForm.java` to launch the application.

---

## 📸 Screenshots

<!-- Replace file names below only if your uploaded screenshots differ -->

| | |
|---|---|
| ![Screenshot 1](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.32.22%20PM.jpeg) | ![Screenshot 2](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.32.27%20PM.jpeg) |
| ![Screenshot 3](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.33.18%20PM.jpeg) | ![Screenshot 4](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.33.22%20PM.jpeg) |
| ![Screenshot 5](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.33.45%20PM.jpeg) | ![Screenshot 6](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.34.29%20PM.jpeg) |
| ![Screenshot 7](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.34.33%20PM.jpeg) | ![Screenshot 8](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.38.24%20PM.jpeg) |
| ![Screenshot 9](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.38.28%20PM.jpeg) | ![Screenshot 10](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.38.32%20PM.jpeg) |
| ![Screenshot 11](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.38.35%20PM.jpeg) | ![Screenshot 12](SCREENSHOTS/WhatsApp%20Image%202026-08-19%20at%205.40.03%20PM.jpeg) |

---

## 👨‍💻 Author

**Moazzam Ali**
GitHub: [@MOAZZAM-ALI-07](https://github.com/MOAZZAM-ALI-07)

---

## 📄 License

This project is developed for academic/portfolio purposes. Feel free to fork and build upon it with attribution.
