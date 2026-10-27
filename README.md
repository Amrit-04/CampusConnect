# Campus Connect 🏫

### Interactive College Event Showcase & Registration Portal

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-222222?style=flat&logo=github)](https://amrit-04.github.io/cc.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

Campus Connect is an accessible, responsive web portal designed for college students to explore upcoming campus activities, register for technical and cultural events, and get in touch with event organizers.

---

## ✨ Features

- **🚀 Interactive Event Modal Dialogue:** Dynamic event cards for Hackathon 2025, AI & Machine Learning Workshops, and Startup Connect with rich JavaScript modal views detailing dates, schedules, and venues.
- **📱 Fully Responsive Design:** Modern CSS layouts tailored for mobile, tablet, and desktop viewports.
- **📄 Multi-Page Architecture:**
  - `index.html`: Hero landing page, featured highlights, and quick access.
  - `events.html`: Comprehensive calendar and interactive event catalog.
  - `about.html`: Mission statement, campus community goals, and student leadership.
  - `contact.html`: Inquiry and event registration feedback form.
  - `success.html` & `failure.html`: Confirmation and status feedback screens.

---

## 📂 File Structure

```
CampusConnect/
├── index.html       # Main landing page
├── events.html      # Events directory with interactive modal
├── about.html       # About Campus Connect and organization details
├── contact.html     # Contact and inquiry form
├── success.html     # Submission confirmation view
├── failure.html     # Error / failure view
├── script.js        # Event modal logic and dynamic DOM rendering
├── style.css        # Clean responsive typography, card styles, and animations
├── images/          # Portal assets, banners, and logos
└── assests/         # Supporting stylesheets and icons
```

---

## 🚀 Running Locally

No build tools or package managers required. Simply clone and view:

```bash
# Clone the repository
git clone https://github.com/Amrit-04/CampusConnect.git
cd CampusConnect

# Open index.html in your preferred browser, or serve locally:
npx serve .
# or with Python:
python -m http.server 8000
```

Open `http://localhost:8000` to preview the site.

---

## 🌐 Live Deployment

A live deployment of this website is hosted via GitHub Pages at:  
👉 **[cc.github.io Deployment](https://amrit-04.github.io/cc.github.io/)**

---

## 📄 License

This project is licensed under the MIT License.