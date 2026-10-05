# Java-Mini-Project
Atm Machine Simulator 
# Apex Bank ATM Simulator

A lightweight, console-based **Automated Teller Machine (ATM) Simulator** application written in Java. This project mirrors core banking transactions through a Command Line Interface (CLI), utilizing fundamental programming principles like loops, conditional branching, data validation, and dynamically tracked collection states.

---

## 🚀 Features

*   **Check Balance:** Real-time lookup of available financial funds.
*   **Secure Deposits:** Instantly credit monetary amounts with structural rules preventing negative inputs.
*   **Validated Withdrawals:** Dispenses cash while evaluating boundaries against insufficient account balances.
*   **Mini Statement:** Displays a complete runtime audit log of the user's historical transaction statements.
*   **Robust Input Protection:** Built-in validation loops using `Scanner` checking algorithms to swallow text anomalies or menu selection errors gracefully without dropping or crashing the program runtime.

---

## 🛠️ Technology Stack

*   **Language:** Java (JDK 8 or higher)
*   **Components:** `java.util.Scanner`, `java.util.ArrayList`
*   **Interface Type:** Command Line Interface (CLI) / Console application

---

## 📁 Project Structure

```text
ATM-Simulator/
│
├── src/
│   └── AtmSimulator.java    # Core application logic and entry point
├── README.md                # Project documentation
└── .gitignore               # Ignored build configurations
```

---

## ⚙️ Setup and Installation

### Prerequisites
Make sure you have the [Java Development Kit (JDK)](https://oracle.com) installed on your machine (Version 8 or above).

### 1. Clone the Repository
```bash
git clone https://github.com
cd Java-Mini-Project
```

### 2. Compiling the Project
You can build this via your native terminal or console:
```bash
javac src/AtmSimulator.java
```

### 3. Running the Application
Execute the compiled byte-code wrapper:
```bash
java -cp src AtmSimulator
```
*(Alternatively, you can copy the code into any IDE like IntelliJ IDEA, Eclipse, or VS Code and press the **Run** button directly on the `AtmSimulator.java` file).*

---

## 💡 How It Works (Simulation Defaults)
*   **Default Starting Balance:** Open simulation initializes automatically with a pre-seeded balance of **₹1,000.00**.
*   **Transaction Logs:** History logging uses memory-allocated `ArrayList` tracking wrappers to log sequential activities during the lifecycle of the active application.

---
