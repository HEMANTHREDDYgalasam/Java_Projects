# 🔢 JavaFX Calculator App

![JavaFX](https://img.shields.io/badge/JavaFX-UI-blue) 
![Status](https://img.shields.io/badge/Project-Complete-brightgreen) 
![License](https://img.shields.io/badge/License-MIT-lightgrey)

> 🎯 A sleek and interactive desktop calculator built using **JavaFX**.  
> ✨ Perform basic arithmetic operations with a responsive, clean, and intuitive UI.

---

## 🚀 Key Features

- ➕ **Addition**, ➖ **Subtraction**, ✖️ **Multiplication**, ➗ **Division**
- 🔁 Clear/reset button to start fresh
- 📐 Clean layout using `GridPane`
- ⚡ Lightweight and fast — ideal for JavaFX beginners
- 🧑‍💻 100% open-source and beginner-friendly

---

## 🖼️ Application UI Preview

![Calculator Screenshot](./Screenshot.jpg)  
*Clean, minimal JavaFX interface*

---

## 🧰 Built With

| 🧩 Technology | 📝 Description                    |
|--------------|----------------------------------|
| Java         | Core logic & backend              |
| JavaFX       | GUI framework for rich interfaces |
| GridPane     | UI layout manager                 |
| Scene/Stage  | Window management in JavaFX       |

---

## 🛠️ Getting Started

### 📋 Prerequisites

- ✅ Java JDK 11 or later
- ✅ JavaFX SDK [(Download JavaFX)](https://openjfx.io)

### ⚙️ Running the App

1. **Clone the repository** or copy the code into `CalculatorApp.java`.
2. **Open the project** in your preferred Java IDE (IntelliJ, VS Code, or Eclipse).
3. **Configure JavaFX**:
   - Add JavaFX SDK to your project/module path.
   - Add the following **VM options** when running:

   ```bash
   --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls
