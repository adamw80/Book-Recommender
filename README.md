# Book Recommender System

## Overview
This project develops a personalized book recommendation system using data from Goodreads. By analyzing user ratings, review counts, and book metadata, the system suggests books that are similar to a given input. It leverages exploratory data analysis (EDA) and similarity-based recommendation techniques to provide tailored suggestions.

## Dataset
The dataset contains the following key features:
- **bookID:** Unique identifier for each book.
- **title:** Title of the book.
- **authors:** Author(s) of the book.
- **average_rating:** Average rating given by users.
- **ISBN/ISBN13:** Book identifiers used globally.
- **language_code:** Language in which the book is published.
- **num_pages:** Number of pages in the book.
- **ratings_count:** Number of ratings submitted by users.
- **text_reviews_count:** Number of written reviews submitted.

## Key Objectives
1. Perform EDA to understand trends and distributions within the book data.
2. Implement a weighted rating algorithm to rank books.
3. Develop a recommendation system using similarity measures to suggest related books.

## Project Structure
```
.
├── README.md                 # Documentation file
├── Book_Recommendation.ipynb # Main analysis and recommendation engine
├── data/                     # Input dataset containing book details
├── results/                  # Outputs such as recommended book lists
└── models/                   # Any saved models used in the recommendation process
```

## Key Features
- **Exploratory Data Analysis:** Visualizes ratings, reviews, and author distributions.
- **Weighted Rating Algorithm:** Improves recommendation quality by balancing ratings and review counts.
- **Recommendation Engine:** Suggests books similar to a given input based on user-defined criteria.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/book-recommender.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and execute the `Book_Recommendation.ipynb` notebook in a Jupyter environment to explore the data and generate recommendations.

## Results
- Personalized book recommendations based on user inputs.
- Visualizations of key data insights.
- Ranked lists of books based on weighted rating and similarity.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, feel free to reach out:
- **Email:** Adam.RivardWalter@gmail.com  
- **GitHub:** [adamw80](https://github.com/adamw80)
