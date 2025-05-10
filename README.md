# Hospital Management System

A Java-based Hospital Management System built with Swing and developed in NetBeans IDE. 
This application allows for hospital workflow management such as
patient registration, billing, admin and doctor access, and login modules.

---

## ✨ Features

- Admin login and registration
- Doctor login and registration
- Patient login, registration, and record management
- Billing system
- GUI-based interface with Java Swing
- Modular system design

---

## 🛠 Requirements

- Java JDK 8 or higher
- NetBeans IDE (recommended)
- MySQL (if database connectivity is used)
- Apache Ant (optional for build automation)

---

## 🚀 How to Run

### 🔧 Using NetBeans IDE

1. Open NetBeans IDE.
2. Go to `File > Open Project`.
3. Select the extracted folder: `Hospital-Management-System-main`.
4. Right-click the project > `Clean and Build`.
5. Right-click again > `Run`.

> ✅ The entry point is likely `HMS_Package.Frame1`. Adjust if another class acts as the launcher.

---

### 💻 Using Command Line

```bash
# Navigate to the project directory
cd Hospital-Management-System-main

# Compile all Java files
javac -d build/classes src/HMS_Package/*.java

# Run the application (update class if needed)
java -cp build/classes HMS_Package.Frame1
📁 Project Structure
bash
Copy
Edit
Hospital-Management-System-main/
├── build/              # Compiled class files
├── dist/               # JAR files
├── nbproject/          # NetBeans configs
├── src/                # Java source files
├── build.xml           # Ant build script
├── manifest.mf         # JAR manifest
🔒 Notes
The app might be connected to a MySQL database. Check the src/HMS_Package/*.java files for DB connection code (e.g., JDBC URL, username, password).

Ensure MySQL server is running and necessary tables are created.

