Module academic_crawler.scrapers.templates
==========================================

Sub-modules
-----------
* academic_crawler.scrapers.templates.websites

Classes
-------

`Affiliation(division: str, position: str = '')`
:   This class represents an affiliation entity.

    ### Class variables

    `division: str`
    :

    `position: str`
    :

    ### Static methods

    `from_dict(kvs: Union[dict, list, str, int, float, bool, ForwardRef(None)], *, infer_missing=False) ‑> ~A`
    :

    `from_json(s: Union[str, bytes, bytearray], *, parse_float=None, parse_int=None, parse_constant=None, infer_missing=False, **kw) ‑> ~A`
    :

    `schema(*, infer_missing: bool = False, only=None, exclude=(), many: bool = False, context=None, load_only=(), dump_only=(), partial: bool = False, unknown=None) ‑> dataclasses_json.mm.SchemaF[~A]`
    :

    ### Methods

    `to_dict(self, encode_json=False) ‑> Dict[str, Union[dict, list, str, int, float, bool, ForwardRef(None)]]`
    :

    `to_json(self, *, skipkeys: bool = False, ensure_ascii: bool = True, check_circular: bool = True, allow_nan: bool = True, indent: Union[int, str, ForwardRef(None)] = None, separators: Tuple[str, str] = None, default: Callable = None, sort_keys: bool = False, **kw) ‑> str`
    :

`Organization(name: str, domain: str, url: str, parent: Optional[ForwardRef('Organization')], abbreviation: str = '')`
:   This class represents an organization entity.

    ### Class variables

    `abbreviation: str`
    :

    `domain: str`
    :

    `name: str`
    :

    `parent: Optional[academic_crawler.scrapers.templates.Organization]`
    :

    `url: str`
    :

    ### Static methods

    `from_dict(kvs: Union[dict, list, str, int, float, bool, ForwardRef(None)], *, infer_missing=False) ‑> ~A`
    :

    `from_json(s: Union[str, bytes, bytearray], *, parse_float=None, parse_int=None, parse_constant=None, infer_missing=False, **kw) ‑> ~A`
    :

    `schema(*, infer_missing: bool = False, only=None, exclude=(), many: bool = False, context=None, load_only=(), dump_only=(), partial: bool = False, unknown=None) ‑> dataclasses_json.mm.SchemaF[~A]`
    :

    ### Methods

    `fix_url(self, url) ‑> tuple`
    :   This method fixes the url to fit Organization domain
        Args:
            url:
        
        Returns:

    `is_subdomain(self, url: str) ‑> bool`
    :   This method checks if the url is a subdomain of the organization domain
        Args:
            url:
        
        Returns:

    `to_dict(self, encode_json=False) ‑> Dict[str, Union[dict, list, str, int, float, bool, ForwardRef(None)]]`
    :

    `to_json(self, *, skipkeys: bool = False, ensure_ascii: bool = True, check_circular: bool = True, allow_nan: bool = True, indent: Union[int, str, ForwardRef(None)] = None, separators: Tuple[str, str] = None, default: Callable = None, sort_keys: bool = False, **kw) ‑> str`
    :

`Person(organization: academic_crawler.scrapers.templates.Organization, name: str, email: str = '', phone: str = '', url: str = '', affiliations: list[academic_crawler.scrapers.templates.Affiliation] = <factory>)`
:   This class represents a person entity.

    ### Class variables

    `affiliations: list[academic_crawler.scrapers.templates.Affiliation]`
    :

    `email: str`
    :

    `name: str`
    :

    `organization: academic_crawler.scrapers.templates.Organization`
    :

    `phone: str`
    :

    `url: str`
    :

    ### Static methods

    `from_dict(kvs: Union[dict, list, str, int, float, bool, ForwardRef(None)], *, infer_missing=False) ‑> ~A`
    :

    `from_json(s: Union[str, bytes, bytearray], *, parse_float=None, parse_int=None, parse_constant=None, infer_missing=False, **kw) ‑> ~A`
    :

    `schema(*, infer_missing: bool = False, only=None, exclude=(), many: bool = False, context=None, load_only=(), dump_only=(), partial: bool = False, unknown=None) ‑> dataclasses_json.mm.SchemaF[~A]`
    :

    ### Methods

    `add_affiliation(self, division, position=None)`
    :

    `add_implicit_affiliations(self)`
    :   This method adds an implicit affiliation to the person from its parent Organizations
        Returns:

    `to_dict(self, encode_json=False) ‑> Dict[str, Union[dict, list, str, int, float, bool, ForwardRef(None)]]`
    :

    `to_json(self, *, skipkeys: bool = False, ensure_ascii: bool = True, check_circular: bool = True, allow_nan: bool = True, indent: Union[int, str, ForwardRef(None)] = None, separators: Tuple[str, str] = None, default: Callable = None, sort_keys: bool = False, **kw) ‑> str`
    :