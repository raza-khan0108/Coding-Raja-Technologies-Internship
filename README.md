# Coding-Raja-Technologies-Internship

# Movie Recommendation System

This project is a movie recommendation system built using collaborative filtering techniques to suggest movies to users based on their preferences.

## Tech Stack
- Python
- pandas
- surprise
- Flask

## Steps to Run the Project

1. *Clone the repository:*
    bash
    git clone https://github.com/d3005/coding_raja_Task_01.git
    cd coding_raja_Task_01
    

2. *Install dependencies:*
    bash
    pip install -r requirements.txt
    

3. *Download and place the dataset:*
    - Download the MovieLens Latest Small dataset from [here](https://files.grouplens.org/datasets/movielens/ml-latest-small.zip).
    - Extract it and place the movies.csv and ratings.csv files in the data/ directory.

4. *Run the Flask app:*
    bash
    python src/app.py
    

5. *Access the web interface:*
    Open your browser and go to http://127.0.0.1:5000.

## Project Structure

- *data/*: Contains the movie ratings data.
- *notebooks/*: Jupyter notebooks for data preprocessing, exploratory data analysis, and collaborative filtering.
- *src/*: Source code for the Flask application and recommendation system.
- *templates/*: HTML templates for the web interface.
- *static/*: Static files (CSS) for the web interface.
- *requirements.txt*: List of dependencies.
- *README.md*: Project documentation.

## Usage

- Run the Flask app and open the web interface.
- Input your preferences to receive movie recommendations.

## Contributing

Feel free to open issues or submit pull requests for any improvements or bug fixes.
