Module academic_crawler.heuristics.page_features.ner_features
=============================================================

Classes
-------

`NERPageFeatureExtractor(state, ner_type)`
:   Helper class that provides a standard way to create an ABC using
    inheritance.

    ### Ancestors (in MRO)

    * academic_crawler.heuristics.page_features.AbstractPageFeatureExtractor
    * abc.ABC

    ### Class variables

    `base_tag_set`
    :

    `ner_detector: <function Singleton.<locals>.get_instance at 0x7ff8989f2790>`
    :

    `nodes_map: collections.defaultdict[typing.Any, set[academic_crawler.heuristics.tree.node.SemanticNode]]`
    :

    `tagged_nodes: list[academic_crawler.heuristics.tree.node.SemanticNode]`
    :

    ### Methods

    `check_name_in_heading(self, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :

    `extract_features(self)`
    :

    `extract_title_features(self)`
    :

    `get_ner_node_weight(self, n)`
    :

    `has_found_enough(self)`
    :

    `node_ner_search(self, node: academic_crawler.heuristics.tree.node.SemanticNode, tag_set=None)`
    :

    `tag_ner_search(self, text, interval_idx=None)`
    :

    `tree_ner_search(self)`
    :

    `update_ner_stats(self, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :

    `update_node_ner_status(self, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :