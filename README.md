# Movie Recommendation System

This project is a Movie Recommendation System developed in Python, utilizing machine learning techniques to suggest movies based on user preferences. The system is implemented in a Jupyter notebook and employs a dataset of 5000 movies from TMDB (The Movie Database).

## Features

- **Movie Selection**: Users can input a movie name.
- **Recommendations**: The system recommends the three most related movies based on the selected movie.
- **Visual Display**: Each recommendation includes the movie's poster and name.
- **Distance Calculation**: Recommendations are determined using nearest distance calculations between movies.

## Dataset

- **TMDB 5000 Movies Dataset**: The dataset contains 5000 movies and various attributes that were filtered and cleaned to enhance the model's performance.

## Methodology

1. **Data Cleaning**: 
   - Filtered out irrelevant data and handled missing values to create a clean dataset.
   
2. **Model Creation**:
   - Developed a machine learning model to calculate the similarity between movies.
   - Used techniques such as cosine similarity or distance metrics to identify the nearest movies.

3. **User Interface**:
   - Designed a simple UI allowing users to select a movie name.
   - Integrated functionality to display the related movies and their posters.

## Installation & Setup

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries:
  - `pandas`
  - `numpy`
  - `sklearn`
  - `matplotlib`
  - `seaborn`

### Installation Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/MovieRecommendationSystem.git
    ```
2. Navigate to the project directory:
    ```bash
    cd MovieRecommendationSystem
    ```
3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5. Run the notebook file (e.g., `movie_recommendation.ipynb`).

## Technologies Used

- **Python**: Programming language for data processing and model creation.
- **Jupyter Notebook**: Environment for developing and executing the code.
- **Machine Learning**: Algorithms for calculating movie similarity.
- **Flask**: (Optional) Framework for creating a web interface.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions, please reach out via email at `youremail@example.com`.
