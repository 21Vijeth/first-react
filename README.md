# 🎬 MovieRank — React Movie Listing App

A **React-based** movie ranking and listing web application, showcasing dynamic movie posters, search functionality, and a responsive UI.

![App Banner](./public/hero.png) <!-- You can replace this with a real screenshot -->

## 🚀 Features

* 📊 **Dynamic Movie Display** — Showcases movies with posters and ranking.
* 🔍 **Search Functionality** — Filter/search movies in real-time.
* ⏳ **Loading Spinner** — Custom spinner during data loading.
* ⚛️ **Component-based Architecture** — Built with reusable components like `MovieCard`, `Search`, and `Spinner`.
* 🎨 **Stylish Design** — Clean, modern styling with CSS modules.
* 📱 **Responsive Layout** — Optimized for mobile and desktop devices.

## 🛠 Tech Stack

* **React.js** – UI library
* **Vite** – Development and build tool
* **CSS** – For styling (with `App.css` and component-specific styles)
* **JavaScript ES6** – For logic and interactions

## 📂 Folder Structure

```
first-react/
├── public/              # Static assets (images, icons)
│   ├── hero-bg.png
│   ├── hero.png
│   ├── logo.png
│   └── ...  
├── src/
│   ├── assets/          # Additional SVGs and graphics
│   │   └── react.svg
│   ├── components/      # Reusable UI components
│   │   ├── MovieCard.jsx
│   │   ├── Search.jsx
│   │   ├── Spinner.jsx
│   │   └── App.css
│   ├── App.jsx          # Main App component
│   ├── appwrite.js      # Backend service integration (if used)
│   ├── index.css
│   ├── main.jsx         # React entry point
│   └── .env.local       # Environment configuration
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 📸 Screenshots

| Home View                  | 
| --------------------------  
| ![Home](./public/hero.png) | 

## 🏗️ Setup & Installation

```bash
# Clone the repository
git clone https://github.com/21Vijeth/first-react.git
cd first-react

# Install dependencies
npm install

# Run the development server
npm run dev
```

Visit `http://localhost:5173` in your browser.

## 📈 Future Improvements

* 🔍 **API Integration** — Fetch dynamic data from a real movie API (e.g., TMDB).
* 🌟 **Enhanced Search** — Include genre filters, ratings, and more.
* 🎥 **Trailer Popups** — Show trailers when clicking on a movie card.
* 📈 **Pagination/Infinite Scroll** — Efficient handling of large datasets.

## 🔗 Live Demo

> Coming soon… *(Or replace with your Netlify/Vercel deployment link)*

## 🙋‍♂️ Author

**Vijeth**
GitHub: [@21Vijeth](https://github.com/21Vijeth)

## 📄 License

This project is licensed under the MIT License.
