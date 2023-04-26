Module academic_crawler.scrapers.operations
===========================================

Sub-modules
-----------
* academic_crawler.scrapers.operations.general
* academic_crawler.scrapers.operations.org_structure
* academic_crawler.scrapers.operations.people

Functions
---------

    
`create_operation_result(func) ‑> academic_crawler.scrapers.operations.OperationResult`
:   

    
`get_op_status(expression, is_list=False)`
:   

    
`make_operation_message(type=None, status=None, has_information_data=False)`
:   

    
`op_failed(result: academic_crawler.scrapers.operations.OperationResult)`
:   

    
`op_success(result: academic_crawler.scrapers.operations.OperationResult)`
:   

Classes
-------

`OperationMessage(type: academic_crawler.config.enums.OperationType, status: academic_crawler.config.enums.OperationStatus, has_information_data: bool)`
:   OperationMessage(type: academic_crawler.config.enums.OperationType, status: academic_crawler.config.enums.OperationStatus, has_information_data: bool)

    ### Class variables

    `has_information_data: bool`
    :

    `status: academic_crawler.config.enums.OperationStatus`
    :

    `type: academic_crawler.config.enums.OperationType`
    :

`OperationResult(data: dict, message: academic_crawler.scrapers.operations.OperationMessage)`
:   OperationResult(data: dict, message: academic_crawler.scrapers.operations.OperationMessage)

    ### Class variables

    `data: dict`
    :

    `message: academic_crawler.scrapers.operations.OperationMessage`
    :