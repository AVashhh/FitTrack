# Health & Fitness Recommendation System

A Flask-based web application that helps users manage their health through personalized **food and exercise recommendations**, **calorie tracking**, **hydration reminders**, and **weekly reports**. The system integrates MySQL stored procedures, functions, and views for robust backend logic and data handling.

---

## What It Does

- 🔐 **User & Admin Authentication**  
  Secure login and session handling for both users and administrators.

- 🧮 **Calorie Calculator**  
  Calculates daily calorie needs using a stored SQL function based on age, gender, height, and weight.

- 🥗 **Food & Exercise Recommendations**  
  Generates personalized suggestions via stored procedures, considering region, allergies, and fitness goals.

- 💧 **Water Intake Reminders**  
  Allows users to set and receive hydration reminders at custom intervals.

- 📅 **Weekly Reports**  
  Automatically compiles weekly summaries of user activity and recommendations.

- 🛠️ **Admin Dashboard**  
  Admins can add, edit, and delete food and workout items, manage allergies and regions, and view user statistics through an SQL view.

---

## Tech Stack

- **Backend**: Python (Flask)  
- **Frontend**: HTML, CSS (Jinja templates)  
- **Database**: MySQL  
- **ORM**: SQLAlchemy  
- **Security**: Werkzeug (password hashing)

---

## Highlights

- Fully integrated with **MySQL stored procedures** and **functions**
- Handles **user personalization** through goal, region, and allergy data
- Generates real-time and weekly **health insights**
- Includes a functional and modular **admin interface**

---
