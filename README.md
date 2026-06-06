# 🏠 Future Residency Limited

Welcome to the official repository for **Future Residency Limited**—a modern, responsive real estate and residency website. This platform features a comprehensive multi-page layout designed to showcase real estate properties, facilitate user interaction, and provide a seamless navigation experience.

---

## 🛠️ Technologies Used

This project is built using standard front-end web technologies, focusing on clean structure, responsiveness, and minimal but effective interactivity.

*   **HTML5:** Used to build the structural semantic markup for all web pages.
*   **CSS3:** Custom styles to design layouts, handle typography, and implement the color palette.
*   **Bootstrap 5.2.2 (via CDN):** Utilized for rapid UI development, featuring:
    *   A fully responsive grid system.
    *   A sticky navigation bar (`sticky-top`) with a collapsible mobile hamburger menu (`navbar-toggler`).
*   **JavaScript (ES6):** Used for lightweight DOM manipulation and dynamic styling updates.

---

## 📂 Web Pages Included

The website contains a comprehensive suite of pages to handle standard customer journeys:

*   🏠 **Home (`index.html`):** The primary landing page welcoming users to Future Residency.
*   🔑 **Sign In & Login:** Securely designed interfaces for user authentication.
*   ✨ **Features:** Showcases premium properties and key residency benefits.
*   💼 **Service:** Details the company's real estate offerings, consultations, and packages.
*   💳 **Payment:** A clean interface designed for down payments or transaction processing.
*   📞 **Contact:** Contains an inquiry form and physical office location details.
*   ❓ **Help:** A dedicated support space or FAQ center to assist users navigating the portal.

---

## 💻 Code Architecture Highlights

### 1. Responsive Bootstrap Navigation Bar
The header features a modern, mobile-friendly navigation system that collapses smoothly into a burger menu on smaller viewports:
```html
<nav class="navbar sticky-top navbar-expand-lg" id="navbar">
  <div class="container-fluid">
    <a class="navbar-brand" id="website_name" href="#">
      <img id="nav_logo" src="images/logo_t.png"> Future Residency Limited
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
        <!-- Additional links go here -->
      </ul>
    </div>
  </div>
</nav>
```

### 2. Dynamic UI Interactivity
A native JavaScript utility toggles component text colors dynamically based on user interaction.
```JavaScript
function changeColor(x) {
  if (x.style.color === "gray") {
    x.style.color = "red";
  } else if (x.style.color === "red") {
    x.style.color = "none"; 
  }
}
```
---

## 🚀 How to Run the Project Locally
To view this website on your local machine, follow these simple steps:
1. **Clone the Repository**
2. **Navigate to the Project Directory** cd Future-Residency
3. **Launch the Website**
Since this is a front-end project utilizing static files (HTML, CSS, JavaScript) and Bootstrap via CDN, you do not need to install any heavy dependencies or run a local server.

Option A (Quickest): Locate the project folder in your file explorer and double-click index.html. It will instantly open in your default web browser.
Option B (VS Code users): If you use Visual Studio Code, right-click index.html and select Open with Live Server for real-time changes as you edit the code.
