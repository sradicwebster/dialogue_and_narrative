# Key phrase identification and classification of scientific publications
University of Bristol Interactive AI CDT first year module Dialogue and Narrative coursework to implement a solution to SemEval 2017 Task 10 "Extracting Keyphrases and Relations from Scientific Publications". Task description and data available from [CodaLab][coda].

The task involved sequence labelling and I used a Hidden Markov Model tagger using NLTK and a sequence tagger (Bi-LSTM-CRF) using [Flair][flair].

# Files
task1_alignment.ipynb -- align text files with annotations

nltk_bio.ipynb 	initial -- key phrase identification using NLTK HMM tagger

nltk_classification.ipynb -- key phrase classification using NLTK HMM tagger

key_phrase_model.ipynb -- key phrase identification using Flair sequence tagger

key_phrase_optimisation.ipynb -- optimising Flair sequence tagger

kp_type_model.ipynb -- key phrase classification using Flair sequence tagger



   [coda]: <https://competitions.codalab.org/competitions/15898>
   [flair]: <https://github.com/flairNLP/flair>
   

