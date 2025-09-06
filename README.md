# 🏦 Bank Management System

A console-based C++ application that simulates a simple **bank client management system**.  
The program allows adding, listing, updating, deleting, and searching client records stored in a text file.

It uses a menu-driven interface where each option corresponds to a specific operation on the clients' database.

---

## ✨ Features
- 📋 Display all clients in a formatted table  
- ➕ Add new clients with unique account numbers  
- 🗑️ Delete existing clients after confirmation  
- ✏️ Update client information (PinCode, Name, Phone, Balance)  
- 🔍 Search for a client by account number and display details  
- 💾 Persistent storage of client data in a text file (`Clients.txt`)  

---

## 🛠️ Technologies
- **C++**  
- Standard libraries:  
  - `<iostream>` (input/output)  
  - `<fstream>` (file handling)  
  - `<vector>` (dynamic storage)  
  - `<string>` (text processing)  
  - `<iomanip>` (formatted output)  

---

## ⚙️ How It Works
1. The program starts by displaying the **Main Menu** with available options.  
2. User selects one of the following operations:  
   - **1:** Show Client List  
   - **2:** Add New Client  
   - **3:** Delete Client  
   - **4:** Update Client Info  
   - **5:** Find Client  
   - **6:** Exit Program  
3. Each client is stored as a record in `Clients.txt` using the format:  
```
AccountNumber#//#PinCode#//#Name#//#Phone#//#Balance
```
4. The system ensures **unique account numbers** when adding new clients.  
5. Data is automatically saved to file after any update or deletion.  

---

## 📂 Project Structure
```
Bank-Management/
│── main.cpp # Main source code
│── Clients.txt # File that stores client records
│── README.md # Project documentation
```
---

## 🎯 Learning Outcomes
This project demonstrates fundamental concepts of **C++ programming**, such as:  
- Structs for data representation  
- Enums for menu navigation  
- Functions for modular design  
- File I/O operations  
- Input validation and user interaction  

---
