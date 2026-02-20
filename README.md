# Project 

Sentiment Analysis of Amazon Reviews Using Classical NLP and Neural Networks

# Overview

This project compares natural language processing techniques (Bag-of-Words and TF-IDF) with a neural network approach for sentiment classification on Amazon reviews. My goal is to find whether deep learning provides meaningful improvements over classical models.

# Methods

Logistic Regression with Bag-of-Words

Logistic Regression with TF-IDF

Neural Network 

# Key Results

Classical models achieved ~93% accuracy. It had a similar outcome to the neural network while requiring less complexity.

# How to Run

Open 593Portfolio1.ipynb and run all cells

# Requirements

Python, pandas, numpy, sklearn, pytorch, matplotlib, seaborn, gensim
















## Grading

Your work will be evaluated on:
- **Conceptual Understanding** (5 pts): Do you explain *why* you chose specific methods? Do you connect to course material?
- **Technical Implementation** (5 pts): Does your code run without errors? Do all components work correctly?
- **Code Quality & Documentation** (5 pts): Is your notebook/code clear and well-organized? Does it tell a story?
- **Critical Analysis** (5 pts): Do you interpret results thoughtfully? Discuss limitations and tradeoffs?
- **Peer Reviews** (5 pts): Did you provide constructive feedback on two classmates' projects?

See the full [rubric](https://lauren897.github.io/cds593-private/rubrics.html#portfolio-piece-rubric) for details.

## Suggested Repository Structure

You're free to organize this however makes sense for your project, but here's a structure that works well:

```
your-portfolio-piece/
├── README.md (this file - update it with your project details)
├── requirements.txt or equivalent
├── notebooks/
│   └── main_analysis.ipynb (or multiple notebooks)
├── src/ (optional - if you refactor code into modules)
├── data/ (see note below about data)
├── outputs/ (figures, saved models, etc.)
```

**About data**: If your dataset is small (<10 MB), you can include it in the repo. For larger datasets, put instructions in your README for how to download/access it, and add data files to `.gitignore`.


## Peer Review Process

You'll be assigned two classmates' repositories to review. Provide your feedback through **pull requests**:

1. Clone your assigned classmate's repository to your machine
2. Read through their notebooks, scripts, and documentation
3. Try running the code yourself
4. Create a pull request with inline comments on their code/analysis
5. In the PR description, provide overall feedback addressing:
   - What worked well conceptually and technically?
   - What could be clearer in the documentation or analysis?
   - Specific suggestions for deeper analysis or improvements
   - Overall strengths of the project

Be constructive and specific. Good peer reviews identify both strengths and areas for growth.

You are *not* grading each other's pieces, just providing feedback.

## Timeline

- **Friday, Feb 20**: Portfolio piece due (push your final version to this repo)
- **Friday, Feb 27**: Peer reviews due (submit PRs with feedback to your assigned classmates' repos)

