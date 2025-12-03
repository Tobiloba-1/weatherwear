AI Clothing Recommendation & Styling Assistant
Overview

A web application that provides personalized clothing recommendations and styling advice using OpenAI’s GPT models. Users can submit preferences or upload outfit images for AI-generated suggestions.

Features

User Authentication: Login with role-based access.

Clothing Recommendations: Input style, occasion, and body type; get AI-generated suggestions.

Styling Assistant: Upload images for fashion advice, with formatted, readable responses.

Feedback System: Users submit feedback via a dedicated section, with clear icons.

Responsive UI: TailwindCSS ensures mobile-friendly design.

Technologies

Backend: PHP, MySQL, cURL for API requests

Frontend: HTML, TailwindCSS

API: OpenAI GPT-3.5/4

Icons: Font Awesome

Installation

Clone the repo:

git clone https://github.com/Tobiloba-1/weatherwear


Set up WAMP/XAMPP with PHP & MySQL.

Import database/db.sql and configure db.php.

Set OpenAI API key in .env or in the script.

Access via http://localhost/tomi/auth/login.php.

Usage

Login with email/password.

Submit clothing preferences for AI recommendations.

Upload outfit images for styling advice.

View suggestions in a clean, formatted layout.

Security

Use environment variables for API keys.

Only allow .jpeg/.png uploads <5MB.

Sanitize inputs to prevent SQL Injection and XSS.

Future Improvements

Real-time AI chat for styling advice.

User profiles with saved preferences.

Advanced image analysis for color/outfit matching.

# weatherwear
