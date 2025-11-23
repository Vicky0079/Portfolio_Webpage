# Vicky — Personal Portfolio Website
A modern, responsive personal portfolio website designed for a web development student. This project showcases skills, projects, and contact information using clean HTML5 and advanced CSS3 styling without reliance on external frameworks or JavaScript libraries.

# 📖 Project Description
This repository contains the source code for a static portfolio website. It features a clean Blue & White color theme (#3b82f6), modern typography (Poppins), and various interactive UI elements.

The site is designed to be a "Single Page Application" style layout where the navigation links smooth-scroll to specific sections of the page (About, Skills, Projects, Contact).

# ✨ Key Features
1. Responsive Design: Utilizes CSS Grid (auto-fit) and Flexbox to adapt to different screen sizes.

2. CSS-Only Image Slider: The project cards feature a custom @keyframes animation (slideShow) that cycles through project screenshots automatically without using JavaScript.

3. Sticky Navigation: The header stays fixed at the top of the viewport for easy navigation.

4. Smooth Scrolling: Native CSS smooth scrolling behavior for anchor links and the "Back to Top" button.

5. Interactive UI:

* Hover effects on skill cards (transform/translate).

* Gradient backgrounds on the header.

* Styled Contact Form.

6. Custom Variables: Uses CSS :root variables for easy color theme and spacing management.

# 📂 Project Structure
```Plaintext
.
├── index.html          # The main HTML structure
├── style.css           # Global styles, variables, and animations
└── README.md           # Project documentation
```
Note: The code references local images (e.g., foodapp1.jpg, goalapp1.jpg). You must place images with these filenames in the root directory or update the src paths in the HTML to point to your own images.

# 🚀 Installation and Usage
Since this is a static website, no complex installation or build process (like Node.js or Python) is required.

# Prerequisites
* A modern web browser (Chrome, Firefox, Edge, Safari).

* A code editor (VS Code, Sublime Text) if you wish to edit the content.

# Steps to Run
* Clone or Download the Repository:

```bash
git clone https://github.com/Vicky0079/vicky-portfolio.git
```
Or simply download the ZIP file and extract it.

* Add Images: Ensure you have images in the folder matching the src attributes in the HTML (or update the HTML to match your image filenames).

* Open the Website:

* Navigate to the project folder.

* Double-click index.html to open it in your default web browser.

* Alternatively, if using VS Code, you can use the "Live Server" extension for real-time updates.

# 🎨 Customization
To make this portfolio your own:

* Update Content: Open index.html and replace the text (Name, "About Me" blurb, Skills list) with your own information.

* Change Colors: Open style.css and locate the :root section at the top. Change the hex codes to your preferred color palette:

```CSS
:root {
  --blue: #YOUR_COLOR;
  --blue-dark: #YOUR_DARKER_COLOR;
  /* ... */
}
```
* Screenshorts
<img width="1885" height="921" alt="Screenshot 2025-11-22 181131" src="https://github.com/user-attachments/assets/00a58406-b393-4b5b-aedf-a25b81245bc7" />

<img width="1870" height="911" alt="Screenshot 2025-11-22 200233" src="https://github.com/user-attachments/assets/fa325fea-5315-41b0-8f5e-6943e615d76a" />

<img width="1885" height="907" alt="Screenshot 2025-11-22 181144" src="https://github.com/user-attachments/assets/d61c8342-1bb4-4a2d-a682-46c7a99d9cc6" />

<img width="1866" height="912" alt="Screenshot 2025-11-22 181157" src="https://github.com/user-attachments/assets/30064f20-271b-4968-8f8e-77b939fe599d" />

