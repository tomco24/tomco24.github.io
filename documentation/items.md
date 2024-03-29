Module academic_crawler.items
=============================

Classes
-------

`AcademicCrawlerItem(*args, **kwargs)`
:   Base class for scraped items.
    
    In Scrapy, an object is considered an ``item`` if it is an instance of either
    :class:`Item` or :class:`dict`, or any subclass. For example, when the output of a
    spider callback is evaluated, only instances of :class:`Item` or
    :class:`dict` are passed to :ref:`item pipelines <topics-item-pipeline>`.
    
    If you need instances of a custom class to be considered items by Scrapy,
    you must inherit from either :class:`Item` or :class:`dict`.
    
    Items must declare :class:`Field` attributes, which are processed and stored
    in the ``fields`` attribute. This restricts the set of allowed field names
    and prevents typos, raising ``KeyError`` when referring to undefined fields.
    Additionally, fields can be used to define metadata and control the way
    data is processed internally. Please refer to the :ref:`documentation
    about fields <topics-items-fields>` for additional information.
    
    Unlike instances of :class:`dict`, instances of :class:`Item` may be
    :ref:`tracked <topics-leaks-trackrefs>` to debug memory leaks.

    ### Ancestors (in MRO)

    * scrapy.item.Item
    * collections.abc.MutableMapping
    * collections.abc.Mapping
    * collections.abc.Collection
    * collections.abc.Sized
    * collections.abc.Iterable
    * collections.abc.Container
    * scrapy.utils.trackref.object_ref

    ### Class variables

    `fields: Dict[str, scrapy.item.Field]`
    :