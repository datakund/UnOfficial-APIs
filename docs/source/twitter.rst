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

