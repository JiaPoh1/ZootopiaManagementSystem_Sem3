# 🐾 Zootopia Management System (Java)
## 📌 Important Instructions

⚠️ DO NOT open or run the program inside the src folder.

⚠️ This may cause unexpected errors due to file path dependencies.

👉 Please follow these steps:

1) Extract the ZIP file
2) Place the folder in your home directory
3) Run the program from the following directory:
```
$HOME/Zootopia_ASH/
```

## 📖 Project Overview

The Zootopia Management System is a Java-based desktop application developed using Swing GUI.
It is designed to simulate a zoo management environment where users can manage species and animals interactively.

## 🎯 Features

### 🐻 Species Management
- Add (Import) new species
- Update species information
- Store species details in species.txt

### 🐾 Animal Management
- Add new animals
- Remove animals (release to wild)
- Assign animals to species
- Store animal data in animal.txt

### 📊 Information Display
- View animal details (name, ID, growth stage, feeding time)
- View species details (habitat, diet, description)
- Interactive tree structure for navigation

### 🍽 Feeding System
- Feed animals and update feeding timestamp
- Automatically stored in file

### 🎟 Ticket Calculator
- Calculate ticket prices based on:
  - Category (Malaysian / Non-Malaysian)
  - Age group (Child / Adult / Senior)

## 🛠 Technologies Used
- Java
- Java Swing (GUI)
- File Handling (Text Files)
- Object-Oriented Programming (OOP)

## 📂 Project Structure
```
Zootopia_ASH/
│
├── src/
│   ├── main/        # GUI components and dialogs
│   └── zoo/         # Core classes (Animal, Species)
│
├── species.txt      # Stores species data
├── animal.txt       # Stores animal data
└── icons/           # UI images
```
## ▶️ How to Run
1) Compile the project:
```
javac src/main/ZootopiaManagementSystem.java
```
2) Run the program:
```
java src.main.ZootopiaManagementSystem
```
## ⚠️ Notes
- Make sure species.txt and animal.txt are in the root directory (not inside src)
- Do not rename folders or files as paths are hardcoded
- Font and icon resources must remain in their original locations
