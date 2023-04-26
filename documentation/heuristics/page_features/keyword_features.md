Module academic_crawler.heuristics.page_features.keyword_features
=================================================================

Classes
-------

`KeywordPageFeatureExtractor(state)`
:   Helper class that provides a standard way to create an ABC using
    inheritance.

    ### Ancestors (in MRO)

    * academic_crawler.heuristics.page_features.AbstractPageFeatureExtractor
    * abc.ABC

    ### Class variables

    `keyword_detector: academic_crawler.heuristics.detectors.KeywordDetector`
    :

    ### Methods

    `extract_features(self)`
    :

    `extract_title_features(self)`
    :

    `node_keyword_search(self, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :

    `text_keyword_search(self, text)`
    :

    `tree_keyword_search(self)`
    :

    `update_keyword_status(self, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :