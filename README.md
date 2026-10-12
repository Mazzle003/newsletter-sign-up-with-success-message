# Newsletter Sign-up with Success Message

A responsive newsletter subscription form built with Tailwind CSS. This project is part of the Ibrahim Assessment and is based on the Frontend Mentor challenge.

### The Project

The page displays a "Stay updated!" card that invites 60,000+ product managers to join monthly updates. It contains:

- A headline, benefits list with check icons
- An email input field (`email@example.com`)
- A "Subscribe to monthly newsletter" button

Core Flow:
1. User enters their email address in the form on `index.html`
2. JavaScript validates the email format (checks for empty field and invalid email)
3. If valid, clicking **Subscribe** redirects the user to `success.html`
4. The success page shows a confirmation message: "Thanks for subscribing!" with the user's email displayed, confirming they are successfully subscribed
5. User can dismiss the message and return to the main form

This flow is handled in `main.js` using localStorage / URL parameter to pass the email to the success page.

### Features

- Email validation with error states
- Success confirmation page with dynamic email
- Responsive layout (desktop card centered on dark background, stacked on mobile)
- Hover states on button and inputs
- Clean Tailwind styling

### Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript

### How to Run

1. Clone and open: https://github.com/Mazzle003/newsletter-sign-up-with-success-message.git

2. Open `index.html` with Live Server:
   http://127.0.0.1:53726/index.html

### Folder Structure
starter/
├── assets/ (images & fonts)
├── index.html
├── success.html
├── main.js
└── README.md