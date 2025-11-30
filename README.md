# LDU Factorisation Calculator

A simple and interactive web application that performs **LDU (Lower–Diagonal–Upper)** factorisation of any square matrix. Users can input matrix dimensions, fill the values, and view the calculated **L**, **D**, and **U** matrices along with step-by-step explanations.

---

## 📌 Table of Contents

* Introduction
* Purpose
* Requirements
* Features
* Design & Architecture
* Implementation
* Meeting Records
* Limitations & Future Enhancements
* Conclusion
* Team Members
* Repository Link

---

## 📘 Introduction

This project provides a website that calculates the **LDU factorization** of a matrix, a key concept in linear algebra used for simplifying matrix operations.
The tool accepts any **square matrix**, computes its **L**, **D**, and **U** forms, and displays the entire factorisation process clearly.

---

## 🎯 Purpose

To build an educational and useful web-based tool that:

* Performs LDU factorization of matrices
* Displays step-by-step breakdowns
* Helps students understand matrix decomposition

---

## 🛠️ Requirements

### **Software**

* Google Chrome
* VS Code
* GitHub

### **Technologies Used**

* **HTML** – Structure
* **CSS** – Styling
* **JavaScript** – Logic and factorization
* **GitHub** – Version control

### **Functional Requirements**

* Input field for matrix dimension
* Dynamic matrix input boxes
* Step-by-step factorisation
* Error handling for invalid inputs

---

## 🚀 Features

* **Matrix Input:** Enter any square matrix
* **Automatic LDU Calculation:** Computes L, D, and U matrices
* **Step-by-Step Explanation:** Shows how the factorisation is done
* **Error Handling:** Alerts for incorrect inputs
* **Clean UI:** Easy to navigate and understand

---

## 🧩 Design & Architecture

### **Layout**

* Simple and responsive interface
* User enters matrix dimension
* Input grid generates dynamically
* Results displayed on the same page

### **Architecture**

* **HTML** → Page Structure
* **CSS** → Modern & responsive layout
* **JavaScript** → Core logic for LDU factorisation

---

## ⚙️ Implementation

1. **Matrix Dimension Input**

   * JavaScript creates input fields dynamically based on size.

2. **Matrix Value Collection**

   * User fills in values which are validated and processed.

3. **LDU Factorisation Algorithm**

   * **L Matrix**: Calculated using inverse elementary matrices.
   * **D Matrix**: Extracted from diagonal of U after reduction.
   * **U Matrix**: Formed by eliminating lower-diagonal elements.

---

## 📅 Meeting Records

### **Meeting 1 – (28/10/2024)**

* Discussed project goals
* Assigned responsibilities

### **Meeting 2 – (04/11/2024)**

* Reviewed progress
* Identified issues and improvements

### **Meeting 3 – (08/11/2024)**

* Completed testing
* Final bug fixes
* Prepared documentation

---

## ⚠️ Limitations

* Only supports square matrices
* Floating-point precision issues may occur

---

## 🔮 Future Enhancements

* Support for larger matrices
* Graphical matrix editor
* File upload support
* Better error guidance
* Export results as PDF, TXT, JSON, etc.

---

## 🏁 Conclusion

The LDU Factorisation Calculator is a useful educational tool built with a clean interface and clear computational steps. While currently limited to square matrices, the planned enhancements can greatly expand its capabilities and usability for students and professionals.

---

## 👥 Team Members

* **Ajit Yadav** – D Calculator
* **Jagriti Pandey** – L Calculator
* **Guman Singh** – U Calculator
* **Mani Kumar** – GitHub Management
* **Anand Singh** – Documentation

---

## 🔗 Repository Link

**GitHub:** Jagritipandey625/Assignment_02








