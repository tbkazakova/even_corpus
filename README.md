# even_corpus
There are files for creating Bystraja Even Corpus.

It is my thesis and a project of our expedition team from HSE.

Now there are some drafts.

### Directory "dict_processing" contains:
- Program for preprocessing of the Even dictionary. It gets one-word Russian translations for Even word stems.
- Program for getting POS tas for Even words using one-word Russian translations.
- Manually checked table with one-word translations and POS tags obtained using the program.

### Directory "apertium-eve" contains:
- eve.lexd which describes morphological word structure
- eve.twol with some morphophonological rules
- Program for getting morphological tags and segmentation of the Even word and turning morphological tags into usual gloss anotation

### Program "txt2json":
- Program for turning txt files with annotated sentences into special tsakorpus json format
