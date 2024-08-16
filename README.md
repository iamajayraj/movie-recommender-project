
---

# 🎬 Movie Recommendation System

Welcome to the **Movie Recommendation System** project! This project leverages data science techniques to build a recommendation engine that suggests movies based on various features like genres, cast, and more. It's hosted as a user-friendly web application using Streamlit.

## 🚀 Project Overview

This project was developed to create a system that recommends movies similar to a user's favorite films. It uses data from the TMDB 5000 Movies dataset, which includes extensive information on movies such as genres, cast, crew, keywords, and more.

### Features:
- **Content-Based Filtering:** Recommends movies based on the content of the movies a user likes.
- **Data Preprocessing:** Extensive preprocessing of movie metadata, including extraction and transformation of genres, keywords, cast, and crew.
- **Streamlit App:** An interactive web app to easily get movie recommendations.

## 📊 Data

The project uses two main datasets:
- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

These datasets are merged and processed to extract relevant features for the recommendation system.

## 🔧 Technologies Used

- **Python:** The core programming language used.
- **Pandas & NumPy:** For data manipulation and analysis.
- **Ast:** To safely evaluate string representations of Python data structures.
- **Streamlit:** To create the web application.

## 🛠️ Setup & Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit App:**
   ```bash
   streamlit run app.py
   ```

## 💻 Usage

Once the app is running, you can input the title of a movie you like, and the system will recommend similar movies based on the metadata. The recommendations are generated using a content-based filtering approach, considering factors such as genres, cast, and crew.

## 📂 Project Structure

- `app.py`: The Streamlit app script.
- `movies.py`: Core Python script with data preprocessing and model logic.
- `datasets/`: Folder containing the movie datasets.
- `README.md`: Project documentation.

## 👨‍💻 Author

- **Your Name** - [GitHub Profile](https://github.com/iamajayraj)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

