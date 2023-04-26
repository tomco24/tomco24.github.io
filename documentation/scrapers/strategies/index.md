Module academic_crawler.scrapers.strategies
===========================================

Sub-modules
-----------
* academic_crawler.scrapers.strategies.org_structure
* academic_crawler.scrapers.strategies.people
* academic_crawler.scrapers.strategies.single_person

Classes
-------

`BaseScrapingStrategy()`
:   Helper class that provides a standard way to create an ABC using
    inheritance.

    ### Ancestors (in MRO)

    * abc.ABC

    ### Descendants

    * academic_crawler.scrapers.strategies.org_structure.OrgStructureStrategy
    * academic_crawler.scrapers.strategies.people.PeopleStrategy
    * academic_crawler.scrapers.strategies.single_person.SinglePersonStrategy

    ### Methods

    `extract_template_instances(self) ‑> list`
    :

    `run(self)`
    :