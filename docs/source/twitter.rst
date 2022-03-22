Twitter
******************************

Twitter - Scrape all Profile Tweets 
####################################

This twitter API will scrape all the tweets in the profile URL given in the input.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__tweets__from__profile(profile url='https://twitter.com/urstrulyMahesh')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__tweets__from__profile(profile url);

Twitter - Scrape Top Results
############################

This twitter API will scrape the top results of the given keyword.   

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__top__results(Search_Twitter='twenty')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__top__results(Search_Twitter);

Twitter - Profile URL Scraper
#############################

This twitter API, searches the keyword in the twitter and scrape all the profile details.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__search__profiles(Search_Twitter='mayor')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__search__profiles(Search_Twitter);

