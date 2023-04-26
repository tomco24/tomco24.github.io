Module academic_crawler.scrapers.base
=====================================

Classes
-------

`BaseScraper()`
:   Helper class that provides a standard way to create an ABC using
    inheritance.

    ### Ancestors (in MRO)

    * abc.ABC

    ### Descendants

    * academic_crawler.scrapers.org_structure.OrgStructureScraper
    * academic_crawler.scrapers.people.PeopleScraper

    ### Methods

    `add_instance(self, instance)`
    :

    `scrape(self, input_data: dict)`
    :