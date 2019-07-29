AWS Cost Api Integrations using Python
===========

The purpose of this project is to get cost usage data from AWS costexplorer api using python.


How to run:
------------

Configure AWS credentials, SES_SEND, SES_REGION, SES_FROM:
    
    aws configure 
    
    

Run following commands:

    $ python report_script.py --months <month>
    
    Example 
    $ python report_script.py --months 6    	
