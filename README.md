# Music Genre Classification Project

Welcome to the Music Genre Classification project repository! This project aims to classify music genres using various machine learning models based on audio features extracted from `.wav` format files. The repository contains the code, data, and results of our efforts to accurately predict the genre of music tracks.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Results](#results)
- [Practical Applications](#practical-applications)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [License](#license)

## Introduction

The Music Genre Classification project focuses on classifying music tracks into different genres using machine learning techniques. By analyzing audio features extracted from `.wav` files, we developed and evaluated multiple models to determine the best approach for accurate genre prediction.

## Usage

To classify a music track's genre, you can upload a `.wav` format file to our trained models. The models will analyze the audio features and predict the most likely genre of the music. We recommend following the steps outlined in the [Getting Started](#getting-started) section to set up the necessary environment and dependencies.

## Results

Our investigation revealed that the Support Vector Machine (SVM) and Random Forest Classifier algorithms outperformed the K-Nearest Neighbors (KNN) algorithm in music genre classification. Specifically, the Random Forest Classifier achieved the highest accuracy of 73.2%. More details about our experimentation and results can be found in the project's code and documentation.

## Practical Applications

The Music Genre Classification project has practical implications in various domains, including:

- Music Recommendation Systems: Enhance user experience by accurately categorizing music tracks and suggesting similar songs based on genre.
- Automatic Music Tagging: Streamline the process of tagging music tracks with appropriate genres for cataloging and organization.
- Music Streaming Services: Improve playlist generation and content curation by accurately classifying songs to create genre-specific playlists.

## Tech Stack

The project is primarily developed using Python and utilizes a range of machine learning libraries and tools. Key components of our tech stack include:

- Python
- Machine Learning Libraries (scikit-learn, XGBoost, etc.)
- Audio Feature Extraction Libraries
- Jupyter Notebooks

## Getting Started

To get started with the Music Genre Classification project, follow these steps:

1. Clone this repository to your local machine.
2. Set up the Python environment with the required dependencies used.
3. Prepare your `.wav` format music files for testing and prediction.
4. Run the provided code to load the trained models and classify the music tracks.

For detailed instructions and code examples, refer to the project's documentation.

