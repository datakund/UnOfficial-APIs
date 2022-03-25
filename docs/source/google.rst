Google
******************************

Google - Search
###############

This API will search keyword given in input, in google.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.google_search(Keyword='h')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.google_search(Keyword);

Google - Search Images
######################

It searches the keyword given in input on google and clicks images section

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.google_search_images(Keyword='h')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.google_search_images(Keyword);

Google - Click Next
###################

This google API, clicks on next on google search results page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.google_click_next()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.google_click_next();

Google - Search Results
#######################

This API scrapes the links and titles in the google search results page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.google_search_results()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.google_search_results();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "Title": "Linux cat command help and examples - Computer Hopehttps://www.computerhope.com \u203a Help \u203a Linux"
        },
        {
            "Desc": "Cached",
            "Title": "What is the difference between MAT and CAT exams? - Mbaroihttps://mbaroi.in \u203a blog \u203a what-is-the-difference-betwee...",
            "Link": "https://www.computerhope.com/unix/ucat.htm"
        },
        {
            "Desc": "Cached",
            "Link": "https://mbaroi.in/blog/what-is-the-difference-between-mat-and-cat-exams/"
        }
    ],
    "errors": "[]"
    }

