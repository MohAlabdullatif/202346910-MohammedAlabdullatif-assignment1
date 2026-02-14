Technical Documentation -- Moe Website Portfolio

1\. Project Overview

Moe Website is a personal portfolio designed to showcase my skills, projects, achievements, and contact information.

The website is fully responsive, includes dark/light mode functionality, and provides a personalized greeting based on the time of day.

Key Features:

Responsive multi-section layout: About Me, Projects, Achievements, Contact

Dark/Light theme toggle

Dynamic greeting message based on user's local time

Structured, readable, and accessible design

Clean and well-commented HTML, CSS, and JavaScript code

2\. File Structure

project-root/

│

├─ index.html           # Main HTML page

├─ css/

│   └─ style.css        # Styling, dark mode, and responsive design

├─ js/

│   └─ script.js        # JavaScript for theme toggle and greeting message

└─ assets/

    ├─ Me.jpg           # Profile image

    ├─ phys.jpg         # Achievement image: Physics

    ├─ edad.jpg         # Achievement image: Edad Program

    └─ CalcAward.jpg    # Achievement image: Calculus Award

3\. Technologies Used

HTML5 -- Semantic page structure

CSS3 -- Flexbox layout, responsive design, dark mode styling

JavaScript (ES6) -- Dynamic greeting messages and theme toggle

4\. Design and Layout

4.1 Header

Sticky header containing the site title, navigation links, greeting message, and theme toggle button

Navigation links scroll smoothly to the respective sections

4.2 Sections

About Me: Profile picture and brief bio

Projects: Highlights two main projects with descriptions

Achievements: Three key achievements with images and descriptions

Contact: Displays email and phone number

4.3 Footer

Links to all sections and LinkedIn profile

Design consistent with the header

4.4 Dark/Light Mode

Toggle button switches between dark and light themes

Implements a dark-mode CSS class on <body> to dynamically update background, text, and card styles

5\. JavaScript Functionality

5.1 Greeting Message

Uses the Date object to obtain the current hour

Displays a greeting based on the hour:

"Good Morning!" for hours 0--11

"Good Afternoon!" for hours 12--17

"Good Evening!" for hours 18--23

Injects the greeting into the #greeting element on page load (DOMContentLoaded)

5.2 Theme Toggle

Button with id="themeToggle" toggles the dark-mode class on <body>

Updates button text to indicate the current mode: "Dark Mode" or "Light Mode"

All dark mode styles are defined in css/style.css under body.dark-mode

6\. CSS Styling

Flexbox is used for layout and alignment

Responsive design: Media queries adjust layout for screens ≤768px

Cards: Each section uses .card elements with borders, padding, and rounded corners

Dark mode: Updates background, text, and link colors for improved accessibility

7\. Development Notes

Clean code principles: Proper indentation, organized files, semantic HTML elements

Comments: Key sections in CSS and JavaScript are commented for clarity

Accessibility: Proper headings, navigation links, and alt text for all images

Testing: Verified layout, dark/light mode, and greeting message across desktop and mobile devices

8\. Future Improvements

Add a portfolio projects gallery with images and links

Include interactive skill charts or graphs

Add a contact form with validation and email functionality

Further enhance SEO and accessibility
