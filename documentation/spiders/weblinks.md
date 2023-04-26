Module academic_crawler.spiders.weblinks
========================================

Functions
---------

    
`process_links(links)`
:   

Classes
-------

`WeblinksSpider(*a, **kw)`
:   Base class for scrapy spiders. All spiders must inherit from this
    class.

    ### Ancestors (in MRO)

    * scrapy.spiders.crawl.CrawlSpider
    * scrapy.spiders.Spider
    * scrapy.utils.trackref.object_ref

    ### Class variables

    `allowed_domains`
    :

    `base_url`
    :

    `custom_settings: Optional[dict]`
    :

    `name: Optional[str]`
    :

    `rules: Sequence[scrapy.spiders.crawl.Rule]`
    :

    `start_urls`
    :

    ### Methods

    `parse(self, response)`
    :

    `parse_item(self, response)`
    :