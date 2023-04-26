Module academic_crawler.scrapers.people
=======================================

Classes
-------

`PeopleScraper()`
:   This class is responsible for extracting people information from a given page.

    ### Ancestors (in MRO)

    * academic_crawler.scrapers.base.BaseScraper
    * abc.ABC

    ### Methods

    `filter_and_merge_duplicates(self, instances: list[academic_crawler.scrapers.templates.Person]) ‑> list[academic_crawler.scrapers.templates.Person]`
    :   This method filters out duplicates and merges them into one instance.
        Args:
            instances:
        
        Returns:

    `get_instances(self)`
    :

    `scrape(self, input_data: dict)`
    :   Scraping using PeopleStrategy
        Args:
            input_data:
        
        Returns:

    `scrape_single_person(self, input_data: dict)`
    :   Scraping using SinglePersonStrategy
        Args:
            input_data:
        
        Returns: