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

This API scrapes the comments of the post.

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
    "resume_variable": "6",
    "success_score": "98",
    "body": [
        {
            "commentor": "Terence Battles",
            "comment": "Do you think if I get a job there they could help me get my account back?  \ud83d\ude43\ud83d\ude02"
        },
        {
            "commentor": "Abhishek Balawan",
            "comment": "Hello Nathan, I am enthusiastic about working at @meta. Please go through my profile and let me know if I am suitable for any roles."
        },
        {
            "commentor": "Akshita Aggarwal",
            "comment": "Its my dream\u2764 maybe one day\u2764"
        },
        {
            "commentor": "Swatika Das",
            "comment": "Commenting for better reach"
        },
        {
            "commentor": "swati maurya",
            "comment": "Dreams \ud83e\udd72\ud83d\ude05but trying best to get this\ud83d\ude07"
        }
    ],
    "errors": "[\"'NoneType' object has no attribute 'replace'\"]"
    }

LinkedIn - Scrape Company URLs
##############################

This API searches a keyword and then filters with company and scrapes the data on single page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___company___url___finder(cookies='cookies list',Search='amazon')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___company___url___finder(cookies,Search);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "4",
    "success_score": "98",
    "body": [
        {
            "company": "Amazon",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "24.6M followers",
            "type": "Internet \u2022 Seattle, WA"
        },
        {
            "company": "Amazon Web Services (AWS)",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "6.8M followers",
            "type": "Information Technology & Services \u2022 Seattle, WA"
        },
        {
            "company": "Amazon Science",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "220K followers",
            "type": "Research \u2022 Seattle, Washington"
        },
        {
            "company": "Amazon Lab126",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "179K followers",
            "type": "Consumer Electronics \u2022 Sunnyvale, CA"
        },
        {
            "company": "Amazon Robotics",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "89.5K followers",
            "type": "Computer Software \u2022 North Reading, MA"
        }
    ],
    "errors": "[\"'NoneType' object has no attribute 'replace'\"]"
    }

