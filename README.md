# Personalized Students Recommendation Project

## Project Overview

The **Personalized Students Recommendation Project** aims to analyze and visualize quiz performance data to provide actionable insights and personalized recommendations. By leveraging current and historical quiz data, the project offers a detailed evaluation of user performance and highlights areas for improvement.

---

## Features

- Mistake rate analysis for individual quizzes.
- Visualization of trends in accuracy and scores over time.
- Comparison of performance across topics and difficulty levels.
- Generation of personalized recommendations to improve quiz outcomes.

---

## Data Overview

This project processes data from two sources:

### 1. **Current Quiz Data**

This dataset includes the details of a user’s most recent quiz submission, covering questions, topics, and user responses. It is accessed through the following endpoints:

- **Quiz Endpoint**: [https://jsonkeeper.com/b/LLQT](https://jsonkeeper.com/b/LLQT)
- **Quiz Submission Data**: [https://api.jsonserve.com/rJvd7g](https://api.jsonserve.com/rJvd7g)

### 2. **Historical Quiz Data**

This dataset contains performance data from the last 5 quizzes taken by each user. It includes scores and a response map (Key: Question ID, Value: Selected Option ID). The data is fetched from:

- **API Endpoint**: [https://api.jsonserve.com/XgAgFJ](https://api.jsonserve.com/XgAgFJ)

---

## Key Functionalities

### Mistake Analysis

- Compute mistake rates for each quiz.
- Visualize mistake rates using bar charts for both current and historical data.

### Trend Analysis

- Track accuracy and score trends over time.
- Generate trend lines to identify performance patterns.

### Topic-Wise Performance

- Extract quiz topics and calculate topic-specific accuracy.
- Create bar charts to display accuracy for each topic.

### Difficulty-Level Performance

- Extract difficulty levels from quiz data.
- Compare and visualize average scores for different difficulty levels.

### Personalized Recommendations

- Highlight weak areas based on low accuracy scores.
- Identify quizzes with high mistake rates.
- Suggest strategies to improve time management and speed.
- Provide advanced-level recommendations for high-performing users.

---

## Tools and Technologies

The project utilizes the following tools and libraries:

- **Python**: Primary programming language for data processing and visualization.
- **Matplotlib**: For creating static and interactive visualizations.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Requests**: For API calls to fetch data.

---

## Usage Instructions

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/tverma111/Students-Recommendations
   ```

2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook file `AI_Student.ipynb` and run all cells to execute the analysis and generate visualizations.

4. Ensure an active internet connection for fetching data from API endpoints.

---

## Visualizations

The project provides the following visual insights:

- **Mistake Rate Analysis**: Bar charts displaying quiz mistake rates.
- **Score and Accuracy Trends**: Line plots showing performance trends over time.
- **Topic-Wise Performance**: Bar charts visualizing accuracy across different topics.
- **Difficulty-Level Performance**: Bar charts comparing average scores for various difficulty levels.
- **Trend Analysis**: Line graphs depicting changes in scores and accuracy over multiple quiz attempts.

---

## Data Sources

- **Quiz Endpoint**: [https://jsonkeeper.com/b/LLQT](https://jsonkeeper.com/b/LLQT)
- **Quiz Submission Data**: [https://api.jsonserve.com/rJvd7g](https://api.jsonserve.com/rJvd7g)
- **Historical Quiz Data**: [https://api.jsonserve.com/XgAgFJ](https://api.jsonserve.com/XgAgFJ)

---

## Contributing

Contributions to enhance or extend the functionality of this project are welcome. Fork the repository, make your changes, and submit a pull request for review.

---

## Acknowledgments

Special thanks to [JsonKeeper](https://jsonkeeper.com) and [JsonServe](https://jsonserve.com) for hosting the data used in this project.

---

## Contact

For questions or suggestions, reach out to **Tarika Verma**.
