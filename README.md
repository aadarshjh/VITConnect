# VITConnect

VITConnect is a centralized web platform designed to simplify campus life at **Vellore Institute of Technology (VIT)**. From navigating the campus to staying updated with events, clubs, and daily mess menus, VITConnect brings everything students need into one place.

---

## 🌟 Features

| Feature | Description |
|---|---|
| 🏠 **Home** | Central dashboard with announcements and quick-access links to all modules |
| 🍽️ **Mess Menu** | View daily and weekly mess menus; highlights today's meals by type |
| 🎓 **Club Registration** | Browse available clubs, view registration status, and submit a registration form |
| 🎉 **Events** | Explore upcoming campus events with category filters, date-range search, and a countdown timer |
| 🗺️ **Campus Directions** | Interactive map (powered by Leaflet) for navigating between campus buildings |
| ❓ **FAQ** | Quick answers to common student queries |
| 🛍️ **Shops** | Directory of campus shops with open/closed status, category filters, and favouriting |
| 💊 **Medical Store** | Information on the on-campus medical store and its services |
| 💬 **Feedback** | Submit feedback about your campus experience |
| ℹ️ **About** | Learn about the vision and the team behind VITConnect |

---

## 🛠️ Tech Stack

- **HTML5** – semantic page structure
- **CSS3** – responsive layout and styling (`styles.css`)
- **Vanilla JavaScript** – dynamic behaviour for each module
- **[Leaflet.js](https://leafletjs.com/)** – interactive campus map and routing
- **Google Apps Script** – backend form submission for club registrations

---

## 📁 Project Structure

```
VITConnect/
├── index.html            # Home page
├── about_final.html      # About page
├── clubs.html            # Club registration page
├── events_final.html     # Events listing page
├── maps_final.html       # Campus directions / map page
├── faq_final.html        # FAQ page
├── shops.html            # Campus shops directory
├── medical_store.html    # Medical store information
├── mess_menu.html        # Mess menu page
├── feedback.html         # Feedback form
├── styles.css            # Global stylesheet
├── index.js              # Home page scripts
├── clubs.js              # Club registration scripts
├── events.js             # Events filter & countdown scripts
├── maps.js               # Map & routing scripts
├── faq.js                # FAQ accordion scripts
├── shops.js              # Shops filter & favourites scripts
├── mess.js               # Mess menu scripts
└── medical_store.js      # Medical store scripts
```

---

## 🚀 Getting Started

VITConnect is a fully static web application — no build step or server required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/aadarshjh/VITConnect.git
   cd VITConnect
   ```

2. **Open in a browser**
   - Simply open `index.html` in any modern web browser, **or**
   - Serve the directory with any local HTTP server, for example:
     ```bash
     # Python 3
     python -m http.server 8080
     ```
     Then visit `http://localhost:8080`.

---

## 👥 Team

| Name | Role |
|---|---|
| **Adarsh Kumar Jha** | Founder & Developer |
| **Keshav Sharma** | UI/UX Designer |

---

## 📄 License

© 2026 VITConnect. All rights reserved.
