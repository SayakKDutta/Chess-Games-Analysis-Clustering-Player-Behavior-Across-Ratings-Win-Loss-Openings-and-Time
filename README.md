# Chess Games Analysis by Clustering Player Behavior across Ratings by Win-Loss Outcome, Openings and Time

This project focuses on analyzing a dataset of chess games using Python's pandas library for data manipulation and visualization, scikit-learn for machine learning tasks like clustering, and Plotly for interactive visualizations. The dataset used in this project contains information about over 20,000 chess games, including various attributes such as game length, opening moves, player ratings, and more.

## Dataset Overview

The dataset used in this project contains the following columns:

- **id**: Unique identifier for each game.
- **rated**: Boolean indicating whether the game was rated.
- **created_at**: Timestamp for when the game was created.
- **last_move_at**: Timestamp for the last move made in the game.
- **turns**: Number of turns in the game.
- **victory_status**: Outcome of the game (e.g., mate, resign, outoftime).
- **winner**: Winner of the game (white, black, or draw).
- **increment_code**: Time control of the game (e.g., 15+2, 5+10).
- **white_id**: ID of the white player.
- **white_rating**: Rating of the white player.
- **black_id**: ID of the black player.
- **black_rating**: Rating of the black player.
- **moves**: Sequence of moves played in the game.
- **opening_eco**: ECO code of the opening.
- **opening_name**: Name of the opening.
- **opening_ply**: Number of ply in the opening.

## Analysis Highlights

- **Exploratory Data Analysis**: Investigate various aspects of the dataset, such as game length, player ratings, victory status, and more.
- **Feature Engineering**: Create new features based on existing attributes, such as average rating, rating floor, captures per ply, etc.
- **Clustering**: Utilize K-Means clustering to group chess games based on their characteristics.
- **Interactive Visualizations**: Use Plotly to create interactive plots for better understanding of the data.

## Acknowledgments
The [DATASET](games.csv) used in this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/datasnaek/chess) and is publicly available.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [sayak.kr.dutta1@gmail.com](mailto:sayak.kr.dutta1@gmail.com).
