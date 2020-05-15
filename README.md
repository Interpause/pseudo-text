# pseudo-text
My code and documentation while exploring NLP under an internship.
## Description
I was attempting a content-based approach for fake-news detection, using an algorithm designed to extract queries from a text and google search them, before using entailment to detect contradictions. Sorry that this readme and repo is kinda messy.
- [Final Presentation Slides](https://docs.google.com/presentation/d/1sQhYRWtfti5F14P6gyEYhAKyrRIYWjMRG3lKo0jkGoE/edit?usp=sharing): my slides probably explains it better.
- [Plan.ipynb](Plan.ipynb): original plan, couldn't finish it completely.
- [research.ipynb](research.ipynb): my research
## Useful Code
- [how_to_query_a_database_EX_edition.ipynb](how_to_query_a_database_EX_edition.ipynb): A collation of many methods of embedding and similarity measurement during experimenting.
- [The_Pipe.ipynb](The_Pipe.ipynb): Completed Spacy version of BERTSumEXT, demo of how query extractor works
- [true_news_scraper.ipynb](true_news_scraper.ipynb): Code utilizing [newspaper3k](https://newspaper.readthedocs.io/en/latest/) to scrape from multiple news sources in parallel
## Experimental code
- [ALBERT_for_SNLI.ipynb](ALBERT_for_SNLI.ipynb): Code for training [Transformers library ALBERT](https://huggingface.co/transformers/) on [SNLI dataset](https://nlp.stanford.edu/projects/snli/)
- [BERTsum.ipynb](BERTsum.ipynb): Experimental attempt at essentially a VAE using transformers. It didn't work very well.
- [LIAR_dataset_classifying_using_svm.ipynb](LIAR_dataset_classifying_using_svm.ipynb): Classifying the [LIAR dataset](https://www.aclweb.org/anthology/P17-2067/) using SVM.
- [Query_extraction_and_BERTSumEXT.ipynb](Query_extraction_and_BERTSumEXT.ipynb): Experimenting with using them
## History of project
- Before i used YangNLP, I was attempting to replicate/beat his abstractive model using a Albert Bert hybrid trained in a similar fashion (insert notebook)
- LIAR Dataset, where i started by brushing up on skills and basic techniques
- Plan, remnants from a more research than application based approach
- How to query a database: I failed to beat google at data querying and realised the key lies in optimizing google’s immense search database by using well-adjusted search queries (tfidf, tsss, sent-transform, gensim, blah)
- Research.ipynb: my initial research to get myself up to date and know what to do etc
- Testing_all_the_news: Back when i was trying to create my own pool of news articles
- True_news_scraper: newspaper3k plus some optimizations by me used to scrap 14k high quality dataset that can be used for other things







