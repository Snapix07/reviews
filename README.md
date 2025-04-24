# Reviews Component

A simple and responsive React component for displaying user reviews with navigation buttons.

## Features

- Display user profiles with image, name, job title, and review text.
- Navigation: "Next", "Previous", and "Surprise Me" randomizer.
- Smooth UI styling with CSS.
- Fully responsive design.

## Technologies Used

- **React** (Functional Components + Hooks)
- **CSS** (Vanilla styling, no framework)
- **JavaScript** (ES6+)

## Screenshots

![alt text](image.png)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Snapix07/reviews.git
cd reviews-component
```

### 2. Install Dependencies

```bash
npm install 
npm install react-icons --save
```

### 3. Run the App

```bash
npm run dev
```

App will be available at `http://localhost:5173` (if using Vite).

## Folder Structure

```
src/
│
├── App.jsx
├── Review.jsx
├── data.js        # Reviews data
├── index.css
└── main.jsx
```
## How It Works

- Review data is stored in an array (`data.js`).
- Buttons allow users to move through reviews or pick a random one.
- The `useState` hook handles current review index.

## Live Demo

[View Demo on Netlify](https://snapixreviews.netlify.app)

## License

This project is open source and available under the [MIT License](LICENSE).

---

Happy coding!

