Module academic_crawler.heuristics.tree.semantic
================================================

Functions
---------

    
`num_of_repeats(nums_rest, subseq)`
:   

    
`print_in_degree_zero_nodes(G)`
:   

Classes
-------

`SemanticTreeGenerator()`
:   

    ### Methods

    `build_DOM_tree(self, G: networkx.classes.digraph.DiGraph, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :

    `build_merged_node(self, G: networkx.classes.digraph.DiGraph, nodes: list[academic_crawler.heuristics.tree.node.SemanticNode])`
    :

    `build_page_tree(self, soup: bs4.BeautifulSoup, start='body', prune=True)`
    :

    `find_partition(self, G, node)`
    :

    `get_DOM_tree(self, tag: bs4.element.Tag)`
    :

    `get_id(self, node: academic_crawler.heuristics.tree.node.SemanticNode)`
    :

    `get_max_repeating_sequence(self, G, nodes)`
    :

    `get_path_map_id(self, data_node)`
    :

    `merge_consequent_nodes(self, G, nodes)`
    :

    `merge_same_type_nodes(self, type_seq, tau, G, S, node)`
    :

    `merge_substring_nodes(self, type_seq, alpha, G, nodes, parent, remaining_merges)`
    :

    `partition_tree(self, G: networkx.classes.digraph.DiGraph, node)`
    :

    `prune_DOM_tree(self, G: networkx.classes.digraph.DiGraph, root)`
    :