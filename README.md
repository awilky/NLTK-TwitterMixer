# NLTK-TwitterMixer

The NLTK TwitterMixer generates new text based on tweets scraped from the Twitter API.

Twitter data is collect by a simple search query.

Writing functions scrape part of speech patterns from sentences and compile words from the text into a part of speech, python dictionary. They create new sentences by looping through the part of speech pattern and making a random choice from the part of speech dictionary.

Words used in the new text can be restricted to only those which contain a specified list of phonemes (i.e. particular sounds, like the consonant 'R' and/or the vowel, 'OO'). Because the functions implement the CMU Pronouncing Dictionary, rather than regex search, differences in spelling don't affect the results (e.g. 'ER' will return both hurt, HH ER T, and heard, HH ER D).

Packages required:

Natural Language Toolkit (NLTK) (including the CMU Pronouncing Dict Corpora, CMUDict) installed on your local machine (see installation / getting started instructions at http://www.nltk.org/install.html). If you are using Anaconda or Miniconda, the NLTK package for Anaconda/Miniconda must also be installed.

Tweepy
