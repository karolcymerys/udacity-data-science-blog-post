#  AI Tools usage analysis based on StackOverflow Developer Survey from 2025
___

AI tools are becoming more and more popular in Software Development. 
This project aims to investigate real usage of AI tools in that industry by conducting analysis of [StackOverflow Developer Survey from 2025](https://survey.stackoverflow.com).
This analysis aims to answer for following questions:
1. How much AI tools were actively used in software development by different age groups in 2025?
2. How much AI tools were actively used in software development by different roles in 2025?
3. How much AI tools were actively used in software development by different industries in 2025?
4. How did respondents rate the trust in AI-generated output, depending on their level of use in 2025?

This project was created as part of Project #1 for [Udacity Data Scientist Nanodegree Program](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

## Installation

### Requirements

- Python 3
- Git

1. Clone repository into your local machine:
 ```bash
git clone https://github.com/karolcymerys/udacity-data-science-blog-post.git 
```

2. Go into root of the project:
```bash
cd ./udacity-data-science-blog-post
```

3. Create new virtual environment (optional):
```bash
python -m venv .venv 
```

4. Install required:
```bash
pip install -r requirements.txt 
```

## File Descriptions

```text
udacity-data-science-blog-post/
├── data/
│   ├── raw_data.csv     # Original, unmodified data
│   └── cleaned_data.csv # Cleaned/transformed dataset
├── analysis.ipynb       # Jupyter notebooks with performed analysis
├── requirements.txt     # Project dependencies
└── docs/                # Blog post related files
```

## Acknowledgements

- Dataset: [StackOverflow Developer Survey](https://survey.stackoverflow.com)
- Tools and libraries: Python, pandas, NumPy, matplotlib, seaborn, and Jupyter Notebook.