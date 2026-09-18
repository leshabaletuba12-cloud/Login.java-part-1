# Login.java-part-1# Chat App POE — Registration & Login System

## Overview
This project is part of the Proof of Evidence (POE) assignment for Business Management and IT Support Services. The task is to design and implement a **registration and login system** for a chat application. The system must validate usernames, passwords, and South African phone numbers, and include automated unit tests using JUnit. The project is version-controlled with GitHub and documented with Harvard references.

---

## Requirements
- **Username validation**: Must contain an underscore and be no more than 5 characters in length.
- **Password validation**: Must contain at least 8 characters, one uppercase letter, one number, and one special character.
- **Cell phone number validation**: Must follow South African format with international code (+27).
- **Registration logic**: Must provide clear error messages if validation fails.
- **Login logic**: Must verify credentials and return personalized messages.
- **JUnit tests**: Must test all validation methods, registration, and login.
- **GitHub commits**: More than 6 descriptive commits required.
- **Documentation**: README file with project overview, instructions, and references.

---

## Implementation

### Login.java
The `Login` class contains:
- Fields: `username`, `password`, `cellNumber`, `firstName`, `lastName`
- Methods:
  - `checkUserName()` — validates username format
  - `checkPasswordComplexity()` — validates password strength
  - `checkCellPhoneNumber()` — validates phone number format
  - `registerUser()` — handles registration logic
  - `loginUser()` — verifies login credentials
  - `returnLoginStatus()` — returns personalized login message

### LoginTest.java
The `LoginTest` class contains JUnit tests for:
- Username validation
- Password complexity
- Cell phone number validation
- Registration success/failure
- Login success/failure
- Login status messages

---

## Example User (from assignment screenshots)
- Username: `kyl_1`  
- Password: `Ch&&sec@ke99!`  
- Phone Number: `+27838968976`  
- Name: Kyle Smith  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/ChatApp_POE.
