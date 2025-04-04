# 🧠 IoT Grocery Expiry Management System (GEMS)

An intelligent IoT-powered inventory and expiry date management system tailored for restaurants, designed as part of MIS 6308 – System Analysis and Project Management (Fall 2024).

## 📌 Overview

GEMS (Grocery Expiry Management System) is designed to solve the challenges restaurants face with managing perishable goods. Using weight and temperature sensors, the system ensures that inventory is monitored in real-time and chefs are alerted when items are close to expiration.

## 👥 Team

- Group 4 – MIS 6308 – Fall 2024  
- Professor: Srinivasan Raghunathan

## 🚀 Key Features

- 📦 **Real-Time Inventory Tracking**  
  - Weight sensors detect product changes on shelves  
  - Temperature sensors adjust expiry based on storage conditions

- ⏰ **Automated Alerts**  
  - Sends alerts for items expiring within 7 days  
  - Alerts sent via system UI and email

- 🍽️ **Menu Adjustment**  
  - Chefs can modify menus based on real-time inventory

- 🔐 **Secure Access**  
  - Facial recognition authentication for authorized users

- 🌱 **Eco-Friendly and Cost Saving**  
  - Reduces food waste and supports sustainability efforts

## 🧩 System Architecture

- **Smart Shelves:** Equipped with sensors for tracking
- **RFID/Barcodes:** Identify and track inventory items
- **Edge Computing System (ECS):** Processes data locally for faster decisions
- **Database:** Maintains product data, expiry, and user permissions

## 💻 Functional Modules

- Edit Menu  
- Check Expiry Dates  
- Retrieve Relevant Zone  
- Adjust Expiry Dates  
- Manage Alerts  
- Manage Access  
- View Inventory

## 📚 Use Case Examples

- **Chef logs in → Views alerts → Edits menu accordingly**
- **ECS detects temp change → Recalculates expiry → Alerts chef**
- **Weight change detected → Product quantity updated automatically**

## 🔐 Non-Functional Goals

- ⚡ Performance: Real-time updates and alerts within 1 sec  
- 📈 Scalability: Supports 5,000+ products and future growth  
- 🔒 Security: Encrypted communication & facial recognition  
- 🤝 Compatibility: Works with standard RFID/barcode systems  

## 🖥️ Interface Screens

- Login / Home Screen  
- View Inventory / Receive Alerts  
- Manage Menu / Alerts  

## 🧠 Technologies Used

- IoT Sensors (Weight & Temperature)  
- RFID / Barcode Scanning  
- Edge Computing  
- Database (ERD, Class Diagrams)  
- UML (Use Case, Sequence, Class Diagrams)  
- Functional Specification Document

## 📅 Timeline & Meetings

The project followed a structured weekly timeline from September to December 2024, with milestone deliverables and collaborative meetings.
