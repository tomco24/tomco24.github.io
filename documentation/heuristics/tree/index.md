Module academic_crawler.heuristics.tree
=======================================

Sub-modules
-----------
* academic_crawler.heuristics.tree.node
* academic_crawler.heuristics.tree.pruning
* academic_crawler.heuristics.tree.semantic

Classes
-------

`HTMLSematicTreeGenerator()`
:   

    ### Methods

    `build_page_tree(self, soup, fname='output.svg', add_nodes_to_graph=False)`
    :

    `get_node_link_level(self, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :

    `update_node_params(self, tree: networkx.classes.digraph.DiGraph, node, parent)`
    :