## Overview

This project explores data from the entertainment industry, with a specific focus on the "Golden Age" of television—starting in 1999 with the release of *The Sopranos*. The goal is to investigate the relationship between the number of votes a TV show receives and its rating, under the assumption that highly-rated shows also tend to receive more votes.

## Dataset

- **Source**: `/datasets/movies_and_shows.csv`
- **Contents**: Records of movies and TV shows including ratings and votes.
- **Note**: The dataset's quality is not initially known and must be assessed during the analysis process.

## Project Structure

The notebook is organized into three main stages:

1. **Data Overview**
   - Load and explore the dataset.
   - Understand the structure and potential issues in the data.

2. **Data Preprocessing**
   - Handle missing values, data types, and other quality issues.
   - Focus on cleaning and preparing the dataset for analysis.

3. **Data Analysis**
   - Analyze the correlation between number of votes and ratings.
   - Focus specifically on TV shows released from 1999 onwards.
   - Identify trends and draw conclusions relevant to the "Golden Age" of television.

## Usage

1. Clone this repository or download the `.ipynb` file.
2. Ensure you have Python and Jupyter Notebook installed.
3. Install required packages (e.g., pandas, matplotlib, seaborn).
4. Run the notebook step-by-step to reproduce the analysis.

## Goals

- Understand how user engagement (via votes) correlates with perceived quality (ratings).
- Gain experience in data wrangling, cleaning, and visualization.
- Apply basic Python and data analysis techniques to a real-world dataset.
"""

# Save the content to a README.md file
readme_path = "/mnt/data/README.md"
with open(readme_path, "w", encoding="utf-8") as f:
    f.write(readme_content)

readme_path
