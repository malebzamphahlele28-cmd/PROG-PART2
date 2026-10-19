
# PROG-PART2 - ChatApp

This is my Java Chat Application for PROG POE Part 2.

## What the project does
1. Login System - Checks username, password and cellphone number.
   - Username must have underscore (_) and be max 5 characters.
   - Password must be 8 chars with capital letter, number and special character.
   - Cellphone must start with +27 and be 10 digits.

2. Message System- Creates and manages chat messages.
   - Message ID: 10 random numbers.
   - Recipient: Validates +27 number.
   - Message length: Must be <= 250 characters.
   - Message Hash: First 2 of ID + message number + first word + last word (e.g 00:0:HITONIGHT).
   - Send options: 1=Send, 0=Delete, 2=Store to file.

 How to run
1. Open project in NetBeans
2. Clean and Build
3. Run ChatApp.java
4. To test: Right-click MessageTest.java > Test File

Project structure
- Login.java - Login validation
- Message.java - Message logic
- ChatApp.java - Main app and menu
- MessageTest.java - JUnit tests (8 tests)
- pom.xml- Maven config with JUnit 4.13.2

Testing
- JUnit 4 tests: 8 tests
- Result: Tests run: 8, Failures: 0, Errors: 0, Skipped: 0
- BUILD SUCCESS

 Technologies
- Java 17
- NetBeans IDE
- Maven
- JUnit 4

Author
Malebo mphahlele - PROG POE Part 2 - 2026

Repository Link
This repository is for Part 2 submission.
