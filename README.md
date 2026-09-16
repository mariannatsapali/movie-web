# 🎬 Movie Website

A movie website built with **React** that allows users to browse movies and keep track of their favorite movies.

## ✨ Features

* 🎥 Movie browsing
* ❤️ Favorites functionality
* 🏠 Home page
* ⭐ Favorites page
* 🧭 Navigation with React Router
* ⚛️ Global movie state using React Context
* 🧩 Reusable React components
* 🎨 Custom CSS styling

## 🛠️ Technologies

* **React**
* **React Router**
* **React Context API**
* **JavaScript**
* **CSS**

## 📁 Project Structure

```text
src/
├── components/
│   └── NavBar
├── contexts/
│   └── MovieContext
├── pages/
│   ├── Home
│   └── Favorites
├── css/
│   ├── App.css
│   └── index.css
├── App.jsx
└── main.jsx
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the project

```bash
cd <project-folder>
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

The application will then be available at the local development URL provided by Vite.

## 🧭 Application Routes

| Route        | Page      |
| ------------ | --------- |
| `/`          | Home      |
| `/favorites` | Favorites |

The application uses `BrowserRouter` to handle client-side routing, while `App.jsx` defines the Home and Favorites routes.

## 🧠 State Management

Movie-related state is provided through the custom `MovieProvider`, which wraps the main application. This allows movie state to be shared between different parts of the application.

## 📌 Future Improvements

Some possible improvements for future versions:

* Add movie search
* Add movie genres and filters
* Add movie details pages
* Add ratings and reviews
* Add responsive/mobile improvements
* Add loading and error states
* Add user authentication
* Add dark/light theme support

## 📄 License

This project is available for personal and educational use.
