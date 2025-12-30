# Student Solution – Task 02

## 1. System Overview
The system represents a banking application designed using SOLID principles
and object-oriented design patterns.
It manages customers, accounts, and financial transactions in a flexible way.

## 2. Applied SOLID Principles
- Single Responsibility Principle (SRP):
  Each class has a single responsibility, such as BankAccount handling account logic
  and Customer handling customer data.

- Open/Closed Principle (OCP):
  The transaction behavior can be extended by adding new strategies
  without modifying existing classes.

- Liskov Substitution Principle (LSP):
  Derived transaction classes can replace the base TransactionStrategy class
  without affecting system correctness.

## 3. Design Patterns Used
- Strategy Pattern:
  Used to encapsulate deposit and withdrawal behaviors.
  Different transaction strategies can be added easily.

- Facade Pattern:
  The BankSystem class provides a simplified interface
  to manage customers, accounts, and transactions.

## 4. Transaction Handling
Transactions are executed through an abstraction (TransactionStrategy),
allowing the system to remain flexible and extensible.

## 5. Testing Approach
The system includes automated test cases to verify correct behavior
and demonstrate compliance with SOLID principles.
