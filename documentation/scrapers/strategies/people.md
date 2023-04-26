Module academic_crawler.scrapers.strategies.people
==================================================

Classes
-------

`PeopleStrategy(input_data)`
:   Helper class that provides a standard way to create an ABC using
    inheritance.

    ### Ancestors (in MRO)

    * academic_crawler.scrapers.strategies.BaseScrapingStrategy
    * abc.ABC

    ### Methods

    `extract_people_data(self, tree, template_instances_dict)`
    :

    `extract_sections(self) ‑> tuple[academic_crawler.heuristics.tree.node.EntityNode]`
    :

    `extract_template_instances(self, records: list[dict]) ‑> list`
    :

    `parse_sections(self) ‑> dict`
    :

    `run(self)`
    :