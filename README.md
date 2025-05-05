# 🍳 Frontend Challenge – Breakfast Menu App

Welcome to the Frontend Challenge! Your task is to build a **React** application using **TypeScript** that showcases a **breakfast menu** based on the provided Figma design.

👉 [Figma Design – FE Challenge](https://www.figma.com/design/2KMVvXpInjEwmYOB4cicxG/FE-Challenge?node-id=0-1&p=f&t=HLyhlCq9NXLCipbv-0)

---

## 🧾 Project Overview

Create a beautiful and responsive breakfast menu app with the following key features:

- Menu items displayed in a **carousel**, with a central focus and **blurred side items**.
- Menu data (name, price, icon, category) loaded from a local **JSON file**. Let's imagine is our backend's API returning taht JSON value.
- Filtering by **category**.
- Matching styles and layout based on the **Figma prototype**.

---

## 🧰 Tech Requirements

- **Framework**: React (with Vite or Create React App)
- **Language**: TypeScript
- **Styling**: Tailwind CSS / CSS Modules / Styled Components / Any other choice you want
- **State Management**: You can choose whatever you want
- **Data Source**: Local JSON file. Persistance of data is optional, but will be valued properly.
- **Carousel Blur**: Try to mimic the Figma design.
- **Improvements / Changes**: Feel free to make changes to the app to show your skills.

---

## 📁 JSON Data Structure

Place your menu data in `src/data/menu.json`:

```json
[
  {
    "id": 1,
    "name": "Avocado Toast",
    "price": 8.99,
    "category": "Pastries",
    "icon": "🥑",
    "icon-name": "avocado",
    "image": "avocado-toast.jpg"
  },
  {
    "id": 2,
    "name": "Pancakes",
    "price": 7.49,
    "category": "Pastries",
    "icon": "🥞",
    "icon-name": "pancake",
    "image": "pancakes.jpg"
  }
]
```

---

## 📝 Submission
- Push your code to a public GitHub repository.
- Provide a live demo URL (Netlify, Vercel, etc.). (Optional)
- Submit the link to the repo with instructiosn to run it to use once you have it.
- If you have any questions please reach out to us :).
