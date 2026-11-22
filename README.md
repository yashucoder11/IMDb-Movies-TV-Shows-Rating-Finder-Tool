# IMDb-Movies-TV-Shows-Rating-Finder-Tool
A lightweight Node.js web tool that instantly searches and retrieves movie and TV show ratings directly from IMDb.


<p align="center">
  <img src="https://raw.githubusercontent.com/yashucoder11/IMDb-Movies-TV-Shows-Rating-Finder-Tool/refs/heads/main/output.png" alt="IMDb Movies & TV Shows Ratings Count Output" width="700">
</p>



## ✨ Features
- 🔍 **Smart Search:** Automatically optimizes queries (e.g., appending "movie" or "series") for accurate IMDb results.
- ⭐ **Instant Ratings:** Extracts and displays the official IMDb rating cleanly.
- 📱 **Responsive UI:** Modern glassmorphism design that works perfectly on both desktop and mobile.
- 🛡️ **Graceful Fallbacks:** Displays "Working on it" if a rating cannot be retrieved, preventing app crashes.

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **Scraping:** Puppeteer (Headless Chrome)
- **Frontend:** HTML5, CSS3, Bootstrap 5, Font Awesome

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR-USERNAME/IMDb-Movies-TV-Shows-Rating-Finder-Tool.git
   cd IMDb-Movies-TV-Shows-Rating-Finder-Tool
   ```

2. **Install dependencies:**
   ```bash
   npm install express puppeteer
   ```

3. **Start the server:**
   ```bash
   node server.js
   ```

4. **Open in your browser:**
   Navigate to `http://localhost:3000`

## ⚠️ Important Note
This tool uses Puppeteer to scrape public IMDb pages. If IMDb changes its website structure or CSS classes, the selectors may need updating. This project is intended for educational purposes.

## 👨‍💻 Developer
**Yashwanth R**  
[Web Development Projects](https://yashwanthwebproject.netlify.app)
