<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Recommendation System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1 {
            color: #2c3e50;
        }
        h2 {
            color: #34495e;
        }
        ul, ol {
            margin: 10px 0 20px 20px;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 4px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
        a {
            color: #3498db;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>🎬 Movie Recommendation System</h1>
    <p>Welcome to the <strong>Movie Recommendation System</strong> project! This project leverages data science techniques to build a recommendation engine that suggests movies based on various features like genres, cast, and more. It's hosted as a user-friendly web application using Streamlit.</p>
    
    <h2>🚀 Project Overview</h2>
    <p>This project was developed to create a system that recommends movies similar to a user's favorite films. It uses data from the TMDB 5000 Movies dataset, which includes extensive information on movies such as genres, cast, crew, keywords, and more.</p>
    
    <h3>Features:</h3>
    <ul>
        <li><strong>Content-Based Filtering:</strong> Recommends movies based on the content of the movies a user likes.</li>
        <li><strong>Data Preprocessing:</strong> Extensive preprocessing of movie metadata, including extraction and transformation of genres, keywords, cast, and crew.</li>
        <li><strong>Streamlit App:</strong> An interactive web app to easily get movie recommendations.</li>
    </ul>
    
    <h2>📊 Data</h2>
    <p>The project uses two main datasets:</p>
    <ul>
        <li><code>tmdb_5000_movies.csv</code></li>
        <li><code>tmdb_5000_credits.csv</code></li>
    </ul>
    <p>These datasets are merged and processed to extract relevant features for the recommendation system.</p>
    
    <h2>🔧 Technologies Used</h2>
    <ul>
        <li><strong>Python:</strong> The core programming language used.</li>
        <li><strong>Pandas &amp; NumPy:</strong> For data manipulation and analysis.</li>
        <li><strong>Ast:</strong> To safely evaluate string representations of Python data structures.</li>
        <li><strong>Streamlit:</strong> To create the web application.</li>
    </ul>
    
    <h2>🛠️ Setup & Installation</h2>
    <ol>
        <li><strong>Clone the Repository:</strong>
            <pre><code>git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system</code></pre>
        </li>
        <li><strong>Install Dependencies:</strong>
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li><strong>Run the Streamlit App:</strong>
            <pre><code>streamlit run app.py</code></pre>
        </li>
    </ol>
    
    <h2>💻 Usage</h2>
    <p>Once the app is running, you can input the title of a movie you like, and the system will recommend similar movies based on the metadata. The recommendations are generated using a content-based filtering approach, considering factors such as genres, cast, and crew.</p>
    
    <h2>📂 Project Structure</h2>
    <ul>
        <li><code>app.py</code>: The Streamlit app script.</li>
        <li><code>movies.py</code>: Core Python script with data preprocessing and model logic.</li>
        <li><code>datasets/</code>: Folder containing the movie datasets.</li>
        <li><code>README.md</code>: Project documentation.</li>
    </ul>
    
    <h2>👨‍💻 Author</h2>
    <p><strong>Your Name</strong> - <a href="https://github.com/iamajayraj">GitHub Profile</a></p>
    
    <h2>📄 License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>
