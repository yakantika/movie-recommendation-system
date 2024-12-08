# movie-recommendation-system

## Overview
This project implements a movie recommendation system using a collaborative filtering approach based on movie similarities. It utilizes a web application built with Streamlit to allow users to select a movie from a dropdown menu and receive a list of recommended movies.

## Features
- Movie selection via a dropdown menu.
- Display of recommended movies based on user selection.

## How It Works
The system uses pre-computed similarity metrics between movies, loaded from a `similarity.pkl` file. When a user selects a movie, the system fetches the top five similar movies and displays their titles.

## Demo
Check out the **demo video** of the Movie Recommendation System in action below:
[![Demo Video](https://drive.google.com/file/d/1KZivPZYWRq_AyI3VBjPLEw4tsLoICZoq/view?usp=sharing)

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
3. Run the Streamlit application:
   ```bash
   streamlit run main.py
