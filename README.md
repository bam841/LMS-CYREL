# Cyrel Learning Center - LMS Portal

A custom web-based Learning Management System (LMS) frontend built for the **Cyrel Learning Center (Dagatan Lipa Branch)**. This portal is designed to provide a seamless, interactive experience for users, starting from a secure role-based login to a fully responsive user dashboard.

## Overview
The Student LMS Portal serves as the digital gateway for the learning center. It features a modern, split-screen authentication page and a highly organized dashboard tailored for managing educational resources, tracking progress, and navigating school tools.

##  Features
* **Role-Based Authentication UI:** A clean, welcoming sign-in page that prompts users to choose their role (e.g., Student, Admin) before accessing the system.
* **Modern Split-Screen Design:** The login page features the school's branding alongside engaging imagery, paired with a sleek, user-friendly form.
* **Interactive Dashboard:** A fully responsive main dashboard featuring:
    * A persistent, easy-to-navigate left sidebar with user profile integration.
    * A top navigation bar equipped with a global search function.
    * A welcoming hero banner highlighting key information or announcements.
* **Responsive Layout:** Built with CSS Flexbox and CSS variables to ensure the portal looks great across different screen sizes.

## Tech Stack
* **HTML5:** Semantic structuring of the web pages (`log.html`, `dashboard.html`).
* **CSS3:** Custom styling, variables, masking for seamless image integration, and responsive media queries.
* **

##  Project Structure
```text
STUDENT_LMS_PORTAL/
├── log.html             # Role-based Sign-In page
├── dashboard.html       # Main user dashboard interface
├── logpage.css          # Stylesheet specific to the login page
├── dashboard.css        # Stylesheet specific to the dashboard
├── images/              
│   ├── cyrel.png        # Official school logo
│   └── loginpic1.png    # Hero image for the login page
└── README.md            # Project documentation
