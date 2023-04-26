Module academic_crawler.scrapers.strategies.org_structure
=========================================================

Classes
-------

`OrgStructureStrategy(input_data)`
:   Helper class that provides a standard way to create an ABC using
    inheritance.

    ### Ancestors (in MRO)

    * academic_crawler.scrapers.strategies.BaseScrapingStrategy
    * abc.ABC

    ### Methods

    `extract_sections(self) ‑> tuple[academic_crawler.heuristics.tree.node.EntityNode]`
    :

    `extract_template_instances(self, records: list)`
    :

    `parse_sections(self) ‑> dict`
    :

    `run(self)`
    :