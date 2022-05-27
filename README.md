# even_corpus
There are files for creating Bystraja Even Corpus.

It is my thesis and a project of our expedition team from HSE.

Now there are some drafts.

Directory "dict_processing" contains:
- Programm for preprocessing of the Even dictionary. It gets one-word Russian translations for Even word stems.
- Programm for getting POS tas for Even words using one-word Russian translations.
- Manually checked table with one-word translations and POS tags obtained using the program.

Directory "apertium-eve" contains:
- eve.lexd which describes morphological word structure
- eve.twol with some morphophonological rules
- Programm for getting morphological tags and segmentation of the Even word
- Programm for turning morphological tags into usual gloss anotation

Directory "txt2json":
- Programm for turning txt files with annotated sentences into spesial tsakorpus json format
