

# Foodify – Smart Food Waste Management & Ordering Platform

## Overview

**Foodify** is a full-stack web application designed to combine real-time food waste tracking with an intelligent food ordering system. The platform provides a sustainable solution for reducing food wastage by allowing users and restaurants to save excess food, track real-time data, and facilitate food orders from multiple restaurant partners.

---

## Objectives

* To minimize food waste by allowing excess food to be saved or redistributed.
* To provide a seamless food ordering experience for users.
* To monitor and analyze food usage and waste through real-time data tracking.
* To promote environmental responsibility in the food industry.

---

## Key Features

* **User Management**: Secure login, registration, and profile handling.
* **Restaurant Integration**: View menus, manage orders, and mark excess food.
* **Food Ordering System**: Browse restaurants and place orders through a user-friendly interface.
* **Excess Food Saving**: Option to save and list excess food items for redistribution.
* **Real-Time Dashboard**: Live tracking of food data including availability, orders, and wastage statistics.
* **Analytics Module**: View detailed charts and insights on food usage and saved items.
* **Modular Architecture**: Separate components for users, restaurants, and waste tracking.

---

## Technology Stack

| Layer          | Technology                      |
| -------------- | ------------------------------- |
| Frontend       | React.js                        |
| Backend        | Spring Boot (Java)              |
| Database       | MySQL / PostgreSQL              |
| APIs           | RESTful APIs                    |
| Real-Time Data | WebSockets / Polling (Optional) |

---

## System Modules

### 1. User Module

* User signup and login
* Profile update and order history
* Access to restaurant menus and donation options

### 2. Restaurant Module

* Restaurant dashboard and authentication
* Menu management and food listing
* Excess food marking and availability tracking

### 3. Waste Management Module

* Real-time monitoring of food waste levels
* Reporting and suggestions for food reuse or redistribution
* Optional NGO or volunteer integration for pickups

---

## Application Workflow

1. Users and restaurants log in to the platform.
2. Users can view and order food from listed restaurants.
3. Restaurants can add menu items and mark excess food.
4. Excess food is tracked and listed for potential saving or redistribution.
5. All data is updated in real time on a shared dashboard.
6. Admins or NGOs can access saved food data for redistribution if implemented.

---

## Future Enhancements

* Integration with NGOs or food banks for real-time pickup of excess food
* AI-based prediction of food waste trends
* Notifications for saved food expiry or pickup reminders
* Mobile app version for wider accessibility

---

## Project Goals

Foodify seeks to bridge the gap between food consumption and wastage by enabling smarter food practices. It not only provides convenience in ordering but also contributes to a more sustainable environment by actively reducing food waste.

---

## How to Run

### Backend (Spring Boot)

1. Configure the database credentials in `application.properties`.
2. Run using:

   ```
   mvn spring-boot:run
   ```

### Frontend (React.js)

1. Navigate to the frontend directory.
2. Install dependencies:

   ```
   npm install
   ```
3. Run the development server:

   ```
   npm start
   ```

---

## Contact

For any queries or collaboration requests, please contact me.(neelakshisravya06@gmail.com)


