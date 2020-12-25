# computational-resonance
This repository contains supplementary materials for Chapot, Laura. "Computational Resonance" in _Canadian Review of Comparative Literature_.


## Supplementary Materials
To consult the array of topic models used for analyses click on `array-of-topic-models` above.


## Results
The directory `topic-model-results` contains the original topic model outputs used for developing the analyses. 
<br>
I generated a number of topic models of the corpus varying the number of topics (from 5 to 10) and running each topic model twice. I used two topic model outputs: lists of topics with their most frequent words and lists of distributions of topics over each document in the corpus. For example, `topic-model-results/mann-topwords-5` is a list of topics with their most frequent words with a parameter of 5 topics. And `topic-model-results/mann-topicsperdoc-5` is the distribution of those topics over each document in the corpus.


## Corpus
The directory `mann-novellas-corpus` contains the corpus of Thomas Mann's early novellas used for generating the topic models. 
<br>
The texts that compose this corpus include the collection _Der kleine Herr Friedemann_ (1898) — which comprises the stories “Der kleine Herr Friedemann” (1896), “Der Tod” (1897), “Der Wille zum Glück” (1896), “Enttaüschung” (1896), “Der Bajazzo” (1897) and “Tobias Mindernickel” (1898) — and the novellas _Gladius Dei_ (1902), _Tristan_ (1903), _Tonio Kröger_ (1903), _Schwere Stunde_ (1905) and _Der Tod in Venedig_ (1912).


N.B. This corpus is not lemmatized.
<br>
The collection of novellas contained in _Der kleine Herr Friedemann_ (1898) has been preserved as a collection, it has not been split into the individual constitutive stories. 


## Forthcoming
I will be adding Notebooks to generate your own topic models of the corpus.