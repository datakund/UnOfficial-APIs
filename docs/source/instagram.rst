Instagram
******************************

Login Bot
#########

It logins to instagram and linkedin

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.InstagramLogin(username='bhatiashikha@gmail.com',password='password',session_key='shikha@gmail.com',session_password='password')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.InstagramLogin(username,password,session_key,session_password);

Instagram - Watch Stories 
##########################

This API watches the story of the given profile.   

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram__stories__auto__watcher(profile url='https://www.instagram.com/ursulolita/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram__stories__auto__watcher(profile url);

Instagram - Search Results Scraper 
###################################

This API Scrapes all the results for the keyword given in the Instagram.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram__search__results(Search='urs')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram__search__results(Search);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "handle name": "manishmalhotra05",
            "url": "https://www.instagram.com/manishmalhotra05/"
        },
        {
            "handle name": "maniofcl",
            "url": "https://www.instagram.com/maniofcl/"
        },
        {
            "handle name": "hiramaniofficial",
            "url": "https://www.instagram.com/hiramaniofficial/"
        },
        {
            "handle name": "mani_rebel_edits",
            "url": "https://www.instagram.com/mani_rebel_edits/"
        },
        {
            "handle name": "call_me_mani_nisha",
            "url": "https://www.instagram.com/call_me_mani_nisha/"
        }
    ],
    "errors": "[]"
    }

