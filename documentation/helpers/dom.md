Module academic_crawler.helpers.dom
===================================

Classes
-------

`ElementCategory(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   An enumeration.

    ### Ancestors (in MRO)

    * enum.Enum

    ### Class variables

    `CONTENT_SECTIONING`
    :

    `DEMARCATING_EDITS`
    :

    `DOCUMENT_METADATA`
    :

    `EMBEDDED_CONTENT`
    :

    `FORMS`
    :

    `IMAGE_AND_MULTIMEDIA`
    :

    `INLINE_TEXT_SEMANTICS`
    :

    `INTERACTIVE_ELEMENTS`
    :

    `MAIN_ROOT`
    :

    `OBSOLETE_AND_DEPRECATED_ELEMENTS`
    :

    `SCRIPTING`
    :

    `SECTIONING_ROOT`
    :

    `SVG_AND_MATHML`
    :

    `TABLE_CONTENT`
    :

    `TEXT_CONTENT`
    :

    `WEB_COMPONENTS`
    :

`ElementCategoryHelper()`
:   Helper class for element categories

    ### Methods

    `get_category(self, tag) ‑> (<enum 'ElementCategory'>, <class 'str'>)`
    :   Get the category of the tag
        Args:
            tag:

    `get_general_category(self, tag_name) ‑> academic_crawler.helpers.dom.ElementCategory`
    :

    `is_main_section(self, tag, category: academic_crawler.helpers.dom.ElementCategory) ‑> bool`
    :

    `is_nav_section(self, tag, category: academic_crawler.helpers.dom.ElementCategory) ‑> bool`
    :

    `is_textual(self, category: academic_crawler.helpers.dom.ElementCategory) ‑> bool`
    :   Check if the category is textual, e.g. its holds text value
        Args:
            category: