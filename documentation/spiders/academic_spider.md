Module academic_crawler.spiders.academic_spider
===============================================

Classes
-------

`AcademicSpider(*a, **kw)`
:   Base class for all spiders from this component.

    ### Ancestors (in MRO)

    * scrapy.spiders.crawl.CrawlSpider
    * scrapy.spiders.Spider
    * scrapy.utils.trackref.object_ref

    ### Descendants

    * academic_crawler.spiders.organization_spider.OrganizationSpider
    * academic_crawler.spiders.people_spider.PeopleSpider

    ### Class variables

    `rules: Sequence[scrapy.spiders.crawl.Rule]`
    :

    ### Methods

    `generate_page_header(self, response)`
    :   Generates a page header from a response object.
        :param response:
        :param prune_tree:
        :return:

    `get_callback(self, state)`
    :

    `get_page_links(self, response, previous_history, home_manager=None) ‑> list[academic_crawler.heuristics.links.LinkManager]`
    :   Returns a list of LinkManager objects from a response object.
        :param response:
        :param previous_history:
        :param home_manager:
        :return:

    `get_scrapy_response_from_manager(self, manager)`
    :

    `get_scrapy_response_from_url(self, url)`
    :

    `get_state_callback(self)`
    :

    `next_state(self, approval=True, page_type=None)`
    :

    `setup_state_callback_map(self)`
    :