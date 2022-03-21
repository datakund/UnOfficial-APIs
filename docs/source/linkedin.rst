Linkedin
******************************

Linkedin Url Bot
################

It opens url.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedintest()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedintest();

LinkedIn - sent requests
########################

This bot scrapes all the sent requests.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___sent___requests___export(cookies='cookies list')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___sent___requests___export(cookies);

LinkedIn - Scrape Post Comments
###############################

This bot scrapes the comments of the post.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___post___commenters(cookies='cookies list',post_link='https://www.linkedin.com/posts/shikha-bhatia-713709154_programming-python-artificialintelligence-activity-6836184041318866944-erZY/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___post___commenters(cookies,post_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "80",
    "body": [
        {
            "commentor": "Stacey-Lee Anne Robberts",
            "comment": "Jelsa Covelli you make sense. I agree with you."
        }
    ],
    "errors": [
        "'NoneType' object has no attribute 'replace'"
    ]
    }

