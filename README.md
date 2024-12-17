# Book Recommendation System using Neural Network Embeddings

This project implements a book recommendation system using neural network embeddings. The system leverages the principle that books with similar outgoing links on Wikipedia are likely to be similar in content.

## Overview

The system works by:

1. **Data Collection:** Gathering book data and their corresponding Wikipedia links.
2. **Data Preprocessing:** Cleaning and preparing the data for model training.
3. **Embedding Generation:** Training a neural network to learn entity embeddings for books and links.
4. **Similarity Calculation:** Computing cosine similarity between embeddings to identify similar books.
5. **Recommendation Generation:** Recommending books based on similarity scores.

## Methodology

The project utilizes a supervised machine learning approach. A neural network is trained to predict the presence or absence of links within book articles. The resulting embeddings capture the semantic relationships between books and links.

## Usage

1. Clone the repository: `git clone https://github.com/Emmanuel-Rono/Neural-Networks-Recommender-System-`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `jupyter notebook book_recommendation.ipynb`

## Results

The system demonstrates promising results in recommending similar books based on their Wikipedia links. The learned embeddings capture the semantic relationships between books, allowing for effective recommendations.

## Future Work

Potential improvements and extensions include:

* Incorporating external links and infobox information for enhanced recommendations.
* Exploring different neural network architectures and embedding techniques.
* Building an interactive interface for exploring the recommendations.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for any suggestions or improvements.

## License

This project is licensed under the MIT License.

## Acknowledgments

This project was inspired by the work of Will Koehrsen on Wikipedia data science.
