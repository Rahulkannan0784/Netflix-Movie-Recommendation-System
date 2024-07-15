# Netflix Movie Recommendation System

This project uses the Apriori algorithm to generate movie recommendations based on user viewing patterns.

## Features

- Identify frequent movie pairs watched together.
- Generate association rules for recommendations.
- Analyze user transactions to provide movie suggestions.

## Technologies Used

- Python
- `apyori` library
- Pandas

## Dataset

The dataset consists of user transactions, where each transaction is a list of movies watched by a user.

## Model

The Apriori algorithm parameters:
- `min_support`: 0.003
- `min_confidence`: 0.2
- `min_lift`: 3
- `min_length`: 2
- `max_length`: 2

## Results

The system outputs the top 10 movie pairs with the highest support:

| Movie 1         | Movie 2         | Support |
|-----------------|-----------------|---------|
| Example Movie 1 | Example Movie 2 | 0.005   |
| Example Movie 3 | Example Movie 4 | 0.004   |


