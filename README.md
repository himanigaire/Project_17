# Responsive Navigation Menu

This project is a **Responsive Navigation Menu** built using **HTML**, **CSS**, and **JavaScript**. The menu adapts to different screen sizes and can be toggled on mobile devices using a hamburger icon.

## Features

- **Responsive Design**: The menu layout adjusts automatically for different screen sizes.
- **Hamburger Menu**: On smaller screens (below 768px), the menu is hidden and can be toggled by clicking the hamburger icon.
- **Flexbox Layout**: The navigation menu is arranged using the CSS Flexbox model.
- **Media Queries**: Used to implement the responsive design for different screen sizes.

## Technologies Used

- **HTML**: For the structure of the navigation bar.
- **CSS**: For styling the navigation menu, including responsiveness and hover effects.
- **JavaScript**: For toggling the visibility of the menu on smaller screens.

## Project Structure

- **HTML File (17.html)**: Defines the structure of the navigation menu and includes the necessary references to the CSS and JavaScript files.
- **CSS File (17.css)**: Contains the styles for the navigation bar, including the layout, responsive design, and hover effects.
- **JavaScript File (17.js)**: Contains the functionality to toggle the navigation menu visibility on mobile devices.

## How to Use

1. **Responsive Design**:
   - On larger screens (greater than 768px), the navigation links are displayed horizontally.
   - On smaller screens (768px and below), the links are hidden by default and can be shown by clicking the hamburger icon (☰).

2. **Toggling the Menu**:
   - The hamburger icon appears on mobile view.
   - Click the icon to show or hide the navigation links.

## File Descriptions

- **index.html**: 
    - Contains the structure of the navigation bar with links for Home, About, Services, Portfolio, and Contact.
    - Includes the hamburger icon (`☰`) for toggling the menu on smaller screens.

- **17.css**:
    - **Flexbox** is used for horizontal alignment of navigation links on larger screens.
    - **Media Queries** ensure that the navigation adapts to screen sizes below 768px, showing the hamburger icon and hiding the links until toggled.
    - Styles for the logo, menu links, and the hamburger icon.

- **17.js**:
    - Contains the `toggleMenu()` function which toggles the `active` class on the navigation links to show/hide them on small screens.

## Setup Instructions

1. Download or clone the repository.
2. Open the `17.html` file in your browser to view the responsive navigation menu.
3. Resize the browser window to see the responsive behavior of the navigation menu.

## Author

Created by **Himani Gaire**.
