Module academic_crawler.heuristics.page_vocabulary.similarity
=============================================================

Functions
---------

    
`cosine_similarity_numba(u: numpy.ndarray, v: numpy.ndarray)`
:   

Classes
-------

`VocabSimilarityManager(vocabulary: academic_crawler.heuristics.page_vocabulary.vocabulary.DomainVocabulary)`
:   

    ### Methods

    `get_categories_similarity(self, word: str) ‑> dict`
    :   Get the similarity of a word to all categories in the vocabulary

    `get_category_top_n_similar(self, word: str, category: str, n=5) ‑> list[tuple[str, float]]`
    :   Get the top n similar words to a word in a category

    `get_keyword_category(self, word: str) ‑> tuple[typing.Any, float]`
    :   Get the category of a word and the confidence of the category

    `get_max_category(self, categories_similarity: dict) ‑> str`
    :