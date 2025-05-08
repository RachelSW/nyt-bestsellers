# 📚 Choose the Next Chapter

An interactive website that lets users explore current New York Times Bestsellers by genre and discover some personal favorite reads.

## 🔑 Getting Started

This project requires **API keys** for:

### 1. New York Times Books API
- Visit: [https://developer.nytimes.com](https://developer.nytimes.com)
- Sign in or create an account.
- Navigate to **"Apps" > "Create App"**.
- Enable the **Books API**.
- Copy your generated **API Key**.

### 2. Google Books API
- Visit: [https://console.cloud.google.com/](https://console.cloud.google.com/)
- Sign in with your Google account.
- Create a new project (if needed).
- Go to **APIs & Services > Library** and enable the **Books API**.
- Then go to **APIs & Services > Credentials** and generate an **API key**.

> 💡 On page load, the site will prompt you to enter and store these keys using `sessionStorage`.

## 👩‍💻 About the Creator

Built by **Rachel S. Wang**, a lifelong reader and product-minded educator exploring how technology can amplify learning.

## 🚀 Features
- View curated NYT Bestseller lists by genre
- Book cover images fetched dynamically via Google Books API
- Personal reading recommendations section
- Mobile-responsive layout using Bootstrap 5
