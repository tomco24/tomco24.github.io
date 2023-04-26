Module academic_crawler.heuristics.page_features
================================================

Sub-modules
-----------
* academic_crawler.heuristics.page_features.keyword_features
* academic_crawler.heuristics.page_features.ner_features
* academic_crawler.heuristics.page_features.pipeline

Classes
-------

`AbstractPageFeatureExtractor(state)`
:   Helper class that provides a standard way to create an ABC using
    inheritance.

    ### Ancestors (in MRO)

    * abc.ABC

    ### Descendants

    * academic_crawler.heuristics.page_features.keyword_features.KeywordPageFeatureExtractor
    * academic_crawler.heuristics.page_features.ner_features.NERPageFeatureExtractor

    ### Methods

    `extract_features(self)`
    :

    `extract_title_features(self)`
    :

    `get_tag_only_text(self, tag: bs4.element.Tag, recursive=False)`
    :