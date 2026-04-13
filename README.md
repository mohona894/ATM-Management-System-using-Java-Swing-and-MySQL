Project Name: ATM-Management-System-using-Java-Swing-and-MySQL

A desktop-based ATM simulation system developed in Java with an interactive Swing GUI and a MySQL database connected through JDBC.
The system replicates real-world ATM operations including authentication, transactions, PIN management, and transaction history.

Project Overview
The application allows users to perform essential ATM operations in a secure and user-friendly environment. All data is stored and retrieved from a relational database in real time, demonstrating practical use of OOP concepts, GUI design and database connectivity.

 Key Features:

| Feature                  | Description                                   |
| ------------------------ | --------------------------------------------- |
| User Authentication   | Secure login using card number and PIN        |
| Balance Inquiry       | View real-time account balance                |
| Cash Deposit          | Deposit money with automatic balance update   |
| Cash Withdrawal       | Withdraw money with balance validation        |
| PIN Change            | Update ATM PIN securely                       |
| Mini Statement        | View recent transaction history               |
| Database Integration | MySQL backend using JDBC                      |
| GUI Interface        | Clean, interactive interface using Java Swing |

Technologies Used:

| Category             | Technology                         |
| -------------------- | ---------------------------------- |
| Programming Language | Java (JDK 17+)                     |
| GUI Framework        | Java Swing                         |
| Database             | MySQL                              |
| Connectivity         | JDBC                               |
| IDE                  | IntelliJ IDEA / Eclipse / NetBeans |
| Libraries            | jcalendar, DateChooser             |


OOP Principles Applied:

| Principle         | Implementation                                        |
| ----------------- | ----------------------------------------------------- |
| Encapsulation     | Private data members with public access methods       |
| Abstraction       | GUI hides database and logic complexity from users    |
| Inheritance       | Shared behaviors reused across multiple classes       |
| Polymorphism      | Event-driven actions vary across different components |


Project Structure:
ATM-Management-System/
│
├── src/
│   ├── Login.java
│   ├── MainMenu.java
│   ├── Deposit.java
│   ├── Withdraw.java
│   ├── BalanceInquiry.java
│   ├── PinChange.java
│   ├── MiniStatement.java
│   └── DBConnection.java
│
├── database/
│   └── atm_database.sql
│
├── lib/
│   └── external libraries (jcalendar, etc.)
│
└── README.md


Database Design:
Main tables used in the system:
* `users` – stores card number, PIN, and user details
* `transactions` – records deposits, withdrawals, and timestamps

How to Run the Project:
1. Install Java JDK 17+
2. Install and start MySQL Server
3. Import the `atm_database.sql` file into MySQL
4. Update database credentials in `DBConnection.java`
5. Run `Login.java` to start the application

Learning Outcomes:
* Practical implementation of OOP concepts
* Building real-world GUI applications using Swing
* Database design and JDBC connectivity
* Event-driven programming
* Secure transaction handling logic



