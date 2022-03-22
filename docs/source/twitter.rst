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

**Response Data**

.. code-block:: json

    {
    "resume_variable": "2",
    "success_score": "100",
    "body": [
        {
            "comments": "60",
            "profile url": "https://twitter.com/kdramashin",
            "description": "if your girl watches twenty five twenty one, that's not your girl bro. that's baek yijin's girl.",
            "profile name": "shin \u00b2\u2075\u00b2\u00b9",
            "profile handle": "16.8K",
            "retweets": "6,614",
            "likes": "16.8K"
        },
        {
            "comments": "68",
            "profile url": "https://twitter.com/ringer",
            "description": "In 2002, there was nothing cooler and more cutting edge than \u2018Blade II.\u2019 Twenty years later, there still might not be.\n@johnwilmeswords:",
            "profile name": "theringer.com",
            "profile handle": "Twenty years ago, Wesley Snipes and Guillermo del Toro paved the way for everything from the Marvel Cinematic Universe to \u2018Twilight\u2019",
            "retweets": "13",
            "likes": "68"
        },
        {
            "comments": "1,243",
            "profile url": "https://twitter.com/dramasmoments",
            "description": "\u2500 twenty-five twenty-one (2022)",
            "profile name": "\ufe0e \ufe0e",
            "profile handle": "1,243",
            "retweets": "371",
            "likes": "1,243"
        },
        {
            "comments": "6",
            "profile url": "https://twitter.com/Nonton_Kdrama",
            "description": "Business Proposal  Twenty Five Twenty One. #BusinessProposal #BusinessProposalEp7 #TwentyFiveTwentyOne",
            "profile name": "Nonton Drakor",
            "profile handle": "8,546",
            "retweets": "3,593",
            "likes": "8,546"
        },
        {
            "comments": "1",
            "profile url": "https://twitter.com/kimtaeri_ifc",
            "description": "Dalam rangka ulang tahun Kim Taeri tanggal 24 April 2022.Kami berencana mengirimkan ucapan selamatsekalian Congratulation Gift \"Twenty Five Twenty One\" yang sudah selesai tayang.\n#KimTaeri #TwentyFiveTwentyOne #ProjectForTaeri",
            "profile name": "Kim Tae Ri Indonesia \uae40\ud0dc\ub9ac",
            "profile handle": "89",
            "retweets": "43",
            "likes": "89"
        }
    ],
    "errors": "[]"
    }

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

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": [
        {
            "name": "NYC Mayor's Office",
            "description": "Live from City Hall and the greatest city in the world. The team of @NYCMayor Eric Adams",
            "handle ": "@NYCMayorsOffice",
            "url": "https://twitter.com/NYCMayorsOffice"
        },
        {
            "name": "Mayor Muriel Bowser",
            "description": "Official account of the Mayor of Washington, DC. Together, let's work to give every Washingtonian a #FairShot. Tweets from Mayor Bowser signed MMB.",
            "handle ": "@MayorBowser",
            "url": "https://twitter.com/MayorBowser"
        },
        {
            "name": "U.S. Mayors",
            "description": "The United States Conference of Mayors. Official non-partisan organization of cities 30,000 in population and larger, each represented by their mayor.",
            "handle ": "@usmayors",
            "url": "https://twitter.com/usmayors"
        },
        {
            "name": "DC Mayor's Office",
            "description": "The Official Twitter Account of the Executive Office of @MayorBowser. Stay tuned for news and updates on the happenings from the Wilson Building and DC Govt.",
            "handle ": "@dcmayorsoffice",
            "url": "https://twitter.com/dcmayorsoffice"
        },
        {
            "name": "MAYOR",
            "description": "I DO COOL THINGS",
            "handle ": "@_MAYOR_",
            "url": "https://twitter.com/_MAYOR_"
        }
    ],
    "errors": "[]"
    }

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

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "following ": "260",
        "profile name": "Pawan Kalyan",
        "profile handle": "@PawanKalyan",
        "followers": "4.7M",
        "description ": "Jai Hind !!",
        "joined": "Joined August 2014"
    },
    "errors": "[]"
    }

