# 🍕 Pizza Order & Loyalty Management System

### A C# Windows Forms Application for Seamless Restaurant Operations

---

## 🌟 Project Overview
This project is a desktop application designed for a local pizza restaurant. It handles the end-to-end ordering process—from menu selection to checkout—integrated with a customer loyalty system. To enhance user experience, I implemented **asynchronous-style feedback** using timers and custom loading screens to simulate real-world transaction processing.

## 🚀 Key Features
- **Dynamic Menu Selection:** Interactive UI for selecting pizza sizes, toppings, and sides with real-time price calculation.
- **Loyalty Program:** A built-in system that tracks customer points and applies discounts to frequent diners.
- **Process Simulation:** Uses **C# Timers** to create realistic "Processing Payment" and "Preparing Order" loading screens.
- **Order Summary Generation:** Produces a clean, formatted receipt for the user upon successful checkout.
- **Input Validation:** Robust error handling to ensure correct data entry for customer details and payment info.

## 🛠 Technical Stack
- **Language:** C#
- **Framework:** .NET Framework / Windows Forms (WinForms)
- **Concepts Used:** Object-Oriented Programming (OOP), Timer-based Events, File I/O for Loyalty Data, and UI Event Handling.

---

## 🏗 System Flow
1. **Login/Registration:** Users enter their loyalty ID or create a new profile.
2. **Order Placement:** Selection of items with a live subtotal display.
3. **Checkout:** The system triggers a **Loading Screen** (Timer-controlled) to simulate bank authorization.
4. **Success:** A final order summary is displayed and loyalty points are updated.

## 📁 Key Components
- `FormMain.cs`: The primary interface for order selection.
- `FormLoading.cs`: A dedicated splash screen/loading bar using `timer_Tick` events.
- `CustomerManager.cs`: Logic for calculating and saving loyalty rewards.
- `Order.cs`: A class structure to manage pizza objects and pricing logic.

---

## ⚙️ How to Run
1. Open the `.sln` file in **Visual Studio**.
2. Ensure the `.NET Desktop Development` workload is installed.
3. Press **F5** or click **Start** to launch the application.

## 👥 Author
**Jonathan Rossouw**
*Software Engineering Student | Belgium Campus iTversity*

---
