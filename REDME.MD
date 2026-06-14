# Hero Landing Page – Project Workspace

## Overview
This project is a modern, clean, and professional hero landing page for a digital workspace platform. It is built strictly using **HTML5** and **Tailwind CSS** (via CDN), specifically designed to demonstrate advanced CSS positioning techniques (`relative`, `absolute`, `sticky`, and `fixed`) without the use of any custom CSS files.

## Features
* **Sticky Navigation Bar:** A top navigation menu that remains visible as the user scrolls, featuring a frosted glass blur effect (`sticky`, `top-0`, `z-50`).
* **Engaging Hero Section:** Includes a light orange-to-white gradient background, bold centered typography, and strategically placed Call-to-Action (CTA) buttons.
* **Floating Information Cards:** Three visually distinct cards positioned dynamically around a central dashboard preview image using `absolute` positioning and `z-index`:
  1. **Tasks Card:** Displays tasks completed today.
  2. **Project Status Card:** Displays an "On Track" status.
  3. **Team Activity Card:** Displays online team members with overlapping avatars.
* **Fixed Chat Widget:** A floating chat icon anchored to the bottom-right corner of the screen (`fixed`, `bottom-6`, `right-6`).

## Technologies Used
* **HTML5:** Semantic structure and layout.
* **Tailwind CSS:** Utility-first CSS framework (loaded via CDN for immediate rendering).

## Setup & Execution
Because this project utilizes the Tailwind CSS CDN, there is no need to install Node.js, npm packages, or any build tools.

1. Download or save the provided code as an `index.html` file.
2. Double-click the `index.html` file to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Ensure you have an active internet connection so the Tailwind CSS CDN can load properly.

## Learning Objectives Demonstrated
This project serves as a practical implementation of:
* Utility-first styling workflow.
* Spacing and typography management (`p-*`, `m-*`, `text-*`).
* Z-index stacking contexts (`z-10`, `z-20`, `z-50`).
* Complex layout structuring using purely CSS classes