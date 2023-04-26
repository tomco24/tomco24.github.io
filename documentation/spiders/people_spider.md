Module academic_crawler.spiders.people_spider
=============================================

Classes
-------

`PeopleSpider(*a, **kw)`
:   Base class for all spiders from this component.

    ### Ancestors (in MRO)

    * academic_crawler.spiders.academic_spider.AcademicSpider
    * scrapy.spiders.crawl.CrawlSpider
    * scrapy.spiders.Spider
    * scrapy.utils.trackref.object_ref

    ### Class variables

    `SCRAPING_WORKFLOW_TEMPLATES`
    :

    `controller: academic_crawler.controllers.people.PeopleController`
    :

    `custom_settings: Optional[dict]`
    :

    `name: Optional[str]`
    :

    ### Methods

    `change_scraping_state(self)`
    :   This method is used to change the scraping state
        Returns:

    `filter_managers(self, managers: list[academic_crawler.heuristics.links.LinkManager], keyword_category: str)`
    :   This method is used to filter the managers that contain the keyword_category category
        :param managers:
        :param keyword_category:
        :return:

    `filter_managers_to_scrape(self, managers: list[academic_crawler.heuristics.links.LinkManager], candidates_org_structure: list[academic_crawler.heuristics.links.LinkManager], candidates_people_page: list[academic_crawler.heuristics.links.LinkManager], candidates_negative: list[academic_crawler.heuristics.links.LinkManager], home_manager: academic_crawler.heuristics.links.LinkManager)`
    :   This method is used to filter the managers that are candidates to be scraped

    `filter_org_managers(self, managers: list[academic_crawler.heuristics.links.LinkManager], manager_ref: academic_crawler.heuristics.links.LinkManager)`
    :   This method is used to filter the managers that are sublinks of the manager_ref
        :param managers:
        :param manager_ref:
        :return:

    `get_page_type(self, response) ‑> academic_crawler.config.page_types.PAGE_TYPE`
    :   This method is used to get the page type of the current page
        :param response:
        :return:

    `parse_home(self, response, **kwargs)`
    :   This method is called when the spider is in the state of parsing the home page of the domain

    `process_scraping_state(self)`
    :   This method is used to process the current scraping state

    `scrape_orgs(self, response)`
    :   This method is used to scrape the organizations
        Args:
            response:

    `scrape_orgs_people(self, response)`
    :   This method is used to scrape the people of the organizations
        Args:
            response:

    `scrape_partial_people(self, instances)`
    :   This method is used to scrape the affiliations for partial Person instances from their PAGE_SINGLE_PERSON page.
        Args:
            instances:

    `scrape_people(self, response)`
    :   This method is used to scrape the people from current page
        Args:
            response:
        
        Returns:

    `scrape_people_candidates(self)`
    :   This method is used to scrape the candidate people pages

    `scrape_single_person(self, person)`
    :   This method is used to scrape the affiliations for a Person instance from their PAGE_SINGLE_PERSON page.
        Args:
            person:
        
        Returns:

    `setup_state_callback_map(self)`
    :

    `start_requests(self)`
    :