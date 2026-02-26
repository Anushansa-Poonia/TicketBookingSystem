# 🎟 Ticket Booking Management System

A console-based Ticket Booking Management System built using **C# (.NET)** implementing a clean **Layered Architecture**, Repository Pattern, and core OOP principles.

The system allows users to create events, book tickets, cancel bookings, and view detailed booking information.

---

## 🚀 Core Features

- Create Events (Movie / Concert / Sports)
- Display Event Details
- Book Tickets with seat validation
- Cancel Bookings
- View Booking Details
- Sort Events using Custom Comparator
- Custom Exception Handling & Input Validation

---


### 1️⃣ Presentation Layer (`app/`)
- Console-based UI
- Handles user input/output
- Calls service layer methods

### 2️⃣ Service Layer (`service/`, `service/impl/`)
- Contains business logic
- Validates rules (seat availability, booking logic, etc.)
- Communicates with repository layer

### 3️⃣ Repository Layer
- Handles data operations
- Responsible for storing and retrieving events & bookings

### 4️⃣ Entity Layer (`bean/`)
- Domain models:
  - `Event` (Base Class)
  - `Movie`, `Concert`, `Sports`
  - `Booking`
  - `Customer`
  - `Venue`

---

## 🧠 OOP Concepts Implemented

- **Inheritance** → Movie, Concert, Sports extend Event
- **Polymorphism** → Overridden `DisplayEventDetails()` method
- **Encapsulation** → Controlled properties using getters/setters
- **Abstraction** → Interfaces for Service & Repository layers

---

## ⚙️ Technologies Used

- C#
- .NET
- SQL
- Repository Pattern
- Console Application Design

---

## ▶ How to Run

1. Clone the repository  
2. Open in Visual Studio  
3. Build the solution  
4. Run the project  

---

## 👩‍💻 Author

Anushansa Poonia

---

## 📜 License

MIT License
