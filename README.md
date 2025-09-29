# Text Data Wrangling & Pre-processing Project
In project, me and my groupmate focused on extracting, cleaning, and transforming semi-structured text data into structured formats suitable for downstream NLP tasks. It involved multiple stages of data wrangling, regular expression–based parsing, and text pre-processing for feature engineering.
## Key Contributions:

### Parsing Raw Text (Task 1):

- Extracted trademark assignment records from semi-structured text files using Python (re, json, pandas).

- Designed and applied regular expressions to capture complex attributes (e.g., reel/frame numbers, assignors/assignees, legal entity descriptions).

- Normalised date formats (YYYY-MM-DD) and handled missing/ambiguous values through systematic assumptions.

- Converted the processed data into structured JSON output following strict schema requirements.

### Text Pre-processing (Task 2):

- Imported and combined YouTube comments across multiple worksheets in Excel, ensuring removal of duplicates.

- Extracted and cleaned the textOriginal field: handled emoji removal, lower-casing, and language detection (using langdetect).

- Constructed a vocabulary of unigrams and bigrams via tokenisation, stemming (Porter Stemmer), and filtering by frequency thresholds.

- Generated sparse numerical representations (count vectors) for each channel to prepare for NLP and machine learning applications.

- Produced deliverables including channel comment statistics (.csv), vocabulary lists (.txt), and sparse representations (.txt).

### Version Control & Documentation (Task 3):

- Maintained a development history log, documenting incremental progress, changes, and collaborative efforts.

- Ensured reproducibility by providing both Jupyter Notebooks (.ipynb) with printed outputs and Python scripts (.py) for plagiarism checking.

### Skills & Tools Used:

- Python (Regex, Pandas, JSON, NLTK, Langdetect)

- Text Wrangling & Cleaning (emoji removal, stemming, stopword filtering)

- Feature Engineering (unigrams, bigrams, count vectors)

- Data Transformation (JSON structuring, CSV exports)

- Collaborative Workflow (Colab, Git version history, documentation)

### Outcome:
Successfully transformed raw, noisy, semi-structured text into clean, structured datasets ready for NLP modelling, recommender systems, and information retrieval tasks. This project strengthened my ability to handle end-to-end text preprocessing pipelines — from parsing raw data to generating numerical representations for machine learning.
