Module academic_crawler.helpers.evaluation
==========================================

Classes
-------

`EntityInstanceMatcher()`
:   

    ### Methods

    `add_instances(self, instances, ref_instances)`
    :

    `compare_affiliations(self)`
    :

    `compare_orgs(self)`
    :

    `compare_people(self)`
    :

    `filter_people(self)`
    :

    `generate_confusion_matrix(self, matches)`
    :

    `match_org(self, org, index=-1)`
    :

    `match_person(self, person, index=-1)`
    :

`Evaluator(results_file, reference_file)`
:   

    ### Methods

    `affiliations_in_reference(self, person, person_ref)`
    :

    `build_hierachical_tree(self, data: list[academic_crawler.scrapers.templates.Person], main_org: academic_crawler.scrapers.templates.Organization)`
    :

    `build_levels(self, tree, root)`
    :

    `compare_levels(self, levels_res, tree_ref)`
    :

    `evaluate_found_people(self)`
    :

    `evaluate_matches(self, matches=None)`
    :

    `load_result_file(self, fname)`
    :

    `person_in_reference(self, person: academic_crawler.scrapers.templates.Person)`
    :