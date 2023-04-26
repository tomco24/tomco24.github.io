Module academic_crawler.helpers.node_data
=========================================

Classes
-------

`NodeDataExtractionHelper(page_type=PAGE_TYPE.PAGE_ORGANIZATIONS)`
:   Helper class for extracting data from a compound node in a semantic tree

    ### Methods

    `extract_data_from_node(self, node: academic_crawler.heuristics.tree.node.SemanticNode, ner_tag: str, keyword_category: str) ‑> list[dict]`
    :   Extract data from a node and return a list of dictionaries
        :param node: 
        :param ner_tag: 
        :param keyword_category:
        :return:

    `extract_partial_data_from_tag(self, node: academic_crawler.heuristics.tree.node.SemanticNode, i, ner_tag, keyword_category) ‑> dict`
    :   Extract data from a tag and return a dictionary with the data extracted
        :param node: 
        :param i: 
        :param ner_tag: 
        :param keyword_category:
        :return:

    `valid_conditions(self, ner_record: dict, keyword_rercord: dict, ner_tag: str, keyword_category: str) ‑> bool`
    :