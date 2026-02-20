# 🏥 Hospital Management System (Java - OOP)

## 📌 Project Overview

The Hospital Management System is a console-based Java application developed using Object-Oriented Programming (OOP) principles.  
It allows management of patients, doctors, appointments, and billing within a hospital environment.

This project demonstrates core OOP concepts such as:
- Abstraction
- Inheritance
- Polymorphism
- Encapsulation
- Composition

---

## 🎯 Features

- Add new patients
- View available doctors
- Book appointments
- View all appointments
- Generate bills
- Menu-driven console interface

---

## 🛠 Technologies Used

- Java (JDK 8 or above)
- OOP Concepts
- Java Collections Framework (ArrayList)
- Scanner (for user input)

---

## 🏗 OOP Concepts Implemented

1. Abstraction  
   - `Person` is implemented as an abstract class.

2. Inheritance  
   - `Patient` and `Doctor` extend the `Person` class.

3. Polymorphism  
   - `displayInfo()` method is overridden in subclasses.

4. Encapsulation  
   - Class variables are private/protected.
   - Access is controlled using getters.

5. Composition  
   - `Appointment` contains references to `Patient` and `Doctor`.

---

## 📂 Project Structure

Since this is a single-file implementation:

HospitalManagementSystem.java

Classes included:
- Person (Abstract Class)
- Patient
- Doctor
- Appointment
- Billing
- HospitalManagementSystem (Main Class)

---

## ▶️ How to Compile and Run

Step 1: Compile
javac HospitalManagementSystem.java

Step 2: Run
java HospitalManagementSystem

---

## 🖥 Sample Workflow

1. Add a patient.
2. View available doctors.
3. Book an appointment.
4. Generate bill for consultation and medicine.
5. Exit system.

---

## 📊 Future Enhancements

- Add MySQL database integration using JDBC
- Implement login authentication (Admin/Staff)
- Add file storage using serialization
- Add appointment conflict checking
- Convert to GUI (Swing / JavaFX)
- Add reporting features (daily revenue, patient statistics)

---

## 📚 Learning Outcomes

Through this project, the following skills are developed:

- Understanding of Java OOP design principles
- Building menu-driven applications
- Managing dynamic data using ArrayList
- Modeling real-world systems using classes and objects
- Writing clean, modular, and maintainable code

---

## 👨‍💻 Author

Developed as a college-level academic project using Java.

---

## 📜 License

This project is created for educational purposes only.
