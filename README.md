# Spanish NLP Workshop
A tutorial about NLP technologies available for the Spanish language

### Setup
 * Install [Anaconda](https://www.continuum.io/downloads)
 * Create a python 3 environment and start a notebook server
 ```bash
 $ git clone https://github.com/eisenjulian/spanish-nlp-workshop.git
 $ cd spanish-nlp-workshop
 $ conda config --add channels conda-forge
 $ conda create -n nlp python=3 gensim spacy matplotlib scikit-learn pandas ipykernel
 $ activate nlp
 $ python -m ipykernel install --user
 $ python -m spacy download es
 $ jupyter notebook
 ```
