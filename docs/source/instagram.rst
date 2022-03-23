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

Instagram - Scrape all the tagged post URL 
###########################################

This API will scrape all the tagged post URL, when given profile URL in the input. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.insta__tagged__url(profile url='https://www.instagram.com/9gag/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.insta__tagged__url(profile url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": [
        {
            "pst url": "https://www.instagram.com/p/BqkyuXbBNzX/"
        },
        {
            "pst url": "https://www.instagram.com/p/BqS7c0IBj1B/"
        },
        {
            "pst url": "https://www.instagram.com/p/BU1S34nF4-G/"
        },
        {
            "pst url": "https://www.instagram.com/p/BKA9231hre4/"
        },
        {
            "pst url": "https://www.instagram.com/p/e8GvQXEH7Y/"
        }
    ],
    "errors": "[]"
    }

Instagram - Auto Comment Post
#############################

This API when given post URL and comment as input, the bot will visit the post and auto comment the post. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram__auto__commentor(post url='https://www.instagram.com/9gag/',Add_a_comment='nice')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram__auto__commentor(post url,Add_a_comment);

