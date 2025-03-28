Fast React Pizza Co. 🍕
This project is a React-based pizza menu application that dynamically displays pizza items, handles sold-out logic, and allows customers to place an order. It was built to solidify fundamental React concepts and practice component-based development.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#build-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

The goal of this project was to:

- Build a dynamic menu of pizzas using React.
- Implement conditional rendering to handle "sold out" pizzas.
- Display dynamic opening and closing hours using JavaScript logic.
- Improve React component reusability.

### Screenshot

![./final screenshot]

### Links

- Live Site URL: [Live site URL ] Add live site URL here
- GitHub Repository: [GitHub Repo](https://github.com/MaddiePst/Pizza-Menu.github.io)

## My Process

### Built With

- React.js (Functional Components)
- CSS Modules
- JavaScript (ES6+)

### What I Learned

<!-- 1. How to Deploy a Web App in React
   I deployed my first React app using Vercel and GitHub Pages.

For GitHub Pages, I added the following to package.json:

json

"homepage": "https://yourusername.github.io/your-repo",
"scripts": {
"predeploy": "npm run build",
"deploy": "gh-pages -d build"
} -->

<!-- Then, I ran:

bash
Copy
Edit
npm install gh-pages --save-dev
npm run deploy 2. Creating and Reusing a Component -->

2. To create reusable components (Pizza) that takes props and dynamically displays pizza details:

![./Component-pizza]

3. Placing JavaScript Logic in Components
   I used JavaScript logic inside the Footer component to determine opening hours dynamically:

   ![./Component-footer]

4. Styling React Apps and Connecting to a CSS File
   I used CSS Modules and imported them into my React components:

import "./index.css";
The styles were organized in index.css, ensuring modular and clean styling.

5. Passing and Receiving Props
   Props were used to pass data between components. For example, the Pizza component received a pizzaObj prop containing all pizza details:

![./Component-use-props]

And inside the Pizza component:
![./Component-pizza]

6. Rendering Lists:
   I dynamically rendered a list of pizzas using .map():
   ![./Component-use-props]

7. Conditional Rendering
   Ternary Operator (? :)

<span>{pizzaObj.soldOut ? "SOLD OUT" : pizzaObj.price}</span>

8. React Fragments
   I used <React.Fragment> to avoid unnecessary <div> wrappers:

root.render(
<React.StrictMode>
<App />
</React.StrictMode>
);

9. Setting Classes and Text Conditionally
   I dynamically applied CSS classes based on props:

<li className={`pizza ${pizzaObj.soldOut ? "sold-out" : ""}`}>
This ensured that sold-out pizzas had a different style.

### Useful Resources

- React Docs - Official documentation.
- MDN JavaScript Guide - JavaScript fundamentals.
- CSS-Tricks - Styling techniques in React.

## Author

- Website: [Madalina Pastiu Portfolio](https://maddiepst.github.io/)
- LinkedIn: [Madalina Pastiu](https://www.linkedin.com/in/madalina-pastiu-52a01396/)
- GitHub: [@maddiepst](https://github.com/MaddiePst)
