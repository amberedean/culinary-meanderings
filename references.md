**References**

The Flavor Connection
https://www.scientificamerican.com/article/flavor-connection-taste-map-interactive/

Principles of food pairing
https://www.nature.com/articles/srep00196

To include supplemental datasets and info.

https://github.com/vchahun/word-salad
http://victor.chahuneau.fr/pub/menus/

Data from Chahuneau et al. (2012): http://victor.chahuneau.fr/pub/menus/data
(Dan Jurafsky may also have data:
http://web.stanford.edu/~jurafsky/foodpubs.html)

Source references (Craig Pfeifer)
http://listserv.linguistlist.org/pipermail/corpora/2014-July/024947.html

The Unified Medical Language System Metathesaurus
http://www.nlm.nih.gov/research/umls/ has semantic type food:
http://www.nlm.nih.gov/research/umls/META3_current_semantic_types.html

The LA Times did a writeup of scraping together a database from their archive of recipes using NLTK
http://datadesk.latimes.com/posts/2013/12/natural-language-processing-in-the-kitchen

http://www.ark.cs.cmu.edu/CURD/
Carnegie Mellon University Recipe Database

Teng et al (2012) created a large dataset of recipes by crawling allrecipes.com: http://arxiv.org/pdf/1111.3919

IBM's recipe generation project is based in part on NLP analysis of food resources, but I'm not sure whether these resources are described in detail anywhere:
http://spectrum.ieee.org/computing/software/creating-recipes-with-artificial-intelligence
http://arxiv.org/pdf/1311.1213v1

Malmaud et al's (2014) ACL paper "Cooking with Semantics"
http://www.cs.ubc.ca/~murphyk/Papers/acl2014.pdf is not a "resource" of the sort you're seeking but, similar to Teng et al it points to a corpus-driven approach to inducing some of the things you're looking for—just the sort of thing we ought to recommend here on corpora-list. Even without the CURD database that Diarmuid links, a verb in the executable part of a recipe has a good chance of being a "process", and a noun phrase is likely to be an "ingredient".

Data from Chahuneau et al. (2012): http://victor.chahuneau.fr/pub/menus/data
(Dan Jurafsky may also have data:
http://web.stanford.edu/~jurafsky/foodpubs.html)

I believe some work at U.Saarland covered food and recipes and generated resources in a variety of modalities; see e.g.
http://www.coli.uni-saarland.de/~regneri/docs/TACoS.pdf .
