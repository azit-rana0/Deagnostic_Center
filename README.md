# Diagnostic Center Website

## Project Overview

This project is a replica of a diagnostic center's website, designed using **HTML** and **Tailwind CSS**. The site showcases features like tests and packages, special programs, promotional offers, and essential health services. It is fully responsive and optimized for a seamless user experience.

## [Live](https://azit-rana0.github.io/Deagnostic_Center/)

## Features

- **Special Programs Section**: Highlights unique healthcare services.
- **Popular Tests/Packages**: Displays quick links to commonly chosen diagnostic tests.
- **Search Tests and Packages**: Users can search for specific tests or health packages.
- **Promotions and Discounts**: Highlights special offers for various user demographics.
- **Quality Assurance**: Information on certifications, customer satisfaction, and quality checks.
- **Download App Section**: Promotes the diagnostic center's mobile app.
- **Educational Blog and Videos**: Features articles and videos for health awareness.
- **FAQs**: Provides answers to common user queries.

## Technologies Used

- **HTML**: For creating the structure of the webpage.
- **Tailwind CSS**: For responsive and utility-first styling.
- **JavaScript** *(optional)*: Can be added for interactivity.

## Installation and Setup

1. Clone the repository:
   ```bash
        git clone https://github.com/azit-rana0/Deagnostic_Center
   ```

2. install Tailwind CSS:
    ```bash
        npm install
    ```

3. Build Tailwind CSS:
    ```bash
        "scripts": {
    "build:css": "npx tailwindcss build src/tailwind.css -o dist/output.css"
        }
    ```

    Run the command to generate the CSS file:
    ```bash
        npm run build:css
    ```

4. Open index.html in your browser to view the site.

## Tailwind CSS Configuration
The Tailwind CSS configuration file (tailwind.config.js) can be customized to modify themes, colors, fonts, etc. Here's an example configuration:

    ```bash
        module.exports = {
        content: ["./*.html"],
        theme: {
            extend: {
            colors: {
                primary: "#004aad",
                secondary: "#f8c02d",
                accent: "#1d72b8",
            },
            },
        },
        plugins: [],
        };
    ```

## Folder Structure
    ```bash
        project/
    ├── src/
    │   ├── tailwind.css       # Main Tailwind CSS input file
    │   └── components/        # Optional reusable HTML components
    ├── dist/
    │   ├── output.css         # Generated CSS file
    ├── index.html             # Main HTML file
    ├── tailwind.config.js     # Tailwind configuration
    ├── README.md              # Project documentation
    └── package.json           # npm dependencies
    ```

## Customization Guide

1. **Colors**: Modify brand colors in tailwind.config.js.

2. **Typography**: Use Tailwind utility classes for text styles like headings, paragraphs, and buttons.

3. **Components**: Create reusable components for sections like cards, buttons, or modals.

## Contribution

Feel free to fork the repository and submit a pull request for new features, bug fixes, or improvements.

## Contact Information

For inquiries, feedback, or support, please reach out:

-  Website: [diagnostic center's website](https://azit-rana0.github.io/Deagnostic_Center/)
-  Social Media: Follow us on our github for updates and community engagement.
- Email: ajeetrana520@gmail.com