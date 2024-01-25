<img src="./Youtube_logo.png" height="90" style='margin: auto;'>

# YouTube Trending Video Analysis Project

## Overview

YouTube, the preeminent video-sharing platform, curates a daily list of trending videos, showcasing content that captures the zeitgeist of global and local cultures. The trending algorithm, as reported by Variety magazine, relies not just on views but also on user interactions, such as shares, comments, and likes. These metrics indicate the videos' virality rather than sheer viewership. Our project conducts a comprehensive analysis of YouTube's trending videos data, aiming to unearth insights into what propels a video to trend, the characteristics of trending content, and the dynamics of user engagement.

## Dataset Description

The dataset is a meticulous aggregation of several months' worth of data on daily trending YouTube videos, specifically tailored for the US region, featuring up to 200 trending videos per day. It includes the following attributes for each video:

- Video ID and Title
- Channel Title
- Publish Time
- Tags
- Views, Likes, Dislikes, Comment Count
- Thumbnail Link
- Comments Disabled Indicator
- Ratings Disabled Indicator
- Video Error or Removed Indicator
- Description

Additionally, the dataset encompasses a `category_id` attribute, correlating to YouTube's video categories. These categories can be decoded using the accompanying JSON files provided for each region included in the dataset.

This enriched dataset is sourced from Kaggle and is a structurally enhanced version of a previous dataset, ensuring better data integrity and ease of analysis.

## Objectives

The project aims to:

- Analyze patterns and trends in video performance across different categories.
- Investigate the correlation between views, likes, comments, and trending duration.
- Understand the impact of various factors on a video's likelihood to trend.
- Visualize data distributions and relationships using advanced graphical techniques.
- Provide insights that can help content creators strategize their content for better engagement and trending potential.

## Tools and Technologies

- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly
- **Statistical Analysis:** SciPy
- **Machine Learning:** scikit-learn (for predictive modeling, if applicable)
- **Database Management:** SQL (for larger datasets or integration with web applications)
- **Version Control:** Git, GitHub
- **Project Management:** JIRA, Trello (if project is managed in a team environment)

## Methodology

The project will follow a structured approach:

1. **Data Cleaning:** Handling missing values, removing duplicates, and ensuring data quality.
2. **Data Exploration:** Understanding the basic statistics of the dataset and exploring each variable individually.
3. **Data Preprocessing:** Preparing data for analysis by encoding categorical variables and normalizing numerical values.
4. **Exploratory Data Analysis (EDA):** Identifying trends, patterns, and anomalies in the data.
5. **In-Depth Analysis:** Performing statistical tests and building models to analyze the impact of different variables on trending potential.
6. **Visualization:** Creating interactive charts and graphs to represent findings effectively.
7. **Insights and Recommendations:** Concluding with actionable insights and strategies for content creators.

## Installation

Instructions for setting up the project environment and installing dependencies.

```sh
# Clone the repository
git clone https://github.com/mendsalbert/Youtube-trending-video-dataset-analysis,git

# Navigate to the project directory
cd Youtube-trending-video-dataset-analysis

# Install required Python packages
pip install -r requirements.txt
```

## Usage

A step-by-step guide on how to run the analysis, including scripts and notebooks.

```sh
# open the Jupyter notebook
jupyter notebook youtube.ipynb
```

## Contributing

We welcome contributions from the community! If you would like to contribute to this project, please follow these guidelines:

1. **Fork the Repository:** Click on the 'Fork' button at the top right corner of this page.
2. **Clone your Fork:** Clone the fork to your local machine.
3. **Create a New Branch:** Create a branch for your edits.
4. **Make Your Changes:** Add or edit the project's code or documentation as needed.
5. **Commit Your Changes:** Commit your changes with a clear commit message.
6. **Push to the Branch:** Push your branch to your fork on GitHub.
7. **Submit a Pull Request:** Open a pull request from your fork to the main repository.

Please make sure your code adheres to the project's coding standards and include appropriate tests as necessary.

## License

This project is open-source and available under the MIT License, which allows for wide usage and contribution.

```
MIT License

Copyright (c) [2024] [Mends Albert]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contact

For any questions or feedback regarding this project, please reach out to:

- Project Maintainer: Mends Albert
- Email: [mendsalbert@gmail.com](mendsalbert@gmail.com)
- LinkedIn: [Mends Albert](https://www.linkedin.com/in/mends-albert/)
- GitHub: [Mends Albert](https://github.com/mendsalbert/)
