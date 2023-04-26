Module academic_crawler.helpers.runners
=======================================

Functions
---------

    
`run_spider_org_structure(program_state: academic_crawler.config.state.ProgramState)`
:   Runs the organization spider and returns the scraped items.

    
`run_spider_people(program_state: academic_crawler.config.state.ProgramState)`
:   Runs the people spider and returns the scraped items.
    :param program_state:
    :return:

Classes
-------

`AcademicCrawlerRunner(settings=None)`
:   Crawler object that collects items and returns output after finishing crawl.

    ### Ancestors (in MRO)

    * scrapy.crawler.CrawlerRunner

    ### Methods

    `crawl(self, crawler_or_spidercls, *args, **kwargs)`
    :   Run a crawler with the provided arguments.
        
        It will call the given Crawler's :meth:`~Crawler.crawl` method, while
        keeping track of it so it can be stopped later.
        
        If ``crawler_or_spidercls`` isn't a :class:`~scrapy.crawler.Crawler`
        instance, this method will try to create one using this parameter as
        the spider class given to it.
        
        Returns a deferred that is fired when the crawling is finished.
        
        :param crawler_or_spidercls: already created crawler, or a spider class
            or spider's name inside the project to create it
        :type crawler_or_spidercls: :class:`~scrapy.crawler.Crawler` instance,
            :class:`~scrapy.spiders.Spider` subclass or string
        
        :param args: arguments to initialize the spider
        
        :param kwargs: keyword arguments to initialize the spider

    `item_scraped(self, item, response, spider)`
    :

    `return_items(self, result)`
    :