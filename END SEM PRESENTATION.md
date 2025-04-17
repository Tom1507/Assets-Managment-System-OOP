<!-- slide: title -->
# 🏢 Assets Management System
### Object-Oriented Programming (OOP) Project
#### GitHub: [RafayKhattak/Assets-Managment-System-OOP](https://github.com/RafayKhattak/Assets-Managment-System-OOP)

---

## 📌 About the Project

- A console-based **Assets Management System** for handling organizational assets, employees, and administrators.
- Implemented in **C++** using **OOP principles**:
  - Classes & Inheritance
  - File Handling
  - Polymorphism
  - Encapsulation

---

## 🔧 Local Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/RafayKhattak/Assets-Managment-System-OOP.git
   ```

2. Open the folder in a C++ supported IDE or compiler.

3. Compile the project:
   ```bash
   g++ main.cpp -o AssetSystem
   ```

4. Run the executable:
   ```bash
   ./AssetSystem
   ```

---

## ⚙️ Basic Working

- **Roles**:
  - 🛠 Admin: Manages assets and employees.
  - 👨‍💼 Employee: Can view assigned assets.

- **Core Features**:
  - Add/view/delete assets
  - Add/view/delete employees
  - Assign assets to employees
  - Persist data via text files

---

## 🏗️ Data Structures Used

- **Classes**: `Asset`, `Employee`, `Admin`, `SystemManager`
- **Vectors**: To manage lists of employees and assets in memory
- Load and save logic built into constructors/destructors or specific I/O methods.
---

## 📦 Project Structure & Modeling

```plaintext
📁 Assets-Managment-System-OOP
├── main.cpp
├── Investor.cpp
├── Stocks.cpp
├── Simple_Stocks.cpp
├── Dividend_Stocks.cpp
└── Real_Estate.cpp
```

- **Main Entry Point**: `main.cpp`
- **Data Files**:
  - `asset.txt`: Stores asset information
  - `employee.txt`: Stores employee data
  - `admin.txt`: Stores admin credentials (simulated)

- **Modular Classes**:
  - Separation of concerns between system logic and UI
  - Data encapsulated within class definitions

---


## 🚀 Future Work

- 💾 Shift to database (e.g., SQLite) for secure storage
- 🌐 Add GUI using Qt or web-based frontend
- 🧪 Unit Testing for core logic
- 🔐 Password encryption for admin/employee access
- 📊 Analytics dashboard for asset usage
- <> User can buy stock at different price and we can show a detailed list of his trading activity
---

## 🙌 Thanks for Watching!

🔗 GitHub: [RafayKhattak/Assets-Managment-System-OOP](https://github.com/RafayKhattak/Assets-Managment-System-OOP)
