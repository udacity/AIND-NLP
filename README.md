# AIND: Natural Language Processing

Coding exercises for the Natural Language Processing concentration, part of Udacity's Artificial Intelligence Nanodegree program.

## Setup

You need Python 3.6+, and the packages mentioned in `requirements.txt`. You can install them using:

```bash
pip install -r requirements.txt
```

## Data

Data files for exercises are included under `data/`, but some of the NLP libraries require additional data for performing tasks like 
PoS tagging, lemmatization, etc. Specifically, `nltk` will throw an error if the required data is not installed. You can use the 
following Python statement to open the NLTK downloader and select the desired package(s) to install:

```python
nltk.download()
```

You can also download all available NLTK data packages, which includes a number of sample corpora as well, but that may take a while 
(10+GB).

## Run

To run any script file, use:

```bash
python <script.py>
```

To open a notebook, use:

```bash
jupyter notebook <notebook.ipynb>
```

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.
