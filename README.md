# Movie-Recommendation-System

# 🎬 MovieNest – Personalized Movie Recommendation System

## 🌐 Live Project  
🔗 [Click Here to Explore MovieNest](https://priyam-movie-recommendation-system.streamlit.app/)  
*(Opens the live deployed version built with Streamlit)*

## 📌 Overview  
**MovieNest** is a content-based movie recommendation system that helps users discover movies based on **genres, actors, directors, and movie metadata**.  
It also displays **posters, IMDb ratings, plots, and allows users to rate movies**.  
Built using **Python, Streamlit, Pandas, and the OMDb API**.

---

## ✨ Features

✅ Home page with custom logo and UI  
✅ Recommend movies by Genre, Actor, Director  
✅ Shows IMDb Rating, Poster & Plot (via OMDb API)  
✅ Clickable posters → opens IMDb page  
✅ User can rate any movie (UI-based rating)  
✅ Clean and modern interface (HTML + CSS inside Streamlit)  
✅ Dataset preprocessed with IMDb links  

---

## 🧠 How It Works (Short)

1. Loads the movie dataset (`movies_data.csv`)  and the modified dataset (`movies_data_with_imdb_links.csv`)
2. Extracts genres, actors, directors for filtering  
3. When user selects a filter, matching movies are shown  
4. For each movie → Poster, Rating, Plot fetched using OMDb API  
5. UI updates in real time using Streamlit

---

## 🗂️ Dataset Details

Contains columns:

- `Name`
- `Year`
- `Genre`
- `Actor 1`, `Actor 2`, `Actor 3`
- `Director`
- `IMDb_Link`

Missing values handled, genre column split and expanded for filtering.
