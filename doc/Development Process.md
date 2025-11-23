✅ 📌 Process / Work Process (Step-By-Step Explanation)
1. Planning the Layout

I analyzed what sections a standard portfolio website should contain.

Decided on a clean single-page structure with easy navigation.

Selected a consistent color theme:

Blue (#3b82f6), Blue-Dark (#1e3a8a), White (#fff).

Planned a grid-based layout for skills and projects.

2. Building the HTML Structure

Created semantic sections such as:

<header>, <main>, <section>, <footer>.

Added a sticky navigation bar with links to different sections using IDs.

Designed the hero section with:

An introduction text area.

A rounded profile image.

Built the “About Me” text section.

Created a three-column skill grid using repetitive .skill cards.

Made the project cards using .project-card and placed two images inside each.

Added a contact form with input fields and a submit button.

3. Styling with Global CSS

Reset default browser styles with * { margin: 0; padding: 0; box-sizing: border-box; }.

Defined theme variables in :root:

Colors, spacing, border radius, shadows.

Applied the global font "Poppins" and background color.

4. Designing the Components

Header:

Added a blue gradient and shadow.

Made it sticky with position: sticky.

Hero Section:

Used Flexbox to place text and image side by side.

Styled profile image with a 50% border radius, blue border, and shadow.

About Section:

Used a white card with rounded corners and drop-shadow.

Skill Cards:

Grid layout with auto-fit for responsiveness.

Hover effect: lift-up animation + border highlight.

Project Cards:

Designed a fixed-size card with overflow hidden.

Added shadows and hover elevation.

5. Creating the CSS Image Slider Animation

Used two images (.img1, .img2) positioned absolutely.

Applied opacity, transform, and a custom @keyframes slideShow animation:

Image fade-in/out.

Slide up and slide down effect.

Each image has an animation delay to alternate between them.

This allowed the slider to work without any JavaScript.

6. Designing the Contact Section

Used a soft gradient background.

Styled form inputs with padding, border radius, and shadows.

Added a dark-blue button that lightens on hover.

7. Adding User Interaction Elements

Hover effects for buttons and skill cards.

“Back to Top” button fixed at the bottom right.

Smooth scrolling using:

html { scroll-behavior: smooth; }

8. Making the Website Responsive

Used CSS Grid auto-fit to adapt skills and projects to all screen sizes.

Ensured the hero section wraps properly on smaller devices.

Made images responsive using object-fit: cover.

9. Final Review

Cleaned the code and removed unused CSS.

Confirmed consistency in spacing, shadows, and fonts.

Tested in multiple browsers and screen sizes.

Ensured that all links work correctly.
