# pseudo-text

My code and documentation while exploring NLP under an internship.

## Description

I was attempting a content-based approach for fake-news detection, using an algorithm designed to extract queries from a text and google search them, before using entailment to detect contradictions.

- [Final Presentation Slides](https://docs.google.com/presentation/d/1sQhYRWtfti5F14P6gyEYhAKyrRIYWjMRG3lKo0jkGoE/edit?usp=sharing): my slides probably explains it better.
- [Plan.ipynb](Plan.ipynb): original plan, couldn't finish it completely.
- [research.ipynb](research.ipynb): some of what I read up on.

## Notable notebooks

- [how_to_query_a_database_EX_edition.ipynb](how_to_query_a_database_EX_edition.ipynb): A collation of many methods of embedding and similarity measurement during experimenting.
- [The_Pipe.ipynb](The_Pipe.ipynb): Completed [SpaCy pipeline adapter](https://spacy.io/usage/processing-pipelines) for [YangNLP's BERTSumEXT model](https://github.com/nlpyang/PreSumm), demo of how query extractor works
- [true_news_scraper.ipynb](true_news_scraper.ipynb): Code utilizing [newspaper3k](https://newspaper.readthedocs.io/en/latest/) to scrape from multiple news sources in parallel

## Other notebooks

- [ALBERT_for_SNLI.ipynb](ALBERT_for_SNLI.ipynb): Code for training [Transformers library ALBERT](https://huggingface.co/transformers/) on [SNLI dataset](https://nlp.stanford.edu/projects/snli/)
- [BERTsum.ipynb](BERTsum.ipynb): Experimental attempt at essentially a VAE using transformers. It didn't work very well.
- [LIAR_dataset_classifying_using_svm.ipynb](LIAR_dataset_classifying_using_svm.ipynb): Classifying the [LIAR dataset](https://www.aclweb.org/anthology/P17-2067/) using SVM.
- [Query_extraction_and_BERTSumEXT.ipynb](Query_extraction_and_BERTSumEXT.ipynb): Experimenting with using them

## Taken from presentation slides

![img/overview.jpg]

![img/extractor.jpg]
