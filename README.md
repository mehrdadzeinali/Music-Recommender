# Music Recommender System

## Description

This project implements a music recommendation system. The system clusters songs based on their features and recommends similar songs to those provided by the user.

## Features

- **Data Preprocessing**: Load and preprocess song data.
- **Clustering**: Group similar songs into clusters using K-Means.
- **Dimensionality Reduction**: Use PCA to visualize clusters in 2D.
- **Recommendation**: Recommend songs similar to those provided by the user.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/music-recommender.git
    cd music-recommender
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install notebook
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter Notebook:
    ```sh
    jupyter notebook music_recommender.ipynb
    ```

2. Follow the steps in the notebook to load data, cluster songs, visualize clusters, and generate recommendations.

## Example

Here's an example of how to use the recommendation function in the notebook:

```python
user_songs = [
    {'name': 'Come As You Are', 'year': 1991},
    {'name': 'Smells Like Teen Spirit', 'year': 1991},
    {'name': 'Lithium', 'year': 1992},
    {'name': 'All Apologies', 'year': 1993},
    {'name': 'Stay Away', 'year': 1993}
]
```
