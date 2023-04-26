Module academic_crawler.heuristics.tree.node
============================================

Classes
-------

`CNRNode(weight: int, text_length: int)`
:   CNRNode(weight: int, text_length: int)

    ### Class variables

    `text_length: int`
    :

    `weight: int`
    :

    ### Instance variables

    `cnr`
    :

`EntityNode()`
:   This class is responsible for representing a entity attributes of a node in the tree.

    ### Methods

    `add_keyword_match(self, idx, result_keyword)`
    :

    `add_ner(self, results_ner)`
    :

    `features(self, id_)`
    :

    `num_tags_ner(self, type=None) ‑> int`
    :

    `search_in_values(self, search_string, threshold=2)`
    :

    `setup_keyword_structure(self)`
    :

    `setup_ner_structure(self)`
    :

    `update_keywords_stats(self, result_keyword)`
    :

    `update_ner_status(self, result_ner)`
    :

    `update_ner_tag(self)`
    :

    `update_parent_ner_stats(self)`
    :

`SemanticNode(tag: bs4.element.Tag, parent: SemanticNode)`
:   This class is responsible for representing a node in the tree.

    ### Instance variables

    `cnr`
    :

    ### Methods

    `get_full_tag_path(self, i)`
    :

    `get_ner_in_tag(self, ner_type, search_tag)`
    :

    `get_serializable(self)`
    :

    `get_tag_feature(self, id_)`
    :

    `get_tag_features(self)`
    :

    `get_value_link(self, idx)`
    :

    `has_same_path(self, other)`
    :

    `is_link_descendant(self)`
    :

    `merge(self, other, same=True)`
    :

    `set_cnr(self, weight, length)`
    :

    `set_path_string(self)`
    :