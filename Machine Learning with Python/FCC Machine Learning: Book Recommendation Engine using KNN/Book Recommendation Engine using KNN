# Book Recommendation Engine using KNN

Welcome to the **Book Recommendation Engine using KNN** project! In this challenge, you will build a book recommendation system using the K-Nearest Neighbors (KNN) algorithm, applied to the **Book-Crossings dataset**.

### Project Overview
In this project, you will:
- Use the **Book-Crossings dataset**, which contains ratings of 270,000 books by 90,000 users, to create a book recommendation engine.
- Build the recommendation engine using the **K-Nearest Neighbors (KNN)** algorithm from **scikit-learn**.
- Develop a function, `get_recommends()`, that takes a book title as input and returns a list of 5 similar books along with their distances.

### Dataset Information
- **Book-Crossings Dataset** contains 1.1 million ratings (on a scale of 1-10) for 270,000 books by 90,000 users.
- The dataset is not uniformly rated, with many books having very few ratings. As a result, you will filter out books with less than 100 ratings and users with fewer than 200 ratings to ensure statistical significance.

### Instructions:

1. **Setting up Google Colaboratory Notebook**:
   - Open the provided [Google Colaboratory link](#) and create a copy in your Google Drive or download it for local use.
   - Complete the tasks as described in the notebook, following the instructions provided for each code cell.
   - The notebook will guide you through the process of importing the necessary libraries, cleaning the data, and developing the recommendation algorithm.

2. **Steps**:
   - **Import Libraries**: The first three cells will import the required libraries and data, such as `pandas`, `scikit-learn`, and the dataset itself.
   - **Data Cleaning**: Clean the dataset by removing users with less than 200 ratings and books with fewer than 100 ratings.
   - **KNN Model**: Use `NearestNeighbors` from `sklearn.neighbors` to develop the KNN model. The model will measure the distance between books based on their ratings to identify similar books.
   - **Create the `get_recommends()` Function**:
     - This function takes a book title as input and returns 5 similar books based on their distance from the input book.
     - For example:
       ```python
       get_recommends("The Queen of the Damned (Vampire Chronicles (Paperback))")
       ```
       Should return:
       ```python
       [
         'The Queen of the Damned (Vampire Chronicles (Paperback))',
         [
           ['Catch 22', 0.793983519077301],
           ['The Witching Hour (Lives of the Mayfair Witches)', 0.7448656558990479],
           ['Interview with the Vampire', 0.7345068454742432],
           ['The Tale of the Body Thief (Vampire Chronicles (Paperback))', 0.5376338362693787],
           ['The Vampire Lestat (Vampire Chronicles, Book II)', 0.5178412199020386]
         ]
       ]
       ```
   - **Optional Graphing**: If you want to explore the dataset further, you can plot a graph to visualize the distribution of ratings.

3. **Final Testing**:
   - Once you have implemented the function and trained your model, test the recommendation system by running the final testing cell.
   - The output will verify if the system is recommending books correctly.

### Submission:
- Once you complete the project and pass the test, submit your project by sharing the link to your Google Colaboratory notebook (make sure link sharing is enabled for "anyone with the link").
- If submitting a local copy, ensure the project is hosted on GitHub and provide the link.

