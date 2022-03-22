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

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "tweet": "",
            "comments": "",
            "retweets": "",
            "likes": ""
        },
        {
            "tweet": "So heart touching125 Year old Yoga Guru from Kashi, Swami Sivananda receives  Padma Shri for his immense contribution in the field of #Yoga#PadmaAwards #PeoplesPadma#PadmaAwards2022 #PadmaShri",
            "comments": "806",
            "retweets": "6,702",
            "likes": "35.2K"
        },
        {
            "tweet": "Padma Vibhushan conferred to General Bipin Rawat (Posthumous) for Civil Service. Daughters received the award on behalf of their late father (Our Hero). PM @narendramodi Ji has converted Palma Awards into People's Padma.\n#PeoplesPadma #PadmaAwards #PadmaAwards2022 #PadmaShri",
            "comments": "35",
            "retweets": "406",
            "likes": "2,907"
        },
        {
            "tweet": "Shri Konsam Ibomcha Singh is awarded Padma Shri. He is an expert in Doll and Toys making craft, a traditional craft of Manipur.PM @narendramodi Ji has converted Padma Awards into People's Padma.\n#PeoplesPadma #PadmaAwards #PadmaAwards2022 #PadmaShri",
            "comments": "11",
            "retweets": "43",
            "likes": "421"
        },
        {
            "tweet": "",
            "comments": "",
            "retweets": "",
            "likes": ""
        }
    ],
    "errors": "[]"
    }

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

Twitter - Scrape Profile Details 
#################################

This twitter URL, scrapes profile details when given profile URL.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__profile__scraper(profile url='https://twitter.com/PawanKalyan')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__profile__scraper(profile url);

