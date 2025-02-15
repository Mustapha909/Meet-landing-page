# Meet Landing Page

A responsive landing page for "Meet" – a group chat application designed to make virtual collaboration seamless across devices. This project is a solution to a Frontend Mentor challenge.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Responsive Design](#responsive-design)
- [Challenges Faced](#challenges-faced)

## Overview

This project is a fully responsive landing page built with HTML and CSS. It adapts to different screen sizes, ensuring a great user experience across devices.

## Features

- Responsive layout that adjusts for mobile, tablet, and desktop.
- A modern and clean UI design.
- Interactive elements such as buttons and structured sections.
- Images optimized for different screen sizes.

## Technologies Used

- **HTML5**: Markup structure
- **CSS3**: Styling and responsive design
- **Flexbox & Grid**: Layout positioning
- **Media Queries**: Responsive design handling

## Installation

To run this project locally:

1. Clone the repository:
   ```sh
   git clone https://github.com/Mustapha909/Meet-landing-page.git
   ```
2. Navigate to the project folder:
   ```sh
   cd meet-landing-page
   ```
3. Open the `index.html` file in your browser.

## Usage

Simply open the `index.html` file in your preferred web browser to view the landing page.

## Responsive Design

The layout adapts based on screen width using media queries:

- **Desktop (1024px and above)**: Full layout with all elements visible.
- **Tablet (768px - 1023px)**: Adjusted layout for better readability.
- **Mobile (480px - 767px)**: Two images per row in the info section, optimized font sizes, and spacing.

## Challenges Faced

- **Hero Image Scaling Issue**: The hero image was larger than 100%, causing layout shifts. This was fixed by restricting its width.
- **Mobile Layout Adjustments**: On screens smaller than 480px, the `.info__content` images were stacked in a single column instead of two per row. Media queries were used to fix this.
