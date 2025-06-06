# StarsAlign: A Taylor Swift Lyrics Analysis

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/raksha-rane/stars-align/main?labpath=solution.ipynb)

A computational analysis of Taylor Swift's lyrics, examining temporal references, sentiment patterns, and thematic evolution across her discography from 2006-2022.

## Try it Live! 🚀

Click the "launch binder" button above to run this analysis in your browser! No installation required.

## Project Overview

This project conducts a detailed analysis of Taylor Swift's lyrics using natural language processing and data analysis techniques. Key areas of investigation include:

- Temporal reference analysis (day/night imagery)
- Sentiment analysis across albums
- Word frequency and thematic patterns
- Chronological evolution of lyrical themes

## Prerequisites

To run this analysis, you'll need:

- Python 3.7+
- Jupyter Notebook/Lab
- Required Python packages:
  ```
  pandas
  matplotlib
  seaborn
  nltk
  ```

## Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd stars_align
   ```

2. Install required packages:
   ```bash
   pip install pandas matplotlib seaborn nltk
   ```

3. Download required NLTK data:
   ```python
   import nltk
   nltk.download('vader_lexicon')
   nltk.download('stopwords')
   ```

## Data Sources

The project uses the following datasets:
- `taylor_swift_lyrics_2006-2020_all.csv`: Main lyrics dataset
- `album_year_name.csv`: Album metadata
- Individual album CSV files in the `lyrics/` directory

Original dataset curated by Jan Llenzl Dagohoy and published on [Kaggle](https://www.kaggle.com/datasets/thespacefreak/taylor-swift-song-lyrics-all-albums).

## Project Structure

```
├── solution.ipynb          # Main analysis notebook
├── taylor_swift_dataprep.ipynb   # Data preparation notebook
├── README.md              # This file
├── README.ipynb           # Jupyter version of README
├── album_year_name.csv    # Album metadata
├── taylor_swift_lyrics_2006-2020_all.csv  # Main dataset
└── lyrics/               # Individual album datasets
    ├── 01-taylor_swift.csv
    ├── 02-fearless_taylors_version.csv
    └── ...
```

## Analysis Components

1. **Data Preprocessing**
   - Text cleaning and normalization
   - Temporal reference extraction
   - Album metadata integration

2. **Temporal Analysis**
   - Day/night reference tracking
   - Chronological patterns
   - Album-level temporal distribution

3. **Sentiment Analysis**
   - Overall sentiment trends
   - Temporal reference sentiment
   - Album-by-album sentiment evolution

4. **Word Frequency Analysis**
   - Most common terms
   - Thematic patterns
   - Temporal evolution of vocabulary

## Key Findings

- Significant variation in temporal reference patterns across albums
- Notable dip in time-related imagery around 2017
- Sharp increase in day-related references during 2019-2020
- Overall positive sentiment across the discography
- Distinct sentiment patterns between day and night references

## Usage

1. Open `solution.ipynb` in Jupyter Notebook/Lab
2. Run cells sequentially to reproduce the analysis
3. Modify parameters or extend analyses as needed

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional analyses.

## Acknowledgments

- Jan Llenzl Dagohoy for the original dataset
- The NLTK team for sentiment analysis tools
- Taylor Swift for the amazing music and lyrics

---
*Note: This project is for educational and research purposes only. All lyrics are property of their respective owners.*
