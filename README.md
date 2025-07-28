# Health Care - Javascript Website Template (Design-2)

<img width="1421" height="701" alt="Screenshot 2025-07-28 at 17 30 18" src="https://github.com/user-attachments/assets/30d4a466-ddc0-472b-b4fc-6b8f422a6c7f" /> <img width="1178" height="807" alt="Screenshot 2025-07-28 at 17 31 03" src="https://github.com/user-attachments/assets/e8f17155-ce35-41a1-909c-f7c0a2d8a655" /> <img width="1181" height="874" alt="Screenshot 2025-07-28 at 17 31 26" src="https://github.com/user-attachments/assets/1c21f880-11ef-4c17-b21c-32d785543764" />

---

## Project Summary

This is a responsive, modern health care website built with HTML, CSS, and JavaScript. It is designed for clinics, hospitals, or health-related organizations to showcase their services, departments, and contact information. The project demonstrates best practices in web design, UI/UX, and responsive layouts, making it a great learning resource for beginners and intermediate developers.

- **Live Demo:** [https://healthcare-template-2.netlify.app/](https://healthcare-template-2.netlify.app/)

---

## Table of Contents

- [Project Summary](#project-summary)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Component & Code Walkthrough](#component--code-walkthrough)
- [How to Reuse Components](#how-to-reuse-components)
- [Keywords](#keywords)
- [Conclusion](#conclusion)

---

## Features

- Responsive navigation bar with burger menu for mobile
- Hero section with a call-to-action
- Appointment booking form (UI only)
- Services section with icons
- Quality highlights
- About section with image and description
- Departments overview
- Footer with contact, departments, address, and social links
- Fully responsive design for all devices

---

## Project Structure

```bash
health-website-main/
│
├── index.html         # Main HTML file
├── style.css          # Stylesheet
├── index.js           # JavaScript for navbar interactivity
├── img/               # Images and icons
│   ├── favicon.ico
│   ├── logo.png
│   ├── pic1.jpg
│   └── pic2.jpg
```

---

## Technologies Used

- HTML5
- CSS3 (with Flexbox and media queries)
- JavaScript (ES6)
- Font Awesome (CDN)
- Google Fonts (CDN)

---

## How to Run

To view the website locally, follow these steps:

1. **Open the Project Folder:**
   - Download or clone the repository.
   - Open the `health-website-main` folder.
2. **Open in Browser:**
   - Double-click `index.html` or right-click and choose "Open With" → your browser.
3. **(Optional) Run a Local Server:**
   - For dynamic features or best practice, run a local server:
     - With Python 3: `python3 -m http.server`
     - Open `http://localhost:8000` in your browser.

---

## Component & Code Walkthrough

### index.html

- **DOCTYPE and Meta Tags:** Standard HTML5 setup with viewport for responsiveness.
- **Navbar:** Responsive navigation with logo and burger menu for mobile.
- **Main Section:** Hero text and appointment form (UI only, not connected to backend).
- **Services:** Grid of service cards with Font Awesome icons.
- **Quality:** Highlights clinic strengths.
- **About:** Image and description of the clinic.
- **Departments:** List of medical departments.
- **Footer:** Contact info, departments, address, social icons.

### style.css

- Uses Google Fonts and Font Awesome.
- Flexbox for layout, media queries for responsiveness.
- Custom styles for each section and component.
- Mobile-first adjustments for navigation and layout.

### index.js

- Handles burger menu click to toggle navigation on mobile:
  
  ```js
  burger=document.querySelector('.burger')
  navbarItems=document.querySelector('.navbar-items')
  nav=document.querySelector('.nav')
  burger.addEventListener('click',()=>{
     navbarItems.classList.toggle('h-class')
     nav.classList.toggle('v-class')
  })
  ```

### img/

- Contains favicon, logo, and section images.

---

## How to Reuse Components

- **Navbar & Footer:** Copy HTML and CSS blocks. Update links and icons as needed.
- **Appointment Form:** Use as a template for UI forms. Add backend logic as required.
- **Service/Department Cards:** Reuse card structure for other content types.
- **Responsive Layout:** Media queries and Flexbox can be adapted for other projects.

---

## Keywords

healthcare, responsive website, HTML, CSS, JavaScript, clinic, hospital, appointment, UI, web design, template, Font Awesome, Google Fonts, mobile-friendly

---

## Conclusion

This project is a clean, modern template for health care websites. It demonstrates responsive design, modular components, and best practices in front-end development. Feel free to customize and extend it for your own needs or use it as a learning resource.

---

Happy coding! 🎉

Thank you!

---
