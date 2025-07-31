# Loan Assistant 💰

**Loan Assistant** is a Java Swing-based desktop application that helps users calculate monthly loan payments or determine the number of payments required to repay a loan. It also provides a detailed loan analysis including interest paid, total payments, and final installment.

---

## 📌 Key Features

- 🔢 Compute Monthly Payment based on:
  - Loan Balance
  - Interest Rate
  - Number of Payments
- 🧮 Compute Number of Payments based on:
  - Loan Balance
  - Interest Rate
  - Monthly Payment
- 📊 Loan Analysis Report:
  - Interest Paid
  - Final Payment
  - Total Payments
- 🚫 Input Validation for numeric fields
- 🖥️ User-friendly Graphical Interface (GUI)

---

## 🛠️ Technologies Used

- Java
- Java Swing (GUI components)
- AWT (Event handling & layout management)

---

## 📁 Project Structure

loanassistant/
│
└── LoanAssistant.java # Main GUI application with complete logic


---

## ▶️ How to Run

### Prerequisites:
- JDK 8 or above
  
- Any Java IDE (Eclipse, IntelliJ, NetBeans) or terminal

### Steps:
1. Clone or download the repository.
2. Navigate to the project directory.
3. Compile and run using terminal:
   ```bash
   javac loanassistant/LoanAssistant.java
   java loanassistant.LoanAssistant

Or run LoanAssistant.java directly from your IDE.

🧾 Sample Use Cases
A user wants to calculate the monthly EMI for a car loan of ₹5,00,000 at 7.5% interest for 60 months.

A user has a monthly budget and wants to calculate the total time required to pay off a ₹2,00,000 personal loan at 10% interest.

📋 Validations
Ensures decimal-only input for loan balance, interest rate, and payments.

Prevents empty input submission.

Handles edge cases like zero interest gracefully.

📤 Exit Strategy

The application safely terminates when:

The Exit button is clicked.

The user closes the window.

👩‍💻 Developed By

Java Developer | Data Analyst | Explorer in Tech & Innovation
📧 ankitasahu0006@gmail.com

📃 License

This project is for learning and demonstration purposes only. Free to use and modify for personal or academic use.

