# 🎬 Movie Recommendation System

Welcome to your next favorite way to discover movies! This project is a leap forward in movie discovery, blending sophisticated machine learning with a slick, Netflix-inspired interface. Whether you’re a film buff or a casual viewer, this Movie Recommendation System is designed to help you find movies you’ll truly love.

---

## 🌟 Highlights

### 🚀 Experience the Magic
- **Intelligent Search**: Instantly find movies—even with typos or incomplete titles—using advanced fuzzy matching.
- **Personalized Picks**: Enjoy recommendations custom-tailored to your tastes, powered by ML-driven content-based filtering (TF-IDF & cosine similarity).
- **Live Suggestions**: Watch the recommendation list update in real time as you type.
- **Watch History**: Effortlessly track what you’ve watched and revisit your favorites.
- **Interactive Dashboard**: Navigate a modern, responsive UI with rich visual feedback.

### 💡 User-Focused Features
- **Responsive Design**: Seamlessly optimized for desktop, tablet, and mobile.
- **Dark Mode**: Eye-friendly and stylish, with smooth transitions and subtle animations.
- **Profile Insights**: Dive into your viewing stats and manage your preferences.
- **Cast & Crew Details**: Explore movie cast, see biographies, and discover more titles by your favorite actors.
- **Image Fallbacks**: Missing posters are replaced with graceful placeholders for a consistent look.
- **Audio Touches**: Netflix-style intro sound for immersive ambiance.

### 🛠️ Under the Hood
- **FastAPI & Python**: Swift, modern backend for all logic and APIs.
- **Pandas & NumPy**: Efficient data wrangling and feature engineering.
- **Scikit-learn**: Smart ML algorithms for powering recommendations.
- **FuzzyWuzzy**: Lightning-fast fuzzy search.
- **RESTful APIs**: Clean endpoints for every movie operation.
- **CORS & Static Asset Serving**: Flexible deployment supporting modern frontend frameworks.
- **Robust Error Handling**: Friendly messages for a smooth user journey.

---

## 🖥️ Demo

Curious? [See the system in action on LinkedIn]
https://www.linkedin.com/posts/naveen-gupta-a446a9352_machinelearning-nlp-recommendationengine-activity-7355111540800323585-hTZU?utm_source=share&utm_medium=member_android&rcm=ACoAAFgGFJQBVrgaCuhjQrYIFgykubCug0id3RQ 

---

## 🧰 Technology Stack

### Backend
- **FastAPI** | **Python** | **Pandas** | **NumPy** | **Scikit-learn** | **FuzzyWuzzy**

### Frontend
- **HTML5** | **CSS3** (with animations) | **JavaScript (ES6+)** | **Fetch API**

### Machine Learning
- **TF-IDF Vectorization**
- **Cosine Similarity**
- **Content-Based Filtering**

### External APIs
- **OMDb API** for movie metadata and posters
- **Custom Movie Database** for genres, cast, and directors

---

## 🧠 How It Works

1. **Preprocessing**: Cleans and enriches movie data.
2. **Feature Engineering**: Combines genres, keywords, cast, and director info into feature-rich profiles.
3. **Vectorization**: Converts features into numerical vectors for efficient comparison.
4. **Similarity Calculation**: Measures likeness between movies.
5. **Recommendation Engine**: Suggests the top picks personalized to your input.

**User Flow:**
- Enter a favorite movie.
- The system finds the closest match (even with typos).
- The ML engine recommends similar movies.
- Browse results, explore casts, and manage your watch history.

---

## 🏁 Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation

```bash
pip install fastapi uvicorn pandas numpy scikit-learn requests fuzzywuzzy python-Levenshtein
```

### Run the App

```bash
python -m uvicorn backend:app --reload
```
Open your browser and explore the dashboard
---

## 🎨 Design & UX

- **Netflix-Inspired Theme**: Dark backgrounds, bold red accents, and modern flair.
- **Smooth Animations**: Fade-ins, slide-ups, and hover effects.
- **Responsive Grid**: Adaptive layouts for movie cards.
- **Typewriter Titles**: Dramatic animated headings.
- **Interactive Elements**: Engaging transitions, modals, and feedback.
- **Professional Touches**: Polished loading states and error messages.

---

## 🔮 Roadmap & Future Plans

- **User Authentication**: Secure login/signup.
- **Persistent Watch History**: Store user data in a database.

---

## 📈 Performance

- **Lightning Fast**: Optimized algorithms for real-time results.
- **Efficient Data Handling**: Vectorized operations for speed at scale.
- **In-Memory Caching**: Blazing fast responses, even with large datasets.
- **Scalable**: Ready for cloud deployment and heavy traffic.

---

## 🤝 Contributing

Have ideas or found a bug? Contributions are always welcome—just open an issue or submit a pull request!

- [Open an issue](https://github.com/ng49-rgb/movie-recommendation-system/issues)
- [Submit a pull request](https://github.com/ng49-rgb/movie-recommendation-system/pulls)

---

## 📄 License

MIT License. See the [LICENSE](LICENSE) file for full details.

---

## 👨‍💻 Author

**Naveen**  
- GitHub: [ng49-rgb](https://github.com/ng49-rgb)  
- Email: naveengupta0378@gmail.com  
- Medium: [@ng251370](https://medium.com/@ng251370)

---

## 🙏 Thanks & Credits

- Movie data from public datasets.
- OMDb API for metadata and posters.
- Netflix for design inspiration.
- The open source community for incredible tools and libraries.

---

⭐ **If you love this project, star the repo and spread the word!**

*Built with ❤️ and plenty of ☕*
