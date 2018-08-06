# Lithuanian_snowball_stemmer_preprocessing
Implementation of Snowball stemmer use with Lithuanian language in python

Code is written in python3, ipynb style for working in the cloud (expample google collab )

Code was used for preprocessing book titles and descriptions.
It clones and builds https://github.com/snowballstem/snowball repo. Then using Python subproccess, makes a dictionary for the data where all words are mapped to its stemmed versions. At the final step, cleaning is done.
