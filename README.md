📝 Attendance Form – Project Description
📌 Overview
The Attendance Form is a simple yet functional web-based interface that allows users to record and manage student attendance details. It supports full CRUD operations (Create, Read, Update, Delete) using HTML, CSS, and JavaScript (LocalStorage) — no backend required.

🎯 Key Features
📥 Insert Data – Add a new attendance entry using a user-friendly form

📋 View Records – All entries are displayed in a clean, tabular format

📝 Edit – Update any record directly from the table

❌ Delete – Remove individual records from the list

🧠 LocalStorage – All data is stored in the browser, so it's persistent even after refresh

📱 Responsive Design – Works well on mobile and desktop

🧾 Form Fields
The form includes the following inputs:

Field Name	Type	Description
Attendance	Dropdown	Choose between "Present" or "Absent"
Name	Text	Full name of the student
Class	Dropdown	Select class (from 6th to 12th)
Subject	Text	Enter subject name (e.g., Maths, English)
No. of Questions	Number	Number of questions answered by student
Date	Date Picker	Choose attendance date

🖥️ Technology Stack
HTML5 – Structure of the web pages

CSS3 – Custom styling with responsiveness

JavaScript (Vanilla) – Logic for data handling and interaction

LocalStorage – For saving data locally without a backend

📂 Page Structure
Menu and Home pages

attendance_list.html – Displays the attendance table with "Add Attendance" button

add_attendance.html – Form page to insert new records

style.css – All styles for both pages (optional to separate)
