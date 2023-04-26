Module academic_crawler.config.page_types
=========================================

Classes
-------

`PAGE_TYPE(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   An enumeration.

    ### Ancestors (in MRO)

    * enum.Enum

    ### Class variables

    `PAGE_GENERAL`
    :

    `PAGE_ORGANIZATIONS`
    :

    `PAGE_PEOPLE_DATA`
    :

    `PAGE_PEOPLE_NO_DATA`
    :

    `PAGE_SINGLE_PERSON`
    :

`PageTypeMatcher(to_exclude=[])`
:   

    ### Class variables

    `DEFAULT_DICT`
    :

    `NER_THRESHOLD_DEPARTMENT`
    :

    `NER_THRESHOLD_NAME`
    :

    `page_dict: dict`
    :

    ### Methods

    `check_page_type(self, page_type: academic_crawler.config.page_types.PAGE_TYPE, stage)`
    :

    `exclude_page_types(self, to_exclude)`
    :

    `get_condition_score(self, conditions, weights=None)`
    :

    `has_enough_ner(self)`
    :

    `is_org_site(self)`
    :

    `is_people_site(self)`
    :

    `solve_page_type(self)`
    :

    `update_page_dict(self, new_dict)`
    :