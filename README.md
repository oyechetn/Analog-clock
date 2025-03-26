### **Analog Clock Using HTML, CSS, and JavaScript 🕰️**  

#### **📌 Overview**  
Ye ek simple **Analog Clock** hai jo **HTML, CSS, aur JavaScript** ka use karke banaya gaya hai. Ye **real-time me update** hota hai har second.  

---

### **🚀 Features**  
✔️ Analog Clock Design 🎨  
✔️ **Real-time update** (JS se time calculate hota hai) ⏳  
✔️ **Clock Numbers (1-12) dynamically add hote hain** 🕐  
✔️ Smooth Animations 🌀  

---

### **📂 Code Explanation**  

#### **📌 1. HTML Structure (`<body>`)**  
- **Title**: "This is an Analog Clock"  
- **Clock Container (`.clock`)**  
  - **Hour, Minute, Second Hands** (`.hand`)  
  - **Clock Center Dot** (`.center`)  
  - **Numbers (1-12) dynamically generate hote hain**  

#### **📌 2. CSS Styling (`<style>`)**  
- **Clock Shape**: `border-radius: 50%` se gol banaya  
- **Hands Rotation**: `transform: rotate(degree)` se move hota hai  
- **Center Dot**: Ek chhota white circle hai  
- **Number Positions**: **Trigonometry (`sin`, `cos`)** use karke set kiya  

#### **📌 3. JavaScript Logic (`<script>`)**  
- **`updateClock()`**:  
  - `new Date()` se **hours, minutes, seconds** le raha hai  
  - Angles calculate karke hands **rotate** karta hai  
  - Har second **`setInterval(updateClock, 1000);`** se update hota hai  

- **`addNumbers()`**:  
  - Loop chalakar **1-12** numbers ki position calculate karta hai  
  - **Numbers dynamically add karta hai**  

---

### **📸 Output Preview**  
✔️ **Clock with rotating hands**  
✔️ **Numbers (1-12) correctly positioned**  
✔️ **Smooth animation with real-time update**  

---

### **🛠️ How to Run?**  
1. **Is HTML file ko save karein** (e.g. `clock.html`)  
2. **Double click karein** ya **browser me open karein**  
