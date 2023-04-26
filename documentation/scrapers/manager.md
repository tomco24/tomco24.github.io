Module academic_crawler.scrapers.manager
========================================

Classes
-------

`ScrapingManager()`
:   Scraping manager is responsible for managing the scraping process.

    ### Methods

    `add_instance_to_state(self, state, instance)`
    :

    `add_manager_to_state(self, state, manager)`
    :

    `add_org(self, org: academic_crawler.scrapers.templates.Organization, idx)`
    :

    `add_partial_idx(self, idx, length)`
    :

    `add_person(self, person, idx)`
    :

    `add_url_to_state(self, state, url)`
    :

    `add_visited_org_page(self, manager: academic_crawler.heuristics.links.LinkManager)`
    :

    `add_visited_people(self, manager: academic_crawler.heuristics.links.LinkManager)`
    :

    `build_structure_and_patterns(self)`
    :

    `extract_url_pattern(self, urls)`
    :

    `get_all_partial_persons(self)`
    :

    `get_callback(self, state)`
    :

    `get_instances(self, state)`
    :

    `get_managers(self, state)`
    :

    `get_orgs_urls(self, orgs)`
    :

    `get_page_types(self, state)`
    :

    `get_people_urls(self, people)`
    :

    `setup_states(self, orgs_managers, people_managers, other_managers)`
    :

`ScrapingState(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   An enumeration.

    ### Ancestors (in MRO)

    * enum.Enum

    ### Class variables

    `PARSE_HOME`
    :

    `SCRAPE_FINISHED`
    :

    `SCRAPE_ORGS`
    :

    `SCRAPE_ORGS_PEOPLE`
    :

    `SCRAPE_OTHER`
    :

    `SCRAPE_PARTIAL_PEOPLE`
    :

    `SCRAPE_PEOPLE`
    :