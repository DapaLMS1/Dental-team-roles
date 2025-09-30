Dental Team Roles and Responsibilities Interactive Module
This project provides a clean, single-page interactive guide defining the roles and responsibilities within a dental practice using a tabbed navigation interface. It is built using pure HTML, CSS (via Tailwind CSS CDN), and JavaScript, making it lightweight and easy to deploy.

The design utilizes a custom color palette with deep purple accents for a professional and engaging user experience.

Features
Interactive Tabs: Use the vertical menu (styled as lozenges) to instantly view the details for each role.

Responsive Design: Optimized for display on both mobile devices and large desktop screens.

Clear Visual Hierarchy: The active role is highlighted using a dark purple background and white text.

Visual Context: Each role description includes an associated image for better understanding (Note: Image paths must be updated for external hosting).

Setup and Deployment
This is a single-file application (index.html) and requires no compilation or build tools.

1. Local Setup
Clone or download this repository.

Open index.html directly in your web browser.

2. Image Asset Note (Crucial for External Hosting)
The index.html currently uses internal file IDs (uploaded:Dentist.jpg-c6d6322a-7b87-48d9-b8b4-4ca1c6eb5114, etc.) which only work in the environment where the files were uploaded.

Before deploying to GitHub Pages or another web host, you must:

Host your image files (e.g., in an /assets/images folder).

Update the roleImageMap object in the <script> section of index.html with the new, publicly accessible image paths (e.g., change "uploaded:..." to "./assets/images/Dentist.jpg").

File Structure
.
├── index.html            # The complete, self-contained interactive module
└── README.md             # This file
