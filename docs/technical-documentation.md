Technical Documentation – Moe Website Portfolio
1. Project Overview

Moe Website is a personal portfolio website designed to showcase my skills, projects, achievements, and contact information.
The website is fully responsive, includes dark/light mode functionality, and provides a personalized greeting based on the time of day.

Key Features:

Responsive multi-section layout (About Me, Projects, Achievements, Contact)

Dark/Light theme toggle

Greeting message based on user’s local time

Structured, readable, and accessible design

Clean and well-commented HTML, CSS, and JavaScript code

2. File Structure
project-root/
│
├─ index.html           # Main HTML page
├─ css/
│   └─ style.css        # All styling including dark mode and responsive design
├─ js/
│   └─ script.js        # JavaScript for theme toggle and greeting message
└─ assets/
    ├─ Me.jpg           # Profile image
    ├─ phys.jpg         # Achievement image: Physics
    ├─ edad.jpg         # Achievement image: Edad Program
    └─ CalcAward.jpg    # Achievement image: Calculus Award

3. Technologies Used

HTML5 – Page structure and semantic elements

CSS3 – Styling, Flexbox layout, responsive design, and dark mode

JavaScript (ES6) – Dynamic greeting messages and theme toggle functionality

4. Design and Layout
4.1 Header

Sticky header with site title, navigation links, greeting message, and theme toggle button.

Navigation links scroll smoothly to the respective sections.

4.2 Sections

About Me: Displays profile picture and a brief bio.

Projects: Highlights two main projects with descriptions and relevant details.

Achievements: Shows three key achievements with images and descriptions.

Contact: Displays email and phone number.

4.3 Footer

Links to all sections plus LinkedIn profile.

Consistent design with header.

4.4 Dark/Light Mode

Toggle button switches between dark and light themes.

Uses a CSS class (dark-mode) to update background colors, text colors, and card styles dynamically.

5. JavaScript Functionality
5.1 Greeting Message

Uses the Date object to get the current hour.

Displays:

"Good Morning!" for hours 0–11

"Good Afternoon!" for hours 12–17

"Good Evening!" for hours 18–23

Injects the greeting into the #greeting element on page load (DOMContentLoaded).

5.2 Theme Toggle

Button with id="themeToggle" toggles dark-mode on the <body> element.

Updates button text to indicate the current mode: "Dark Mode" or "Light Mode".

All styles for dark mode are defined in css/style.css under the body.dark-mode selector.

6. CSS Styling

Flexbox used for layout and alignment.

Responsive design: Media queries adjust layout for screens ≤768px.

Cards: Each section uses .card elements for content, with borders, padding, and rounded corners.

Dark mode: Changes background colors, text colors, and link colors for better accessibility at night.

7. Development Notes

Clean code principles: Proper indentation, organized files, semantic HTML elements.

Comments: Key sections in CSS and JS are commented for clarity.

Accessibility: Navigation links, proper headings, and alt text for all images.

Testing: Verified layout, dark/light mode, and greeting message across desktop and mobile devices.

8. Future Improvements

Add a portfolio projects gallery with images and links.

Include interactive skill charts or graphs.

Add contact form with validation and email functionality.

Enhance SEO and accessibility further.
