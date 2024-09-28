# my-personal-portfolio-
Anees mir
 Interactive Webpage with Tabs, Menu, and Form Submission

This project is an interactive webpage that includes features like tabbed content navigation, a responsive side menu, and a feedback form submission to Google Sheets via Google Apps Script. It also includes smooth scrolling functionality and dynamic menu toggling for mobile devices.

Features

 1. Tabbed Content Navigation
    The webpage allows users to switch between different sections of content by clicking on tab links.
    Each tab corresponds to a content section, and only the active tab's content is displayed at a time.
    JavaScript manages adding and removing active states to the tab links and their corresponding content sections.

 2. Responsive Side Menu
    A side menu that slides in and out when toggled, providing easy access to different parts of the website.
    The menu can be opened and closed via buttons.
    Ideal for mobile or smaller screens.

 3. Scroll to Top Button
    A button is provided to allow users to quickly scroll to the top of the page.
    Smooth scrolling effect is applied for a better user experience.

 4. Feedback Form Submission
    The webpage includes a feedback form that submits data to a Google Sheet via Google Apps Script.
    On successful submission, the user receives a confirmation message, and the form resets itself.
    Any submission errors are logged in the console for troubleshooting.

 Technologies Used

 HTML: Structure of the webpage.
 CSS: Styling for tabs, menus, and content layout.
 JavaScript: Handles dynamic behaviors including tab switching, menu toggling, smooth scrolling, and form submission.
 Google Apps Script: Used for handling form submission to Google Sheets.

 Code Breakdown

 Tabs and Menu Interaction

 opentab(tabname): Handles tab switching by removing the active state from all tabs and only adding it to the clicked tab and its corresponding content.
 openMenu() / closeMenu(): Functions to open and close the side menu by adjusting its CSS `right` property.
 homeButton: Scrolls the page to the top when clicked, with a smooth scrolling effect.
 Form Submission
 The form is linked to a Google Apps Script using the provided script URL:
  javascript
  const scriptURL = 'https://script.google.com/macros/s/yourscriptid/exec';

