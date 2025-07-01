# Temmu App 🛒

This project is an academic simulation of a buying and selling application (Temu style), developed in Java using Swing for the graphical interface. Currently, it only allows the registration of buyers and sellers and login.

---

## 🛠️ Technologies used

- **Java SE 17** (you can use Java 8+)
- **Swing** (for GUI)
- **Eclipse IDE** 
- **Sistema de archivos local (.txt)** as an alternative to a database

---

## 📁 Project Structure

```plaintext
TemmuApp/
├── src/
│   ├── View/                # Forms: Loginvw, RgCustomervw, RgSellervw, etc.
│   ├── Controller/          # Navigation logic and validations
│   └── Model/               # Data classes and utilities
├── data/                    # .txt files with persistent data (users, etc.)
└── README.md
```
---

## 🚀 How to compile and run

### ✅ Requirements

- Java JDK installed (preferably 11 or higher)
- Eclipse IDE or any Java editor
- Optional: Git (to clone the repository)

### 📥 Step 1: Clone the Repository

```bash
git clone https://github.com/Jefferson3108/Proyect-POO/tree/main/Workshop-4/TemmuApp
cd TemmuApp
```
### 🧱 Step 2: Import into Eclipse
1. Open Eclipse  
2. Go to `File > Import > Existing Projects into Workspace`
3. Select the folder you just cloned or extracted  
4. Finish the import


### 🧪 Step 3: Run the Program
Open the Loginvw.java class located in the View package

Right-click on the file > `Run As > Java Application`  

💡 Note: If you're using `.txt` files as a database, make sure the file paths are correct and point to the data/ directory.

### **Authors**:  
- 👥 Nelson Navarro de la Rosa - 20242020116
- 👥 Jefferson Rico Ruiz - 20242020108



