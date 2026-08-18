# 🎬 Movie Recommendation System

A machine learning-based Movie Recommendation System that recommends similar movies based on a user's movie selection.

The project combines a recommendation model with a Django web application, allowing users to search for a movie and receive relevant movie recommendations through an interactive web interface.

---

## 📌 Project Overview

Recommendation systems are widely used by platforms such as Netflix, Amazon Prime Video, and other streaming services to help users discover relevant content.

This project demonstrates how a movie recommendation model can be integrated into a complete web application.

The user searches for a movie, the recommendation engine processes the selected movie, and the application returns similar movie recommendations.

---

## 🚀 Features

- Movie search functionality
- Auto-suggestion while searching
- Similar movie recommendations
- Machine learning-based recommendation engine
- Django backend
- Interactive web interface
- HTML, CSS, and JavaScript frontend
- Model training notebook
- Local deployment support
- Recommendation model integration

---

## 🏗️ System Architecture

```text
User
  │
  ▼
Movie Search
  │
  ▼
Django Web Application
  │
  ▼
Recommendation Engine
  │
  ▼
Movie Dataset
  │
  ▼
Similarity / Recommendation Model
  │
  ▼
Recommended Movies
  │
  ▼
Web Interface
```

---

## 🧠 How It Works

The user enters a movie name into the search interface.

```text
User searches for a movie
        ↓
Application identifies the movie
        ↓
Recommendation model processes the selection
        ↓
Similar movies are identified
        ↓
Recommendations are returned
        ↓
Results are displayed to the user
```

The system currently contains approximately the top 2,500 movies based on IMDb data.

---

## 🛠️ Technology Stack

### Backend

- Python
- Django

### Machine Learning / Data

- Pandas
- PyArrow
- Recommendation model
- Parquet-based model/data storage

### Frontend

- HTML
- CSS
- JavaScript
- Bootstrap
- jQuery

### Development

- Jupyter Notebook
- Git
- GitHub

---

## 📂 Project Structure

```text
Movie Recommendation-System/
│
├── movie_recommendation/
│   └── Django project configuration
│
├── recommender/
│   └── Recommendation application
│
├── static/
│   └── Application assets and model data
│
├── readme_images/
│   └── README screenshots
│
├── Movie_Recommendation_System_Complete_Guide.ipynb
│
├── manage.py
├── requirements.txt
├── build.sh
├── db.sqlite3
└── README.md
```

---

## 🔍 User Workflow

The application provides a simple recommendation workflow.

### Step 1

Open the Movie Recommendation System.

### Step 2

Search for a movie using the search bar.

For example:

```text
The Dark Knight
```

### Step 3

Select the desired movie from the search suggestions.

### Step 4

The recommendation engine analyzes the selected movie.

### Step 5

The application displays similar movie recommendations.

---

## 💻 Running the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/hemu3553/Movie-Recommendation-System.git
```

Move into the project directory.

```bash
cd Movie-Recommendation-System
```

Then enter the Django application directory if required:

```bash
cd "Movie Recommendation-System"
```

---

### 2. Create a Virtual Environment

```bash
python3 -m venv venv
```

Activate it on macOS/Linux:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Run the Django Application

```bash
python manage.py runserver
```

The development server will normally start at:

```text
http://127.0.0.1:8000
```

Open that address in your browser.

---

## 🤖 Model Training

The repository contains a Jupyter Notebook:

```text
Movie_Recommendation_System_Complete_Guide.ipynb
```

The notebook contains the workflow used for model training and inference.

It can also be used to experiment with different recommendation datasets or models.

---

## 🔄 Using a Different Recommendation Model

The project is structured so that another compatible recommendation model can be integrated.

The main recommendation logic is located in:

```text
recommender/views.py
```

The dataset/model files are loaded from the `static` directory.

This allows the recommendation engine to be updated without rebuilding the complete Django application.

---

## 🎯 Example

```text
Input:

Movie → The Dark Knight

        ↓

Recommendation Engine

        ↓

Output:

Similar / related movie recommendations
```

The recommendations are then displayed through the Django web interface.

---

## 📊 Project Goal

The goal of this project is to demonstrate an end-to-end recommendation system rather than only a machine learning notebook.

It combines:

```text
Data
   ↓
Recommendation Logic
   ↓
Model/Data Storage
   ↓
Django Backend
   ↓
Web Interface
   ↓
User Recommendations
```

This demonstrates how a recommendation model can be integrated into a usable web application.

---

## 🔮 Future Improvements

Possible improvements include:

- Larger and more recent movie datasets
- Personalized recommendations based on user history
- User authentication
- Movie ratings
- Collaborative filtering
- Hybrid recommendation models
- Movie poster and metadata API integration
- Recommendation feedback
- Docker containerization
- REST API for recommendations
- Cloud deployment
- Model monitoring

---

## ⚠️ Current Limitations

The current system uses a limited movie database containing approximately the top 2,500 IMDb movies.

Recommendations are therefore limited to movies available in the application's dataset.

---

## 👨‍💻 Author

**Hemanth MORE**

GitHub: `hemu3553`

---

## ⭐ About This Project

This project demonstrates practical experience with:

- Python
- Machine Learning
- Recommendation Systems
- Django
- Data Processing
- Model Integration
- Web Application Development
- End-to-End ML Application Design
