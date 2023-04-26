Module academic_crawler.middlewares
===================================

Classes
-------

`AcademicCrawlerDownloaderMiddleware()`
:   

    ### Static methods

    `from_crawler(crawler)`
    :

    ### Methods

    `process_exception(self, request, exception, spider)`
    :

    `process_request(self, request, spider)`
    :

    `process_response(self, request, response, spider)`
    :

    `spider_opened(self, spider)`
    :

`AcademicCrawlerSpiderMiddleware()`
:   

    ### Static methods

    `from_crawler(crawler)`
    :

    ### Methods

    `process_spider_exception(self, response, exception, spider)`
    :

    `process_spider_input(self, response, spider)`
    :

    `process_spider_output(self, response, result, spider)`
    :

    `process_start_requests(self, start_requests, spider)`
    :

    `spider_opened(self, spider)`
    :