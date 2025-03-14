# Lite-Tube  

Lite-Tube is a web application built with **HTML**, **Tailwind CSS**, **DaisyUI**, and **JavaScript** that allows users to browse video content by category and search for specific videos. It fetches data dynamically from an external API and displays the results in an organized and responsive UI.

---

## 🚀 Features  

- **Dynamic Category Fetching** – Categories are loaded from an API.  
- **Search Functionality** – Users can search for videos by title.  
- **Video Display** – Videos are shown with thumbnails, author details, and views.  
- **Loading Indicator** – A loader appears while fetching data.  
- **Video Details Modal** – Clicking a video displays additional details in a modal.  

---

## 🛠 Technologies Used  

- **HTML** – Structure of the application.  
- **Tailwind CSS** – Utility-first CSS framework for styling.  
- **DaisyUI** – Tailwind-based UI component library for better design.  
- **JavaScript (ES6)** – Fetch API, DOM manipulation, and event handling.  

---

## 📂 Project Structure  

Lite-Tube/ │-- assets/ # Logo and icons
│-- script/ # JavaScript files
│ ├── script.js # Main script file
│-- index.html # Main HTML file
│-- README.md # Documentation


---

## 📦 Installation  

1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/AN-Tube.git

## 📜 Usage
1. The homepage displays all categories at the top.
2. Click on a category to filter videos.
3. Use the search bar to find specific videos.
4. Click on a video to view more details.

## 🔗 API Endpoints
### Categories:
GET https://openapi.programming-hero.com/api/phero-tube/categories

### Videos:
GET https://openapi.programming-hero.com/api/phero-tube/videos?title={searchText}

### Category Videos:
GET https://openapi.programming-hero.com/api/phero-tube/category/{id}

### Video Details:
GET https://openapi.programming-hero.com/api/phero-tube/video/{videoId}


## 💡 Future Improvements
1. Add pagination for large video lists.
2. Implement a dark mode toggle.
3. Improve search functionality with filters.

# Made with by Amirun Nahar








