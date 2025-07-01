# Temmu App 🛒

Este proyecto es una simulación académica de una aplicación de compra y venta (estilo Temu), desarrollada en Java usando **Swing** para la interfaz gráfica. Actualmente solo permite registrar compradores y vendedores e iniciar sesión.

---

## 🛠️ Tecnologías utilizadas

- **Java SE 17** (puedes usar Java 8+)
- **Swing** (para GUI)
- **Eclipse IDE** 
- **Sistema de archivos local (.txt)** como alternativa a una base de datos

---

## 📁 Estructura del proyecto

```plaintext
TemmuApp/
├── src/
│   ├── View/                # Formularios: Loginvw, RgCustomervw, RgSellervw, etc.
│   ├── Controller/          # Lógica de navegación y validaciones
│   └── Model/               # Clases de datos y utilidades
├── data/                    # Archivos .txt con datos persistentes (usuarios, etc.)
└── README.md
```
---

## 🚀 Cómo compilar y ejecutar

### ✅ Requisitos previos

- Java JDK instalado (preferiblemente 11 o superior)
- Eclipse IDE o cualquier editor de Java
- Opcional: Git (para clonar el repositorio)

### 📥 Paso 1: Clona el repositorio

```bash
git clone https://github.com/Jefferson3108/Proyect-POO/tree/main/Workshop-4/TemmuApp
cd TemmuApp
```
### 🧱 Paso 2: Importa en Eclipse

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



