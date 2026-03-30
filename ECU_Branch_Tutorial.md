# 📘 Tutorial: How to Access ECU1, ECU2, ECU3 Code from GitHub Branches

## 🎯 Goal
This guide helps you find and view the source code for ECU1, ECU2, and ECU3 when they are stored in different branches of your GitHub repository.

---

## 🌐 Method 1: Using GitHub Website (Easiest)

### Step 1: Open Your Repository
- Go to your GitHub repo in browser
- Example: https://github.com/your-username/your-repository

---

### Step 2: Find Branch Selector
- At the top-left (above file list), you will see a button like:
  👉 **main** or **master**

---

### Step 3: Click Branch Dropdown
- Click on that button
- You will see list of branches like:
  - ECU1
  - ECU2
  - ECU3

---

### Step 4: Open Each ECU Code

👉 Click **ECU1**
- Now you are viewing ECU1 source code

👉 Click **ECU2**
- Now ECU2 files will be shown

👉 Click **ECU3**
- Dashboard code will be displayed

---

## 💻 Method 2: Using Git Commands (Terminal)

### Step 1: Clone Repository
```
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

---

### Step 2: Check All Branches
```
git branch -a
```

You will see:
- origin/ECU1
- origin/ECU2
- origin/ECU3

---

### Step 3: Switch to ECU Branch

👉 For ECU1:
```
git checkout ECU1
```

👉 For ECU2:
```
git checkout ECU2
```

👉 For ECU3:
```
git checkout ECU3
```

---

### Step 4: View Code
- Open folder in VS Code / any IDE
- You will see that ECU-specific code is loaded

---

## 🧠 Best Practice

✔ Keep each ECU in separate branch  
✔ Use clear naming (ECU1, ECU2, ECU3)  
✔ Add README in each branch explaining its function  

---

## 🚀 Summary

| Branch | Contains |
|------|--------|
| ECU1 | Speed & Gear Code |
| ECU2 | RPM & Indicator Code |
| ECU3 | Dashboard Display Code |

---

## 🔥 Pro Tip
You can also download a specific branch directly from GitHub:
- Click branch → Click **Code** → Download ZIP

---

## ✅ Conclusion
Using branches helps you organize multi-module embedded projects like ECU systems cleanly and professionally.

