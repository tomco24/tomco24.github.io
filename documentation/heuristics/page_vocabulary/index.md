Module academic_crawler.heuristics.page_vocabulary
==================================================

Sub-modules
-----------
* academic_crawler.heuristics.page_vocabulary.similarity
* academic_crawler.heuristics.page_vocabulary.vocabulary

Classes
-------

`OrgVocabularyManager()`
:   

    ### Class variables

    `nlp: Union[spacy.language.Language, Any]`
    :

    ### Methods

    `add_keyword_candidate(self, keyword, category)`
    :

    `detect_possible_keywords(self, text) ‑> list[tuple[str, str, float]]`
    :

    `get_noun_phrases_rating(self, noun_phrases, category=None) ‑> list[tuple[str, float]]`
    :

    `insert_candidates_into_vocabulary(self)`
    :