Module academic_crawler.scrapers.operations.people
==================================================

Functions
---------

    
`annotate_person_data(lines: list[str], detector: NERDetector, organization: Organization)`
:   Annotates input lines with person attributes
    Args:
        lines:
        detector:
        organization:
    
    Returns:

    
`confirm_name_on_single_page(G: networkx.classes.digraph.DiGraph, person: academic_crawler.scrapers.templates.Person) ‑> academic_crawler.scrapers.operations.OperationResult`
:   

    
`extract_affiliation_elements(leaf: academic_crawler.heuristics.tree.node.SemanticNode, person: academic_crawler.scrapers.templates.Person, vocab_manager: OrgVocabularyManager)`
:   Extracts affiliation elements from a single page with PAGE_SINGLE_PERSON tag
    Args:
        leaf:
        person:
        vocab_manager:
    
    Returns:

    
`extract_affiliations_candidates_from_single_page(leaf: academic_crawler.heuristics.tree.node.SemanticNode, person: academic_crawler.scrapers.templates.Person, name_nodes) ‑> academic_crawler.scrapers.operations.OperationResult`
:   Extracts affiliation candidates from a single page
    Args:
        leaf:
        person:
        name_nodes:
    
    Returns:

    
`extract_data_from_page(G: networkx.classes.digraph.DiGraph)`
:   Extract person data from page
    Args:
        G:
    
    Returns:

    
`extract_neigborhood(fulltext: str, ner_entity, size=100)`
:   

    
`extract_ner_candidates_joined(values, position_set, keyword_set)`
:   

    
`extract_ner_candidates_key_value(node, position_set)`
:   

    
`filter_affiliation_candidates(G: networkx.classes.digraph.DiGraph, person: academic_crawler.scrapers.templates.Person, candidates, vocab_manager)`
:   Filters affiliation candidates (not used)
    Args:
        G:
        person:
        candidates:
        vocab_manager:
    
    Returns:

    
`filter_candidates_join(person, candidates)`
:   

    
`filter_candidates_key_value(person, candidates, vocab_manager)`
:   

    
`get_ner_noun_split(value, ner_entity=None)`
:   

    
`get_sibling_tags(node: academic_crawler.heuristics.tree.node.SemanticNode)`
:   

    
`get_siblings_for_tag(tag)`
:   

    
`split_page_to_single_pages(G: networkx.classes.digraph.DiGraph)`
: