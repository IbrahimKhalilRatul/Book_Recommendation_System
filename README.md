# Book_Recommendation_System

This project is a Book Recommendation System that uses content-based filtering to recommend books based on their descriptions, titles, and authors. The system leverages Sentence Transformers to generate embeddings for book descriptions and computes cosine similarity to find similar books. The project is implemented in Python and uses popular libraries like pandas, scikit-learn, and sentence-transformers.

**Introduction:**

This project aims to build a book recommendation system that suggests books to users based on the content of the books they have read or are interested in. The system uses Sentence Transformers to generate embeddings for book descriptions and then computes cosine similarity between these embeddings to find similar books.
The system is designed to be simple yet effective, making it a great starting point for anyone interested in building recommendation systems or working with natural language processing (NLP).


**Features**

1.Content-Based Filtering: Recommends books based on their descriptions, titles, and authors.

2.Sentence Transformers: Uses pre-trained transformer models to generate embeddings for book descriptions.

3.Cosine Similarity: Computes similarity between books using cosine similarity.

4.Customizable Recommendations: Allows users to specify the number of recommendations they want.

5.Easy to Use: The code is well-documented and easy to run.



**Dataset**


The project uses the Goodreads Dataset, which contains metadata about books, including:

Title: The title of the book.

Authors: The author(s) of the book.

Description: A brief description of the book.

Average Rating: The average rating of the book.

ISBN: The ISBN number of the book.

Language: The language of the book.

Number of Pages: The number of pages in the book.

Ratings Count: The number of ratings the book has received.

Text Reviews Count: The number of text reviews the book has received.

You can download the dataset from Kaggle.


**Installation**

To run this project, you need to install the following Python libraries:

**pip install pandas numpy scikit-learn sentence-transformers**


**Usage**

1. Clone the Repository:

**git clone https://github.com/ibrahimkhalilratul/book-recommendation-system.git**

**cd book-recommendation-system**

2.Download the Dataset

3. Run the Code:

_Open the Jupyter Notebook or Python script._

*Update the file path to the dataset in the code*

***file_path = '/content/drive/MyDrive/archive (S)/books.csv'***

Run the code to generate book recommendations.

4. Get Recommendations:

The system will prompt you to enter a book title.

It will then display the top 5 recommended books based on the content of the book you entered.

**Example Output**

For the book **"The Great Gatsby"**, the system might recommend:

1. A Life in Letters - F. Scott Fitzgerald/Matthew J. Bruccoli
2. Cliffs Notes on Fitzgerald's the Great Gatsby - Kate Maurer/F. Scott Fitzgerald/Cliffshotes
3. Gatsby's Girl - Caroline Preston
4. All the Sad Young Men (Monks of F. Scott Fitzgerald) - F. Scott Fitzgerald/James L.M. West III
5. The Love of the Last Tycoon - F. Scott Fitzgerald


*Feel free to use your own dataset and improve it*
