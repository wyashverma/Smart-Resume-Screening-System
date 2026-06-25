# AI-Powered Smart-Resume-Screening-System

## Overview

The AI-Powered Resume Analyzer is a Natural Language Processing (NLP) project that analyzes resumes and compares them with job descriptions to evaluate candidate-job compatibility.

The system preprocesses resume text, extracts meaningful features using TF-IDF Vectorization, and calculates similarity scores between resumes and job descriptions. This helps recruiters and job seekers understand how well a resume aligns with a specific role.

---

## Features

* Resume text extraction and preprocessing
* Text cleaning and normalization
* Tokenization and stopword removal
* TF-IDF feature extraction
* Resume-to-job description matching
* Similarity score calculation
* Candidate ranking based on relevance
* Data visualization and analysis

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn

### NLP Techniques

* Text Preprocessing
* Tokenization
* Stopword Removal
* TF-IDF Vectorization
* Cosine Similarity

---

## Project Workflow

### Step 1: Data Collection

* Load resume data
* Load job descriptions
* Convert textual information into processable format

### Step 2: Data Preprocessing

* Remove special characters
* Convert text to lowercase
* Remove stopwords
* Clean and normalize text

### Step 3: Feature Engineering

* Apply TF-IDF Vectorization
* Convert text into numerical feature vectors

### Step 4: Similarity Calculation

* Compute cosine similarity between resumes and job descriptions
* Generate matching scores

### Step 5: Result Generation

* Rank resumes
* Display similarity percentages
* Identify the best-matching candidates

---

## Project Structure

```bash
Resume-Analyzer/
│
├── data/
│   ├── resumes/
│   └── job_descriptions/
│
├── notebook/
│   └── resume_analysis.ipynb
│
├── outputs/
│   ├── matching_results.csv
│   └── visualizations/
│
├── requirements.txt
├── README.md
└── LICENSE
```

## Installation

### Clone the Repository

```bash
git clone https:[//github.com/your-username/resume-analyzer.git](https://github.com/wyashverma/Smart-Resume-Screening-System)
```

### Navigate to Project Folder

```bash
cd resume-analyzer
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
resume_analysis.ipynb
```

Execute all cells to:

* Load data
* Preprocess resumes
* Generate TF-IDF vectors
* Calculate similarity scores
* View matching results

---

## Sample Output

| Resume      | Match Score |
| ----------- | ----------- |
| Candidate A | 87%         |
| Candidate B | 78%         |
| Candidate C | 65%         |

The candidate with the highest score is considered the best fit for the job description.

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Natural Language Processing (NLP)
* Feature Engineering
* Text Vectorization
* Cosine Similarity
* Machine Learning Workflows
* Data Analysis using Python
* Building real-world AI applications

---

## Future Enhancements

* Resume parsing using PDF extraction
* Skill gap analysis
* Advanced NLP using BERT
* Web-based interface using Flask or Streamlit
* Automated resume recommendations

---

## Author

**Mohit Kumar**

B.Tech (Computer Science Engineering - Machine Learning)

GitHub: https://github.com/wyashverma

LinkedIn: www.linkedin.com/in/mohit-kumar-gupta-ab7774250

---

## License

This project is licensed under the MIT License.
