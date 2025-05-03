# Free-Fire-Free-diamonds-day.com
# Free Fire Rewards Claim System
Overview
The Free Fire Rewards Claim System is a web application designed to simulate a reward claiming process for Garena Free Fire players. It includes a login page, a sign-up page, and a rewards selection page where users can claim in-game items such as diamonds, bundles, gun skins, characters, and elite passes. The application uses HTML, CSS, and Bootstrap for the frontend, with form submissions directed to external APIs. The system is styled to resemble a professional gaming rewards platform and is intended for demonstration purposes.
Note: This project appears to simulate a rewards system but includes links to external APIs and placeholders that may suggest phishing or scam-like behavior (e.g., directing to a Facebook login page for claiming rewards). For ethical and legal use, ensure all APIs and links are legitimate, and avoid collecting user credentials without proper authorization. This README assumes the project is for educational or demonstration purposes only.


# Features
Login Page:
A Facebook-styled login form for users to enter email/phone and password.
Form submission is directed to an external API (e.g., Web3Forms).


Sign-Up Page:
A form to create a new account with fields for first name, last name, email, password, birthday, and gender.
Styled to mimic a professional social media sign-up interface.


Rewards Claim Page:
Displays a variety of Free Fire rewards (e.g., diamonds, bundles, gun skins, elite passes) in Bootstrap cards.
Each card includes an image, description, and a "Claim Now" button linking to the login page.
Modals for enlarged image previews.
Details account level requirements and claim conditions.


Responsive Design:
Built with Bootstrap for mobile-friendly layouts.
Custom CSS for enhanced styling, including background images and animations.


Navigation and Branding:
Navbar with links to the official Free Fire website and a Garena logo.
Footer with developer credits and copyright information.



# Installation
Prerequisites

A web browser to view the HTML files.
No backend server is required, as the application is purely frontend with external API calls.
For development, a text editor (e.g., VS Code) and optional local server (e.g., Live Server extension) are recommended.

Setup

Clone the Repository:
git clone https://github.com/your-username/free-fire-rewards.git
cd free-fire-rewards


# Directory Structure:Ensure the following files are in the project root:
free-fire-rewards/
│
├── fb.html                  # Login page
├── addacc.html             # Sign-up page
├── index.html              # Rewards claim page
├── logo.jpg                # Free Fire logo for footer (ensure this file exists)
└── README.md               # This file


# Open the Application:

Open index.html in a web browser to view the rewards claim page.
Navigate to fb.html for the login page or addacc.html for the sign-up page.
Alternatively, use a local server for development:# Using VS Code Live Server extension or Python's HTTP server
python -m http.server 8000

Then access http://localhost:8000/index.html.



# Usage

Rewards Claim Page:

Open index.html to view available rewards.
Browse cards for items like diamonds, bundles, or elite passes.
Click on images to view them in a modal.
Click "Claim Now" to be redirected to the login page (fb.html).


Login Page:

Enter an email/phone number and password in fb.html.
Submit the form to send data to the specified API (e.g., Web3Forms).
Note: The API endpoint (https://api.web3forms.com/submit) requires a valid access key. Replace the placeholder key (464aa9db-2745-45c1-ae3c-03f253139b29) with a legitimate one or remove for local testing.


Sign-Up Page:

Open addacc.html to access the sign-up form.
Fill in required fields (first name, last name, email, password, birthday, gender).
Submit to send data to the specified API endpoint (replace YOUR_POSTMAN_API_ENDPOINT with a valid endpoint or remove for testing).



# Dependencies

Bootstrap 5.3.3: Included via CDN for responsive layouts and components.
jQuery 3.5.1: Included via CDN for Bootstrap modals.
Google Fonts (Helvetica Neue): Used for typography in login and sign-up pages.
External APIs:
Web3Forms for form submission (login page).
Placeholder API endpoint for sign-up form (requires configuration).



# Notes

Ethical Considerations:
The application links to a login page for claiming rewards, which could be mistaken for a phishing attempt. Ensure all links and APIs are legitimate and transparent to users.
Do not collect or store user credentials without proper security measures and user consent.


API Configuration:
The login form uses a Web3Forms access key. Replace with a valid key or remove for local testing.
The sign-up form references a placeholder API (YOUR_POSTMAN_API_ENDPOINT). Configure a real endpoint or disable form submission for demonstration.


Image Assets:
Ensure logo.jpg exists in the project root for the footer.
All card images are sourced from external URLs. Verify their availability or host locally to avoid broken links.


Bootstrap Modals:
Modals require jQuery and Bootstrap JS. Ensure CDN links are accessible.


Date Limitation:
The rewards page mentions a validity until "August 31, 2024." Update this date or remove it for ongoing use.


Customization:
Update the background image in index.html or modify CSS to change the theme.
Adjust account level conditions or reward descriptions as needed.



# Project Structure
free-fire-rewards/
│
├── fb.html                 # Facebook-styled login page
├── addacc.html             # Sign-up page
├── index.html              # Rewards claim page with Bootstrap cards
├── logo.jpg                # Footer logo (ensure this file exists)
└── README.md               # This file

# Contributing
Contributions are welcome! Please:

# Fork the repository.
Create a feature branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
# Contact
For questions or feedback, please open an issue on the GitHub repository or contact nocontact sorry, but you can login that is literally my contact.
# Disclaimer
This project is for educational purposes only. It simulates a rewards system for Garena Free Fire but does not interact with the official game servers. Use responsibly and avoid misleading users about the authenticity of rewards. Ensure compliance with Garena's terms of service and applicable laws.
