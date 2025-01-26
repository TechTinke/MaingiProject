Akan Name Generator

Author: OSCAR MAINGI SOMBA

Description  
The Akan Name Generator is a simple web application that determines a user's Akan name based on their birth date and gender. Akan names originate from Ghanaian culture, where children are named according to the day of the week they were born.

This application calculates the day of birth and assigns the corresponding Akan name for both males and females based on the traditional Ghanaian naming system.

---

Live Demo  
🔗 [Akan Name Generator - Live on GitHub Pages](https://your-github-username.github.io/AkanNameGenerator)

---

Technologies Used

- HTML5 - Structure & Form Handling
- CSS3 - Styling & Layout
- JavaScript (Vanilla JS) - Logic & Interactivity
- Git & GitHub - Version Control & Deployment

---

Setup Instructions

Prerequisites
Before running the project, ensure you have:

- A modern web browser (Chrome, Firefox, Edge, Safari)
- A text editor (VS Code, Sublime, Atom, Notepad++)

How to Run Locally

1. Clone the repository  
   git clone https://github.com/your-github-username/AkanNameGenerator.git
2. Navigate into the project folder
   cd OscarMaingiProject
   Open index.html in your browser
   Option 1: Double-click on index.html
   Option 2: Open with Live Server (if using VS Code)

---

Project Features
Users can enter their birthdate using an input field.
Users can select their gender (Male or Female).
The app validates user input to ensure correct date entry.
Once the user submits, it calculates the day of birth.
Displays the corresponding Akan name based on gender.
Fully responsive design for both desktop & mobile users.

How It Works
Naming System Based on Birth Days
The app determines the day of the week the user was born using this formula:

Day of the week (d) = ( ( (CC/4) - 2*CC-1) + ((5*YY/4) ) + ((26\*(MM+1)/10)) + DD ) mod 7
Where:

CC → Century of birth (e.g., 19 for 1989)
YY → Last two digits of the year (e.g., 89 for 1989)
MM → Month of birth
DD → Day of birth
mod 7 → Finds the remainder when divided by 7

---

License
This project is open-source under the MIT License.

Copyright © 2025
Created by [Oscar Maingi] - All rights reserved.

Contact
Have suggestions or questions? Reach out!
Email: maingioscar2@gmail.com
Instagram: @\_maingiii

Happy Coding!
