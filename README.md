# Web Portfolio: Nelson Fortunatti

This repository contains the source code for Nelson Fortunatti's personal web portfolio. The portfolio showcases projects, provides information about Nelson's skills and academic background, and includes a contact form.

## Project Overview

The website is a static multi-page site built with HTML, CSS, and JavaScript. It is designed to be responsive and includes features such as:

* **Homepage (`index.html`):** Introduces Nelson, highlights key skills, and provides an overview of featured projects.
* **Project Detail Pages (`project1.html`, `project2.html`, etc.):** Each project has its own page with a detailed description, a carousel of images, and key technical aspects or learnings.
* **About Section:** Details Nelson's academic background and professional focus on Embedded Systems, PCB design, IoT, and automation.
* **Contact Form:** Allows visitors to send messages (requires a backend service for actual email sending).
* **Multi-language Support (English/Spanish):** Content can be switched between English and Spanish using a language switcher in the navigation bar. Language preference is stored in `localStorage`.
* **Image Carousel:** Used on project detail pages to display multiple images for each project. Includes auto-play, pause on hover, and click-to-enlarge functionality.
* **Responsive Design:** Adapts to different screen sizes for optimal viewing on desktops, tablets, and mobile devices.

## Technologies Used

* **HTML5:** For the structure and content of the web pages.
* **CSS3:** For styling and layout, including responsive design features.
* **JavaScript (ES6+):** For dynamic functionalities such
    as:
    * Language switching.
    * Image carousel navigation and controls.
    * Modal display for enlarged images.
    * Smooth scrolling.

## Key Features Implemented/Updated

* **Consistent Branding:** Nelson Fortunatti's name and email (nelsonfortunatti@gmail.com) are now consistently displayed across all pages in the navigation logo and footer.
* **Image Display Optimization:**
    * Images on the homepage (cover, about me, project overviews) and project page carousels are set to `contain` within their allocated space, ensuring the full image is visible without zoom or cropping.
    * Project page carousel images can be clicked to view an enlarged version in a modal/lightbox.
* **Dynamic Content:**
    * Multi-language support for textual content and placeholders.
    * Interactive project carousels.

## File Structure

* `index.html`: The main landing page.
* `project1.html`, `project2.html`, `project3.html`, `project4.html`: Individual pages for each featured project.
* `style.css`: Contains all the CSS rules for styling the website.
* `images/`: Directory containing all images used in the portfolio (not included in this repository, must be added by the user).
    * `images/cover.jpg`
    * `images/about-me.jpg`
    * `images/project1/overview.jpg`, `images/project1/carousel-img1.jpg`, etc.
    * (Similar subdirectories and images for other projects)
* `README.md`: This file, providing an overview of the project.

## Setup and Usage

1.  Clone or download the repository.
2.  Ensure you have the `images` folder structured correctly with all necessary image files as referenced in the HTML and CSS.
3.  Open `index.html` in a web browser to view the portfolio.
4.  For the contact form to function, the `action` attribute of the form in `index.html` needs to be updated to point to a valid form processing service endpoint.
5.  Update the placeholder LinkedIn URL in `index.html` with the correct profile link.

## Notes

This portfolio is designed as a static website. For features like the contact form to be fully operational, integration with a backend service or a third-party form handler is required.
