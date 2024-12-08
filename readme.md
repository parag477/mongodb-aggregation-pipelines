# MongoDB Aggregation Queries - Backend Intern Task

This repository contains the solutions for the **Backend Intern Task 2**, which requires solving several aggregation pipeline queries for MongoDB. The task involves working with a sample dataset provided by MongoDB Atlas, specifically the `mflix` database, which includes collections like `movies` and `comments`.

## Task Overview

The task consists of solving the following five questions using MongoDB aggregation pipelines:

### 1. **Find Movie Titles with Associated Comments**
   - Join the `movies` collection with the `comments` collection to display each movie's title along with all comments associated with it.

### 2. **Count the Number of Comments for Each Movie**
   - Count the number of comments for each movie and display the movie's title along with the comment count.

### 3. **Find the Top 5 Movies with the Highest IMDb Ratings**
   - Retrieve the top 5 movies with the highest IMDb rating and show the title, IMDb rating, and total number of comments for each movie.

### 4. **List Unique Cast Members and the Number of Movies They Appeared In**
   - Identify unique cast members across all movies and count how many movies each cast member appeared in.

### 5. **Movies Released Before 1950 with IMDb Rating ≥ 7.0**
   - Retrieve movies released before 1950 with an IMDb rating of 7.0 or higher, including their title, release year, genres, IMDb rating, and the first 2 comments.

## Running the Aggregation Queries

1. Open your MongoDB Atlas dashboard.
2. Navigate to **Browse Collections** and select the `mflix` database.
3. Go to the **Aggregation Pipeline Builder** under the `movies` collection.
4. Copy and paste each query from the respective `.json` files into the builder.
5. Run the query to see the results.

## Expected Output
Each query returns results based on the following criteria:
- **Question 1**: Movie titles with their associated comments.
- **Question 2**: The number of comments for each movie.
- **Question 3**: The top 5 movies based on IMDb ratings and the number of comments.
- **Question 4**: The number of movies each unique cast member appeared in.
- **Question 5**: Movies released before 1950 with an IMDb rating of 7.0 or higher, including the first two comments.

## Files in This Repository

- `1.json`: Solution to **Question 1** - Aggregation pipeline to get movie titles and comments.
- `2.json`: Solution to **Question 2** - Aggregation pipeline to count comments per movie.
- `3.json`: Solution to **Question 3** - Aggregation pipeline to find top 5 movies based on IMDb ratings.
- `4.json`: Solution to **Question 4** - Aggregation pipeline to list unique cast members and the number of movies they appeared in.
- `5.json`: Solution to **Question 5** - Aggregation pipeline to find movies before 1950 with IMDb ratings >= 7.0 and their comments.
