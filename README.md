# NetSphere Authority - Company Website

This repository contains the source code for the official website of **NetSphere Authority**, a Full-Stack & AI Web Studio based in Bengaluru. The website showcases the company's services, project portfolio, pricing plans, and provides a contact form for prospective clients.

## 🚀 Features
- **Responsive Design**: Built entirely with HTML5 and native CSS3, ensuring a smooth experience across desktop and mobile devices.
- **Dark Mode Aesthetic**: A modern, dark-themed UI with `Syne` and `DM Sans` typography for a professional look and feel.
- **Service & Portfolio Showcases**: Clean grid layouts highlighting technical domains like AI, Fintech, HealthTech, and AgriTech.
- **Direct Gmail Integration**: The integrated contact form seamlessly constructs a detailed query and redirects the user directly to a new Gmail compose tab addressed to `authoritynetsphere@gmail.com`.
- **Zero Dependencies**: Lightweight architecture with no external JavaScript frameworks or complex build steps.

## 🛠️ Usage
Since the website is built entirely with raw HTML, CSS, and vanilla JS, there is no build process required to run the project. 

To view the website locally:
1. Simply double-click on `index.html` to open it in your preferred web browser.
2. Alternatively, serve it via a local development server like VS Code's "Live Server" extension for hot reloading during development.

## 📁 Project Structure
- `index.html`: Contains the core content, layout, embedded styles (within the `<style>` tags), and the client-side JavaScript (within the `<script>` tag) handling the contact form submission.

## 📧 Contact Form Behavior
When the user submits the "Hire Us" / Contact form at the bottom of the page, the client-side script reads the form inputs (Name, Email, Service Interest, Budget, and Project Description) and automatically redirects the user to their Gmail account. A new tab will open with a pre-filled email (Subject and Body) directed to `authoritynetsphere@gmail.com` based on the user's explicit inputs, providing a friction-free intake experience.

## © License
© 2026 NetSphere Authority · Yuvan Chaudary
