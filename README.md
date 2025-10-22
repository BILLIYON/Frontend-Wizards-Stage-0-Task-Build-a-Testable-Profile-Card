# 🧑‍💻 Frontend Wizards — Stage 0: Profile Card

A simple, accessible, and responsive **Profile Card** built using **semantic HTML**, **modern CSS**, and **vanilla JavaScript**.  
This project fulfills the **Stage 0 Task** for the *Frontend Wizards* program.

---

## 🚀 Features

- Semantic and accessible HTML structure  
- Displays **real-time milliseconds** using `Date.now()`  
- Fully responsive layout (mobile → desktop)  
- Avatar image with proper `alt` text  
- Keyboard-friendly, focus-visible social links  
- Organized sections for **bio**, **hobbies**, and **dislikes**

---

## 🧠 Data Test IDs (for automated testing)

| Element | `data-testid` |
|----------|----------------|
| Profile Card Container | `test-profile-card` |
| User Name | `test-user-name` |
| Biography | `test-user-bio` |
| Current Time (ms) | `test-user-time` |
| Avatar Image | `test-user-avatar` |
| Social Links Container | `test-user-social-links` |
| Hobbies List | `test-user-hobbies` |
| Dislikes List | `test-user-dislikes` |

Each visible element includes a `data-testid` for automated testing compatibility ✅

---

## 🧩 Folder Structure

```

frontend-wizards-stage0/
├── index.html
├── style.css
└── script.js

````

---

## 💡 How It Works

- The time in milliseconds is fetched via JavaScript:
  ```js
  const timeElement = document.getElementById("time");
  function updateTime() {
    timeElement.textContent = Date.now();
  }
  updateTime();
  setInterval(updateTime, 1000);
````

* The layout is handled with Flexbox and adjusts across screen sizes.

---

## 🧭 Accessibility

* Uses semantic HTML (`<article>`, `<section>`, `<nav>`, etc.)
* All interactive elements (links) are keyboard-accessible
* Includes descriptive `alt` text for images
* Visible focus outline for accessibility compliance

---

## 🌍 Live Demo

🔗 **Live Site:** [https://your-netlify-or-github-pages-link](#)
💻 **GitHub Repo:** [https://github.com/your-username/frontend-wizards-stage0](#)

*(Replace the `#` with your actual URLs before submission.)*

---

## 🧰 Tech Stack

* **HTML5** — for semantic structure
* **CSS3 (Flexbox)** — for responsive design
* **JavaScript (ES6)** — for dynamic time rendering

---

## ✅ Submission Notes

This project meets all acceptance criteria for *Frontend Wizards — Stage 0*:

* All `data-testid` attributes included
* Semantic, accessible structure
* Responsive and visually clean design
* Functional, testable, and hosted online

---

### 👨‍🎨 Author

**John Billon**
Frontend & Cloud Engineer in training | Passionate about clean code and beautiful UI
🌐 [GitHub](https://github.com/your-username) • [Twitter](https://twitter.com/your-handle) • [LinkedIn](https://linkedin.com/in/your-profile)
