# CS50x QuickTab - Comprehensive Guide

[Watch the CS50x QuickTab Video](https://www.youtube.com/watch?v=mff6hMBsb6Q)

## CS50x QuickTab Readme

Welcome to the CS50x QuickTab project! This readme provides a comprehensive guide to understanding and using the CS50x QuickTab web application. Below, you'll find an overview of the project, its main components, and instructions for getting started.

### Overview
The CS50x QuickTab is a browser extension designed to enhance your experience while taking Harvard's CS50x course. This extension provides you with quick access to essential tools and resources for the course right from your browser's new tab page. Whether you're searching for relevant course materials, planning your study schedule, or simply customizing the interface, the CS50x QuickTab has you covered.

### Getting Started

To use the CS50x QuickTab, follow these steps:

1. **Download the Extension:** [Download the zip file](https://drive.google.com/file/d/1rUaYWJPDk8EVj8zTNWRyuwxzFui4TVgK/view?usp=sharing) containing the CS50x QuickTab extension.

2. **Unzip the File:** Extract the contents of the zip file to a location of your choice on your computer.

3. **Enable Developer Mode:**

   - **Google Chrome:** Open your Chrome browser and go to the Extensions page by entering `chrome://extensions/` in the address bar. Toggle on "Developer mode" using the switch at the top-right corner of the page.

   - **Microsoft Edge:** Similarly, open Edge and go to the Extensions page using `edge://extensions/`. Toggle on "Developer mode."

4. **Load the Extension:**

   - **Google Chrome:** Click the "Load unpacked" button and select the folder where you extracted the CS50x QuickTab extension files.

   - **Microsoft Edge:** Similarly, click the "Load unpacked" button and select the same folder.

5. **First-Time Setup:**

   - Name: Personalize your experience by providing your name for friendly greetings on the new tab page.
   - Background Color: Customize the background color of the new tab page. Choose from presets or select a custom color using the color picker.
   - Search Engine Selection: Choose your preferred search engine for quick and easy web searches related to the course.
   - Toggle Features: Decide which features you want to enable or disable, such as bookmarks, date display, time display, and personalized greetings.
   - Week Selection: Choose the current week of your CS50x course. This tailors content and resources based on your progress.
   - Finish Setup: Once you've configured your settings, click the "Finish Setup" button to save preferences and start using the CS50x QuickTab.

### Features
The CS50x QuickTab offers the following features:

- Week-By-Week Content: Access curated resources specific to your current week in the CS50x course.
- Background Customization: Choose a background color that suits your preference.
- Search Engine Integration: Quickly search for relevant course materials using your chosen search engine.
- Personalized Greetings: Enjoy a warm welcome with a personalized greeting each time you open a new tab.
- Date and Time Display: Stay organized by having the current date and time readily available.
- Bookmark Access: Quickly access a collection of essential resources based on the current week's content.

### Developer Guide

## Welcome to the CS50x QuickTab Developer Guide!

### Project Structure

The CS50x QuickTab project is structured as a web application using HTML, CSS, JavaScript, and Handlebars.js for templating. The main components of the project include:

- HTML Files: The project consists of three HTML files: index.html, credits.html, and setup.html. These files define the structure of the user interface and various modal popups.
- CSS Styles: CSS styling is applied through the styles.css file, defining the visual appearance of the application.
- JavaScript Logic: The main application logic is implemented in the main.js file. This includes handling user interactions, local storage management, and dynamic content rendering.
- CS50x Week Content: All the CS50x Content is stored inside data.js which is a very large array that holds the content, instructions, and bookmarks for the week.
- Handlebars Templates: Handlebars templates are used to generate dynamic content. Precompiled templates are stored in the hbs-templates folder and are used to render various sections of the UI.
- External Dependencies: The project relies on external dependencies like Bootstrap for styling and interactivity, and Handlebars.js for template rendering.

### Functionality Overview

The CS50x QuickTab is designed to provide an enhanced experience for CS50x students by offering personalized settings and quick access to relevant resources. Here's a brief overview of the main functionality:

#### Personalization and Setup

- Users are prompted to set their name, background color, search engine preference, and toggle various UI elements during the setup process.
- The setup.html page guides users through these personalization choices using a step-by-step carousel interface.

#### Quick Access to CS50x Resources

- The application provides quick access to CS50x resources based on the user's current week of study.
- Users can navigate through the weeks using a dropdown button that reveals the available resources for each week.

#### Dynamic Content Rendering

- Handlebars.js templates are used to dynamically generate content based on user settings and progress.
- Templates are precompiled and stored in the hbs-templates folder for efficient rendering.

#### Local Storage Management

- User preferences and progress are stored in the browser's local storage, allowing the application to remember settings between sessions.
- Preferences include the user's name, chosen search engine, background color, and toggled UI elements.

### Developer Contribution

If you're interested in contributing to the CS50x QuickTab project or exploring the code further, here are some steps to consider:

- Familiarize Yourself: Study the existing codebase, including HTML structure, CSS styling, JavaScript logic, and Handlebars templates.
- Extend Functionality: Consider adding new features, improving the user interface, or optimizing existing code.
- Bug Fixes: If you find any bugs or issues, you can contribute by fixing them and submitting a pull request.
- Enhance UI: Improve the visual design and responsiveness of the application to enhance the user experience.
- Optimize Code: Review the code for potential optimizations, such as reducing redundancy and improving performance.

### Conclusion

The CS50x QuickTab project is an innovative web application designed to assist CS50x students in their coursework. By exploring the codebase, you can gain a deeper understanding of its functionality and potentially contribute to its ongoing development. Whether you're a CS50x student or a curious developer, this guide provides insight into how the application works and how you can get involved. Happy coding!

---

Thanks to ChatGPT for writing this README.md!