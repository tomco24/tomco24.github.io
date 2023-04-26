Module academic_crawler.spiders.organization_spider
===================================================

Classes
-------

`OrganizationSpider(*a, **kw)`
:   This spider is responsible for extracting organization information from main website of a given domain.

    ### Ancestors (in MRO)

    * academic_crawler.spiders.academic_spider.AcademicSpider
    * scrapy.spiders.crawl.CrawlSpider
    * scrapy.spiders.Spider
    * scrapy.utils.trackref.object_ref

    ### Class variables

    `custom_settings: Optional[dict]`
    :

    `name: Optional[str]`
    :

    `rules: Sequence[scrapy.spiders.crawl.Rule]`
    :

    ### Methods

    `look_for_subdomain_link(self, response)`
    :   This method tries to find a link to the subdomain of the Organization instance
        Args:
            response:

    `parse_candidate(self, response)`
    :   This method tries to extract Organization instances from the given response page
        Args:
            response:
            **kwargs:

    `parse_home(self, response, **kwargs)`
    :

    `setup_state_callback_map(self)`
    :

    `start_requests(self)`
    :