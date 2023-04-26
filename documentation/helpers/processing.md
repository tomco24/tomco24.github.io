Module academic_crawler.helpers.processing
==========================================

Functions
---------

    
`process_scraped_org_structure_items(org_structure_items: list[dict]) ‑> list[academic_crawler.scrapers.templates.Organization]`
:   This function processes the scraped Organization items and returns a list of Organization instances.
    Args:
        org_structure_items:
    
    Returns:

    
`process_scraped_people_items(people_items) ‑> list[academic_crawler.scrapers.templates.Person]`
:   

Classes
-------

`ReferenceRawProcessor()`
:   This class processes the raw reference data and returns a list of Organization instances.

    ### Methods

    `load_raw(self, path)`
    :

    `process_affiliations(self, df: pandas.core.frame.DataFrame)`
    :

    `process_people(self, df: pandas.core.frame.DataFrame)`
    :

    `process_root_organization(self, df: pandas.core.frame.DataFrame, cols=('university_1', 'division'), meta=None)`
    :