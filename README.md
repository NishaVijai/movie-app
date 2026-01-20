# Movie App 🎬

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-Deployed-success)

---

## 📄 Description

**Movie App** is a **simple movie search web application** powered by the **OMDb API**.  
Users can search for movies and view detailed information including title, year, IMDb rating, language, and plot — all within a clean, user-friendly interface. :contentReference[oaicite:1]{index=1}

This project demonstrates how to consume a third-party API, manage API data, and display results dynamically in the browser using modern front-end techniques.

---

## 📋 Table of Contents

* [Preview](#preview)
* [Screenshot](#screenshot)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Deployment](#deployment)
* [License](#license)

---

## Preview
https://movie-details-api-search.netlify.app/

---

## Screenshot
<img width="3840" height="4470" alt="OpenMovie Search Web App" src="https://github.com/user-attachments/assets/0a8206ef-5575-4cf2-8bf4-fcab37f20311" />

---

## Features

* 🎥 **Movie Search** — Search movies by title and see results instantly.
* ℹ️ **Movie Details** — View rich movie information including rating, year, plot, language, and more.
* 🔍 **API Integration** — Powered by the **OMDb API**.
* 📱 **Responsive UI** — Works across mobile and desktop screens.
* 🚀 **Hosted on Netlify** — Continuous deployment from GitHub. :contentReference[oaicite:3]{index=3}

---

## Technologies Used

* **JavaScript** – Core scripting
* **HTML5** – Semantic markup
* **CSS3** – Styling and layout
* **OMDb API** – Movie data source
* **Netlify** – Hosting & CI/CD

---

## Installation

To run this app locally:

### 1️⃣ Clone the repository

```bash
git clone <repository-url>
cd movie-app
````

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Start the local server

```bash
npm start
```

### 4️⃣ Open in your browser

```text
http://localhost:3000
```

---

## Usage

1. Enter a movie title in the search field.
2. Press **Search** or hit **Enter**.
3. Browse results and click any movie to view full details.

---

## Project Structure

```
movie-app/
│
├── public/                 # Public assets
├── src/                    # Application scripts & components
│   ├── createMovieListComponent.js
│   ├── createMovieDetailsComponent.js
│   └── main.js
│
├── .gitignore
├── index.html
├── package.json            # Dependencies & scripts
├── style.css               # Visual styles
└── README.md               # Project documentation
```

---

## Deployment

This project is deployed on **Netlify** with GitHub continuous deployment configured.

When you push changes to the `main` branch:

```bash
git add .
git commit -m "Update app"
git push origin main
```

Netlify will automatically rebuild and redeploy the latest version of the site. ([GitHub][1])

---

## License

This project is **open source** and free to use for personal or educational purposes.
