## Learning Process

While building this project I faced some issues:

1. Initially I used `bg-linear-to-b` but later learned that the correct Tailwind class is `bg-gradient-to-b`.
2. I had difficulty understanding the difference between relative and absolute positioning.
3. I learned that absolute elements are positioned relative to the nearest parent with relative.
4. I tested sticky and fixed positioning multiple times before achieving the desired result.

These mistakes helped me understand Tailwind CSS positioning better.
# Hero Landing Page – Project Workspace

## Overview

This project is a modern, clean, and professional hero landing page for a digital workspace platform. It is built strictly using *HTML* and Tailwind CSS (via CDN), specifically designed to demonstrate advanced CSS positioning techniques (relative,  sticky`, and fixed`) without the use of any custom CSS files.

## Features

 Sticky Navigation Bar: A top navigation menu that remains visible as the user scrolls, featuring a frosted glass blur effect .
 Engaging Hero Section: Includes a light orange-to-white gradient background, bold centered typography, and strategically placed Call-to-Action (CTA) buttons.
 Floating Information Cards: Three visually distinct cards positioned dynamically around a central dashboard preview image using 

  1. **Tasks Card:** Displays tasks completed today.
  2. **Project Status Card:** Displays an "On Track" status.
  3. **Team Activity Card:** Displays online team members with overlapping avatars.
**Fixed Chat Widget:** A floating chat icon anchored to the bottom-right corner of the screen 

## Technologies Used
* **HTML:** Semantic structure and layout.
* **Tailwind CSS:** Utility-first CSS framework (loaded via CDN for immediate rendering).


## Learning Objectives Demonstrated
This project serves as a practical implementation of:
* Utility-first styling workflow.

* Z-index stacking contexts (z-10, z-20, z-50).
* Complex layout structuring using purely CSS classes

## How to Run

1. Download or clone the project.
2. Open the project folder in VS Code.
3. Make sure Tailwind CSS is installed.
4. Run Tailwind build command:
5. Open index.html in your browser.