# 📘 Tutorial: How to Check Sub-Branches in a GitHub Repository (ECU1, ECU2, ECU3)

## 📌 Objective  
This tutorial helps you find and access source code for different ECU nodes (ECU1, ECU2, ECU3) stored in separate branches of a GitHub repository.

---

## 🔹 Step 1: Open the Repository  
- Go to your GitHub repository in a browser  
- Example: https://github.com/Abhikurki/CAN-Based-Automotive-Dashboard-Embedded-Systems-Project.git

---

## 🔹 Step 2: Locate Branch Dropdown  
- On the main page, find the **branch selector dropdown**  
- It usually shows: `main` or `master`  

---

## 🔹 Step 3: View All Branches  
- Click on the dropdown  
- You will see all available branches like:
  - ECU1
  - ECU2
  - ECU3  

---

## 🔹 Step 4: Switch Between Branches  

### 👉 To view ECU1 code:
- Select **ECU1 branch**
- The repository files will update
- Now you are viewing ECU1 source code

### 👉 To view ECU2 code:
- Select **ECU2 branch**
- Files will change accordingly

### 👉 To view ECU3 code:
- Select **ECU3 branch**
- Dashboard node code will be visible

---

## 🔹 Step 5: Clone Specific Branch (Optional)

Use this command in terminal:

```
git clone -b ECU1 https://github.com/your-username/your-repo.git
```

Replace ECU1 with:
- ECU2
- ECU3

---

## 🔹 Step 6: Switch Branch Using Git (Local System)

If repo is already cloned:

```
git branch
git checkout ECU1
```

To switch:
```
git checkout ECU2
git checkout ECU3
```

---

## 📡 Tips  
✔ Keep each ECU code in separate branch for clarity  
✔ Use proper naming: ECU1, ECU2, ECU3  
✔ Add README in each branch explaining functionality  

---

## 🚀 Conclusion  
By using branches, you can organize different ECU codes efficiently and access them easily without mixing files.

