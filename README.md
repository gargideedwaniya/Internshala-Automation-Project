# Internshala Automation

## Overview

This project automates tasks on Internshala using Puppeteer, Node.js, and JavaScript. It simplifies resume building and internship applications by filling out details and applying for internships based on provided data.

## Features

- Logs into Internshala with provided credentials.
- Fills out resume details (graduation, training, work samples) using data from `data.js`.
- Applies for internships listed in a specific internship fair page.
- Submits applications with customized answers.
Run the Script
Execute the main script using Node.js:

node script.js
### Notes
- Adjust timeouts (setTimeout) based on your network speed and system performance.
- Ensure all selectors (waitForSelector) match the latest version of Internshala's UI.
