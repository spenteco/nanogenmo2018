
# Velvet Black Sky

## *100 stories from an alternate universe*

For information about this project, please see [the page on my website](https://robineggsky.com/posts/velvet\_black\_sky.html).

The output is available [here](https://robineggsky.com/velvet_black_sky_2up.pdf).

The source data is available [here](https://robineggsky.com/scifi.tar.gz).

The notebooks run in order:

    1_select_cliched_sentences.ipynb
    2_create_new_sentences.ipynb
    3_make_stories.ipynb
    4_get_names.ipynb
    5_clean_stories.ipynb
    6_make_book.ipynb
  
The notebooks require [Mallet](https://mallet.cs.umass.edu/), [gensim](https://radimrehurek.com/gensim/), 
[Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/), [spaCy](https://spacy.io/), and Latex.  Mallet and CoreNLP require Java.  

I use an older (1.9) version of spaCy (the current version seems to require a huge amount of memory for novel-length texts); I could, of course, have used CoreNLP for everything . . . 
