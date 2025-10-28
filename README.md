A **modern, responsive business intelligence dashboard** built with **Vue 3**, **Tailwind CSS**, and **Font Awesome** — designed for seamless analytics and professional presentation.

![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![Vue](https://img.shields.io/badge/Vue-3.0-green.svg)
![Tailwind](https://img.shields.io/badge/Tailwind-CSS-38B2AC.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🚀 Features

* **Modern UI/UX** — Elegant, professional, and intuitive layout
* **Fully Responsive** — Optimized for mobile, tablet, and desktop
* **Multi-Level Navigation** — Sidebar menus with submenus and child routes
* **Real-Time Notifications** — Built-in system with badge counts
* **Interactive Charts** — Easily connect with Chart.js or ApexCharts
* **WhatsApp Support Widget** — Integrated quick-chat feature
* **Dark & Light Themes** — Toggle with persistent theme state
* **Professional Components** — Stats cards, project tables, and activity feeds

---

## 🛠️ Tech Stack

| Technology               | Description                                          |
| ------------------------ | ---------------------------------------------------- |
| **Vue 3**                | Reactive frontend framework (Composition API)        |
| **Tailwind CSS**         | Utility-first CSS for rapid UI design                |
| **Font Awesome 6**       | Modern icon pack                                     |
| **Google Fonts (Inter)** | Clean, modern typography                             |
| **No Build Step**        | Works directly in the browser — no bundling required |

---

## 📦 Installation

### 🔹 Option 1: Direct Usage

1. Download the `index.html` file
2. Open it directly in your web browser
3. No installation or build process needed!

### 🔹 Option 2: Local Development

```bash
# Clone the repository
git clone https://github.com/sakshsky/sakshsky-admin-dashboard.git

# Navigate to project folder
cd sakshsky-admin-dashboard

# Open in VS Code (or any editor)
code .
```

### 🔹 Option 3: Integrate into an Existing Vue Project

1. Copy the Vue Composition API code into your component
2. Add the Tailwind and Font Awesome dependencies
3. Ensure your project includes:

   * Vue 3
   * Tailwind CSS
   * Font Awesome

---

## 🎯 Quick Start

**Add Dependencies in HTML:**

```html
<div id="app"></div>

<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
<script src="https://cdn.tailwindcss.com"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

**Customization Options:**

* Update colors in the `<style>` section
* Edit navigation in the `menuItems` array
* Modify `notifications` for alert content
* Add your WhatsApp number to the chat widget

---

## 📱 Responsive Design

| Device      | Width          |
| ----------- | -------------- |
| **Mobile**  | < 768px        |
| **Tablet**  | 768px – 1023px |
| **Desktop** | ≥ 1024px       |

---

## 🎨 Customization

### 🔸 Change Card Gradients

```css
.stat-card-gradient-1 {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### 🔸 Add Menu Items

```javascript
menuItems: ref([
  { id: 1, name: 'Dashboard', icon: 'fas fa-home', link: '#' }
  // Add more items...
])
```

### 🔸 Modify Notifications

```javascript
notifications: ref([
  {
    id: 1,
    title: 'New Alert',
    message: 'Dashboard updated successfully!',
    time: 'Just now',
    icon: 'fas fa-bell',
    iconBg: 'bg-blue-500',
    read: false
  }
])
```

---

## 🔧 Configuration

### WhatsApp Integration

Update your WhatsApp number:

```html
<a href="https://wa.me/YOUR_PHONE_NUMBER" target="_blank">
```

### Theme Persistence

User’s theme (dark/light) is stored in `localStorage` and auto-applied on page load.

---

## 📂 Project Structure

```
sakshsky-admin-dashboard/
├── index.html          # Main application file
├── README.md           # Documentation
└── (assets/)           # Optional assets and icons
```

---

## 🚀 Deployment

### 🔹 GitHub Pages

1. Fork this repository
2. Enable **GitHub Pages** in repo settings
3. Deployment URL:

   ```
   https://sakshsky.github.io/sakshsky-admin-dashboard
   ```

### 🔹 Netlify

1. Upload the `index.html` file
2. Site deploys instantly

### 🔹 Vercel

1. Link your GitHub repo
2. Deploy in one click

---

## 🤝 Contributing

Contributions are always welcome!

### Development Workflow

1. Fork the repository
2. Create your feature branch

   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit changes

   ```bash
   git commit -m "Add AmazingFeature"
   ```
4. Push your branch

   ```bash
   git push origin feature/AmazingFeature
   ```
5. Submit a Pull Request

---

## 🧩 Roadmap / Todo

* [ ] Chart.js data visualization
* [ ] API-driven backend integration
* [ ] Authentication system
* [ ] Real-time updates (WebSockets)
* [ ] Multi-language support
* [ ] Data filtering and sorting
* [ ] Export to CSV / PDF
* [ ] Print-friendly view

---

## 🐛 Known Issues

* Table may require horizontal scrolling on smaller screens
* Some gradient effects vary slightly by browser
* WhatsApp widget needs manual phone configuration

---

## 📞 Support

Need help?

* Check [Issues](https://github.com/sakshsky/sakshsky-admin-dashboard/issues)
* Open a new issue with details
* Or email: **[sakshsky@example.com](mailto:sakshsky@example.com)**

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

* [Vue.js](https://vuejs.org/) — Progressive JavaScript Framework
* [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS Framework
* [Font Awesome](https://fontawesome.com/) — Icon Pack
* [Unsplash](https://unsplash.com/) — Free Images

---

## 🌐 Live Demo

🔗 [https://sakshsky.github.io/sakshsky-admin-dashboard](https://sakshsky.github.io/sakshsky-admin-dashboard)

---

**Note:**
This is a **frontend-only** dashboard. For production environments, connect it with an API or backend system to display live data dynamically.
