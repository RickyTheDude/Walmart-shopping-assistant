# SmartBasket - Your AI Shopping Companion

SmartBasket is an AI-powered web application designed to revolutionize your grocery shopping experience. It helps you build smart shopping lists, provides instant product recommendations with in-store locations, and guides you to the shortest checkout queues.

---

## Features

* **Intelligent List Building:** Use text or voice input to quickly create your shopping list. Items are converted into interactive "pills" for easy management.
* **AI Product Recommendations:** Get tailored suggestions for specific items, complete with product images, descriptions, and precise shelf/row numbers.
* **Real-time Progress Tracking:** A progress bar keeps you updated on your shopping journey.
* **Smart Checkout Guidance:** Once your list is complete, SmartBasket directs you to the fastest available checkout counter.
* **Voice Input:** Leverage the Web Speech API for hands-free list creation.

---

## Project Structure

```

smartbasket-app/
├── index.html            // Main application entry point
├── src/
│   ├── css/
│   │   └── style.css   // Custom CSS for styling
│   └── js/
│       ├── main.js     // Core application logic and DOM manipulation
│       ├── data.js     // Static data (e.g., product recommendations)
│       └── utils.js    // Reusable utility functions
└── README.md             // This file

````

---

## How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/smartbasket-app.git](https://github.com/YOUR_USERNAME/smartbasket-app.git)
    cd smartbasket-app
    ```
2.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

    * **Note on Voice Input:** For the voice input feature to work reliably, your browser might require the page to be served over HTTPS. If you experience issues, consider using a simple local web server (e.g., `python -m http.server` in the project root) or deploying it to GitHub Pages.

---
## Technologies Used

* **HTML5**
* **CSS3** (with Tailwind CSS CDN)
* **JavaScript** (ES Modules, Web Speech API)