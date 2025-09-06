Md. Maruf Mullah — Personal Portfolio Website (WordPress)
Overview

This is the WordPress-based personal portfolio website of Md. Maruf Mullah, a Mechanical Engineering graduate from MIST. The website showcases professional information including About Me, Education, Experience, Projects, Skills, and Contact details. It also features a CV download button for visitors.

The design is responsive, modern, and user-friendly, optimized for both desktop and mobile devices.

Features

Hero Section: Animated “Welcome to My Personal Website” heading with a subtitle.

Navigation Bar: Compact, sticky or static navbar for easy navigation.

Sections:

About Me

Education

Experience

Projects & Research

Skills

Contact

CV Download Button: Direct download link for your CV (Google Drive link).

Responsive Design: Works seamlessly across desktops, tablets, and mobiles.

Custom CSS: Adjust spacing, colors, and font styling via Appearance → Customize → Additional CSS.

Animations: Fade-in sections and interactive buttons using JavaScript or built-in WordPress block animations.

WordPress Setup Notes

Theme Used: Authon Personal Blog (or your chosen theme).

Customizations:

Adjusted Additional CSS to remove extra gap between navbar and first block:

.site-header, .main-navigation {
  margin-bottom: 0 !important;
  padding-bottom: 0 !important;
}

.wp-block-cover:first-of-type,
.site-content, .entry-content {
  margin-top: 0 !important;
  padding-top: 0 !important;
}


Navbar colors and text adjusted for readability.

Hero section configured using the Cover block.

CV Download Button: Added via a Custom HTML block or button block linking to your Google Drive CV file.

Installation / Deployment

WordPress Installation: Install WordPress on your hosting environment.

Theme Setup: Install and activate your chosen theme.

Add Pages/Blocks:

Use Cover blocks for hero sections.

Use Section blocks for About, Education, Experience, Projects, Skills, Contact.

Add CV Button:

Insert a Button block or Custom HTML block.

Link it to your Google Drive file (make sure the file is publicly shareable).

Customize CSS: Add any spacing, colors, or font adjustments under Appearance → Customize → Additional CSS.

Notes

Responsive Design: Check different devices to ensure spacing and layout are correct.

CV Link: Use the direct Google Drive shareable link for reliable download.

Animations: You can add simple fade-in or typing effects using JS in a Custom HTML block or plugins.

License


This project is for personal and educational use. You can modify or extend it for your own portfolio.