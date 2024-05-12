# YouTube Comments Sentiment Analysis

## Overview
This repository contains an analysis of YouTube comments to gauge viewer sentiment, using word clouds to highlight positive and negative feedback, and bar charts to quantify emotional reactions represented by emojis. The project is aimed at helping content creators understand and adapt to their audience's reactions.

### Repository Structure
- `data/`: This directory contains the dataset `UScomments.csv` used in the analysis.
- `scripts/`: Contains the Python scripts and Jupyter Notebook for performing the analysis.
  - `Youtube_Analysis.ipynb`: Jupyter Notebook detailing the analysis process, including the generation of word clouds and sentiment quantification.
  - `youtube_analysis.py`: Python script version of the analysis in the Jupyter Notebook.
- `Insights.docx`: A Microsoft Word document summarizing the insights derived from the YouTube comments analysis.

## Key Insights
- **Positive Sentiment:** Words like "best," "beautiful," "awesome," and "love" are prevalent in the comments, indicating a positive reception.
- **Negative Sentiment:** Contrarily, words like "worst," "boring," and "awful" suggest a significant negative reaction from a portion of the audience.
- **Emoji Analysis:** Emojis such as the 'laughing', 'joy', 'surprise', and 'love' emojis are frequently used, pointing to the emotional engagement of viewers with the content.

## Business Implications
The analysis provides critical feedback for content creators:
- **Content Strategy:** Understanding which aspects are well-received and which are not can guide future content development.
- **Engagement Tactics:** Recognizing the most common emotional reactions helps in crafting responses and interactions that resonate more with the audience.
- **Audience Insight:** The polarized feedback indicates diverse viewer preferences, which can be crucial for segmenting content and targeting communications.

## How to Use This Repository
1. **Data Analysis:**
   - Navigate to the `scripts/` directory to access and run the Jupyter Notebook (`Youtube_Analysis.ipynb`) or the Python script (`youtube_analysis.py`).
2. **Insight Report:**
   - Open the `Insights.docx` for a summary of findings and interpretations of the data.

## Requirements
- Python 3.8+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, wordcloud (Install via `pip install -r requirements.txt`)
