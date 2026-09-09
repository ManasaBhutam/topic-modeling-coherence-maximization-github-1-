# Topic Modeling with Coherence Maximization

An NLP and Machine Learning project that optimizes Latent Dirichlet Allocation (LDA) using topic coherence to produce more interpretable and semantically distinct topics.

## Project Overview
This project applies an end-to-end NLP pipeline to academic research abstracts:
- Text preprocessing with tokenization, stopword removal, and lemmatization
- Bag-of-Words vectorization
- Latent Dirichlet Allocation (LDA)
- Grid-search hyperparameter optimization
- Topic coherence / NPMI-based evaluation
- Analysis of discovered topics

## Dataset
The project report describes a corpus of 10,000 academic research abstracts from computer science and biomedical databases.

The original dataset is not included in this starter repository. Add it to `data/` if you have permission to redistribute it.

## Technologies
- Python
- NLTK
- Gensim
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Repository Structure
```text
data/         Dataset or dataset instructions
notebooks/    Jupyter notebooks
src/          Python source code
results/      Experiment outputs
screenshots/  Project screenshots
report/       Project report
```

## Reported Result
The project report identifies K = 15 as the optimal number of topics, with a maximum coherence score of 0.68.

## How to Run
1. Create a Python virtual environment.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Add the permitted dataset to `data/`.
4. Run the notebook in `notebooks/` or implement the pipeline using the modules in `src/`.

## Note
The source-code files in this repository are starter templates because the uploaded project report contains the methodology and results, but not the complete original Python implementation.
