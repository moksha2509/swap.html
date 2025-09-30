# 💱 CashSwap — Your Campus Exchange

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple, single-page web application designed for students on a campus to facilitate peer-to-peer exchange of **Cash** for **UPI (Unified Payments Interface)** transactions, and vice-versa. It acts as a local bulletin board for instant, small-scale cash/digital currency swaps.

## ✨ Features

CashSwap provides a clean, mobile-friendly interface for posting and viewing exchange requests.

* **➕ Post New Requests:** Easily post a request detailing the amount (in ₹), what you **Have** (Cash or UPI) and what you **Need** (Cash or UPI), along with your contact information and meeting details.
* **📋 Real-Time Request List:** View all active exchange requests, sorted by the most recent.
* **🔍 Search & Filter:** Quickly find specific requests by searching through details or filtering by transaction type (`Cash -> UPI` or `UPI -> Cash`).
* **🔒 Local Storage:** All requests are stored locally in your browser's **Local Storage**, meaning they persist even after you close and reopen the app.
* **🗑️ Delete Requests:** Users can delete their own requests once the transaction is complete.
* **🚫 Demo Contact:** Contact information is revealed in a modal (in a real-world scenario, this would likely be secured or linked to a private chat).

---

## 🚀 How to Use

The application is a single HTML file with embedded CSS (Bootstrap + custom) and JavaScript.

### Prerequisites

You need a modern web browser (Chrome, Firefox, Safari, Edge) that supports **HTML5**, **CSS3**, and **JavaScript ES6+**.

### Getting Started

1.  **Clone the repository (or save the file):**
    ```bash
    git clone https://github.com/moksha2509/swap.html
    ```
2.  **Open the file:** Navigate to the cloned folder and open the `index.html` file directly in your web browser.

### Posting a Request

1.  Fill in the **Amount** (e.g., `500`).
2.  Select what you **Have** (e.g., `Cash`).
3.  Select what you **Need** (e.g., `UPI`). *Note: Have and Need cannot be the same.*
4.  Enter your **Contact Number**.
5.  Add any **Additional Details** (location, time, notes).
6.  Click the **Post Request** button. Your request will immediately appear in the list.

### Fulfilling a Request

1.  Browse or use the search/filter to find a request that matches what you can offer.
2.  Click the **Contact** button on the request card to view the contact details.
3.  Reach out to the poster and arrange the swap!
4.  Once the transaction is complete, use the **Trash** icon to delete the request.

---

## 🛠️ Technology Stack

This project is a classic example of a "Zero-Dependency" client-side application (excluding external CDN libraries).

* **HTML5:** Structure and content.
* **CSS3:** Styling and layout.
* **JavaScript (ES6+):** Application logic, form handling, and data manipulation.
* **Bootstrap 5.3:** Responsive design and UI components.
* **Bootstrap Icons & Font Awesome:** Used for various application icons.
* **Browser Local Storage:** Used as the persistent data store for all exchange requests.

---

## 💡 Pro Tip for Users

> **Safety First:** Always meet in a public, well-lit area on campus (like the library entrance or a busy cafeteria). Always verify the payment (cash count or UPI credit alert) before completing your side of the exchange.

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
