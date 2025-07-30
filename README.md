برنامه توسعه املاک به صورت آزمایشی و رایگان
# Real Estate Management Web App
A clean and responsive client-side web application for managing real estate listings. The project is fully implemented using vanilla HTML, CSS, and JavaScript, with no frameworks or backend required.

## Overview
This app enables users to:
- Add and manage property listings for:
  - Sale (house, shop, land)
  - Rent (house, shop)
  - Customer requests (buy or rent)
- Navigate between different sections using a simple tab-like UI
- Store and retrieve data using the browser’s localStorage
- Edit or delete entries from a dashboard view
- Use the application offline, directly in the browser

## Features
- Interactive UI with form validation
- Responsive layout for mobile and desktop
- Clean separation between sections:
  - Sale
  - Rent
  - Requests
  - Dashboard
- Custom fields and dynamic form behavior depending on property type
- No dependencies or external libraries

## Installation
No installation needed. Just download and open `index.html` in any modern browser.
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
open index.html

##Technologies
HTML5
CSS3
JavaScript (ES6+)
LocalStorage (for client-side data persistence)

##Usage Notes
All form data is stored in localStorage
Data will persist between sessions unless browser storage is cleared
Supports different property types with conditional form inputs
Mobile-friendly layout with basic media queries

##Possible Future Improvements
Integrate with a backend for database support
Add search and filtering capabilities
Implement login/authentication
Support for file/image uploads
