#### Basic Terms
+ Tokenization:	Segmenting text into words, punctuations marks etc.
+ Part-of-speech: (POS) Tagging	Assigning word types to tokens, like verb or noun.
+ Dependency Parsing:	Assigning syntactic dependency labels, describing the relations between individual tokens, like subject or object.
+ Lemmatization:	Assigning the base forms of words. For example, the lemma of "was" is "be", and the lemma of "rats" is "rat".
+ Named Entity Recognition (NER):	Labelling named "real-world" objects, like persons, companies or locations.
+ Similarity:	Comparing words, text spans and documents and how similar they are to each other.
+ Sentence Boundary Detection (SBD):	Finding and segmenting individual sentences.
+ Text Classification:	Assigning categories or labels to a whole document, or parts of a document.
+ Rule-based Matching:	Finding sequences of tokens based on their texts and linguistic annotations, similar to regular expressions.
+ Training:	Updating and improving a statistical model's predictions.
+ Serialization:	Saving objects to files or byte strings.

### Installing the Library on Linux/Unix
+ sudo pip install spacy
+ sudo python -m spacy download en
+ sudo python -m spacy download fr

### Installing On Windows using Conda

+ conda install tqdm
+ conda install -c conda-forge spacy /conda install spacy
+ python -m spacy download en
- - with cmd administrator


### Installing using Conda
+ conda install -c conda-forge spacy
+ sudo python -m spacy download en
+ sudo python -m spacy download fr




#### For Download the Models of other languages
+ sudo python -m spacy download de
+ sudo python -m spacy download es
+ sudo python -m spacy download xx 


### Installing On Windows using Conda
+ conda config-add channel conda-forge
+ conda update anaconda
+ conda install tqdm
+ conda install -c conda-forge spacy
+ sudo python -m spacy download en