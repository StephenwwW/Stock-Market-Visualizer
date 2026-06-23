
# 2026 H1 Stock Market & Tech Giants Visualizer

<div align="center">
An interactive, frontend-only data visualization tool built with HTML, Tailwind CSS, and Chart.js to track the precise highs, lows, and closing prices of global indices and major tech stocks in the first half of 2026.
</div>

---

### Features

* **Dual Dashboards**: Includes two distinct visualizers—one for Global Major Indices (DJIA, Nasdaq, S&P 500, VIX, etc.) and another for Tech & Semiconductor Giants (Mag 7, TSM, NVDA, SK Hynix, etc.).

* **Precision Extreme Points**: Accurately plots absolute intraday highs and lows. Nodes that represent extreme values (e.g., "Yearly High" or "Yearly Low") are dynamically enlarged for immediate visual impact.

* **Smart Interactive Tooltips**: Hovering over data points reveals comprehensive details, including the exact peak/trough price, extreme point labels, and the actual monthly closing price.

* **Multi-Currency & Asset Support**: Automatically handles and displays local currencies (KRW, JPY) alongside USD equivalents for Asian tech indicators, while accommodating inverse indicators like the VIX.

* **Customizable Legend Toggles**: Features a custom-built, responsive legend that allows users to easily toggle individual datasets on and off to isolate specific market trends and declutter the chart.

* **Sleek Dark UI**: A modern, responsive, dark-themed interface crafted with Tailwind CSS, ensuring optimal readability and a professional financial terminal aesthetic.

* **No Dependencies**: Pure front-end applications contained within single HTML files. No server or build process required.

### User Interface

![Application Demo](images/market.png) 

![Application Demo](images/tech.png) 

### Setup & Installation

**1. Prerequisites**

* A modern web browser (e.g., Chrome, Firefox, Edge, Safari).

**2. Clone the Repository**

```bash
git clone [https://github.com/YourUsername/2026_stock_visualizer.git](https://github.com/YourUsername/2026_stock_visualizer.git)
cd 2026_stock_visualizer

```

**3. Install Dependencies**

No installation is required! These are standalone front-end applications leveraging CDN links for Tailwind CSS and Chart.js.

### How to Use

1. After cloning the repository, simply open the HTML files directly in your web browser:
* Open `2026_Stock Index.html` to view the macroeconomic trends of global stock indices.
* Open `2026_Stock.html` to track specific trajectories of major technology and semiconductor companies.


2. **Hover** over the data points (especially the enlarged nodes) on the chart to read detailed tooltips showing exact intraday prices vs. monthly closing prices.
3. **Click** on any item in the top legend (e.g., "AAPL", "VIX 恐慌指數") to hide or show that specific line, making it easier to compare specific datasets without visual clutter.

### License

This project is released under the [MIT License](https://www.google.com/search?q=LICENSE).
