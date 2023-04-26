Module academic_crawler.config.utils
====================================

Functions
---------

    
`clean_text(text)`
:   

    
`exclude_items_in_intervals(items, intervals)`
:   

    
`find_with_regex(text, to_find)`
:   

    
`flatten(list_of_lists)`
:   

    
`get_max_key_in_int_dict(d)`
:   

    
`get_noun_phrases_from_text(doc)`
:   

    
`get_parent_by_level(tag, level: int)`
:   Returns the `level`-th parent of `tag`.
    If `tag` does not have `level`-th parent, returns `None`.

    
`get_relabeled_tree(G: networkx.classes.digraph.DiGraph) ‑> networkx.classes.digraph.DiGraph`
:   This operation relabels the nodes of the tree with integers starting from 0.
    Args:
        G:
    
    Returns:

    
`get_tree_data_node(G: networkx.classes.digraph.DiGraph, node) ‑> SemanticNode`
:   

    
`get_tree_root(G: networkx.classes.digraph.DiGraph)`
:   

    
`in_domain(link, domain)`
:   

    
`load_from_pickle(filename)`
:   

    
`mergedict(args)`
:   

    
`node_has_links_in_children(G: networkx.classes.digraph.DiGraph, node: str)`
:   

    
`parse_path(path)`
:   

    
`save_graph(G: networkx.classes.digraph.DiGraph, fname='graph.svg')`
:   

    
`save_to_pickle(variable, filename)`
:   

    
`simple_word_tokenization(sentence, remove_stop=False)`
:   

    
`split_string(string, chunk_size=100000)`
:   

    
`url_match(url, pattern)`
: