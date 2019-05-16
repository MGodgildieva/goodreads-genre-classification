# goodreads-genre-classification

The goal of this project is to build a ML model that would be able to predict book genres by book cover and description. This is a case of multilabel classification task as each book can have a different number of tags.


## Authors

*  **Mariia Godgildieva** - [MGodgildieva](https://github.com/MGodgildieva)
*  **Anastasiia Shalygina** - [ShalyginaA](https://github.com/ShalyginaA)


## Data

Kaggle dataset ["Goodreads’ Best Books Ever"](https://www.kaggle.com/meetnaren/goodreads-best-books)

Dataset contains information on around 50K of books from Goodreads, a social cataloging website with a large database of books with reviews and ratings. The data were scraped for the books with highest ratings.

## Main Idea

To build separate models for genre prediction based on book description and book cover and combine results using stacking.
