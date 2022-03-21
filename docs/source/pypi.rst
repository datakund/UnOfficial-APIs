Pypi
******************************

Pypi Results Scraper
####################

It scrapes results from pypi.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.pypi(Search_projects='firebase')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.pypi(Search_projects);

Response Data
##############

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "title": "firebase",
            "desc": "Python interface to the Google's Firebase REST APIs"
        },
        {
            "title": "python-firebase",
            "desc": "Python interface to the Firebase's REST API."
        },
        {
            "title": "parse2firebase",
            "desc": "UNKNOWN"
        },
        {
            "title": "arcane-firebase",
            "desc": "Utility functions for firebase"
        },
        {
            "title": "djangorestframework-firebase",
            "desc": "Firebase based authentication for Django REST framework"
        }
    ],
    "errors": []
    }

