# Text Data Wrangling & Pre-processing Project
In project, me and my groupmate focused on extracting, cleaning, and transforming semi-structured text data into structured formats suitable for downstream NLP tasks. It involved multiple stages of data wrangling, regular expression–based parsing, and text pre-processing for feature engineering.
## Key Contributions:

### Parsing Raw Text (Task 1):

- Extracted trademark assignment records from semi-structured text files using Python (re, json, pandas).

- Designed and applied regular expressions to capture complex attributes (e.g., reel/frame numbers, assignors/assignees, legal entity descriptions).

- Normalised date formats (YYYY-MM-DD) and handled missing/ambiguous values through systematic assumptions.

- Converted the processed data into structured JSON output following strict schema requirements.
Complete report from the task progress: https://github.com/huypa/Portfolio-Data-Wrangling/blob/main/021_ass1/task1_021.pdf
<img width="820" height="311" alt="Screenshot 2025-09-30 at 11 05 53" src="https://github.com/user-attachments/assets/48d1e7cd-7e44-4cd3-ae60-5d6ecf9742a2" />


### Text Pre-processing (Task 2):

- Imported and combined YouTube comments across multiple worksheets in Excel, ensuring removal of duplicates.

- Extracted and cleaned the textOriginal field: handled emoji removal, lower-casing, and language detection (using langdetect).

- Constructed a vocabulary of unigrams and bigrams via tokenisation, stemming (Porter Stemmer), and filtering by frequency thresholds.

- Generated sparse numerical representations (count vectors) for each channel to prepare for NLP and machine learning applications.

- Produced deliverables including channel comment statistics (.csv), vocabulary lists (.txt), and sparse representations (.txt).

### Skills & Tools Used:

- Python (Regex, Pandas, JSON, NLTK, Langdetect)

- Text Wrangling & Cleaning (emoji removal, stemming, stopword filtering)

- Feature Engineering (unigrams, bigrams, count vectors)

- Data Transformation (JSON structuring, CSV exports)

- Collaborative Workflow (Colab, Git version history, documentation)

### Outcome:
Successfully transformed raw, noisy, semi-structured text into clean, structured datasets ready for NLP modelling, recommender systems, and information retrieval tasks. This project strengthened my ability to handle end-to-end text preprocessing pipelines — from parsing raw data to generating numerical representations for machine learning.
