# Goyral Google Map Extractor 🌍

**Goyral Google Map Extractor** is a powerful Chrome Extension that allows users to extract business data directly from Google Maps. It's built using standard web technologies including **HTML**, **CSS**, **JavaScript**, and a **Web Worker** architecture, offering a fast and seamless data scraping experience.

---

## 🧰 Features

- 📍 Extract business name, address, phone number, website, and more.
- 🚀 Works directly from Google Maps UI.
- 🧠 Background data scraping using `worker.js` for smooth performance.
- 💾 Export data to CSV/Excel (optional feature depending on version).
- 🎯 Simple and user-friendly interface.
- 🔐 No server-side code – works entirely in your browser.
- 🛠️ Built using Manifest V3 for improved performance and security.

---

## 📁 Project Structure

Goyral-Google-Map-Extractor/
│
├── css/                # Stylesheets for the extension UI  
├── html/               # HTML popup or UI components  
├── images/             # Icons and image assets  
├── js/                 # Main JavaScript logic  
├── manifest.json       # Chrome Extension manifest (V3)  
├── worker.js           # Background data extraction logic  

---

## 📦 Installation (Developer Mode)

1. Download or clone this repository.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** (top-right).
4. Click **"Load unpacked"** and select the project directory.
5. The Goyral Map Extractor extension will now be available in your Chrome toolbar.

---

## 🔍 How to Use

1. Navigate to [Google Maps](https://maps.google.com).
2. Search for a business type or location (e.g., "restaurants in New York").
3. Click on the extension icon from your Chrome toolbar.
4. Start extraction – the tool will automatically scrape visible results.
5. (Optional) Export the data to CSV.

> Note: The extension only extracts data visible in the current scroll of search results. Use scroll/load more to extract more entries.

---

## ⚠️ Disclaimer

This extension is intended for **personal or educational use only**. Scraping data from Google Maps may violate Google’s Terms of Service. The author is not responsible for any misuse or legal consequences.

---

## 🧾 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

Developed by [@princemehta-git](https://github.com/princemehta-git)

