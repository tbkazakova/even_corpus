# even_corpus
Here are files for creating [Bystraja Even Corpus](http://51.250.109.118:9000/search).

It is my thesis and a project of our expedition team from HSE.

### Directory "dict_processing":
- Program for processing of the Even dictionary. It gets one-word Russian translations for Even word stems.
- Program for getting POS tas for Even words using one-word Russian translations.
- Manually checked table with one-word translations and POS tags obtained using the program.

### Directory "apertium-eve":
- eve.lexd which describes morphological word structure
- eve.twol with some morphophonological rules
- Program for getting morphological tags and segmentation of the Even word and for turning morphological tags into usual gloss anotation

### Directory "newspaper_annotation":
- Program for processing texts and getting frequency word list.
- Program for processing texts and getting morphological annotation.

### Program "txt2json":
- Program for turning txt files with annotated sentences into special tsakorpus json format

### Directory "txt_good_texts":
- Annotated texts in txt files (for turning into json for the corpus)

### Directory "json_texts":
- Texts in json files for the corpus

### Directory "eaf":
- eaf and mp3 files for the texts with audio
