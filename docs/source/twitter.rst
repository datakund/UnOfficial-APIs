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
    "resume_variable": "0",
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
            "comments": "808",
            "retweets": "6,722",
            "likes": "35.3K"
        },
        {
            "tweet": "Padma Vibhushan conferred to General Bipin Rawat (Posthumous) for Civil Service. Daughters received the award on behalf of their late father (Our Hero). PM @narendramodi Ji has converted Palma Awards into People's Padma.\n#PeoplesPadma #PadmaAwards #PadmaAwards2022 #PadmaShri",
            "comments": "35",
            "retweets": "408",
            "likes": "2,914"
        },
        {
            "tweet": "Shri Konsam Ibomcha Singh is awarded Padma Shri. He is an expert in Doll and Toys making craft, a traditional craft of Manipur.PM @narendramodi Ji has converted Padma Awards into People's Padma.\n#PeoplesPadma #PadmaAwards #PadmaAwards2022 #PadmaShri",
            "comments": "11",
            "retweets": "43",
            "likes": "424"
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

Twitter - Auto like post  
##########################

This Twitter API, will auto like the post, when given post URL as input.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__like(tweet url='https://twitter.com/urstrulyMahesh/status/1501055580232110080')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__like(tweet url);

Twitter - Scrape Hashtag Posts 
###############################

This Twitter API, searches a hashtag and scrapes all the post details in search results.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__hashtag__posts(Search_Twitter='#cat')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__hashtag__posts(Search_Twitter);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "98",
    "body": [
        {
            "description": "",
            "profile name": "",
            "handle": "",
            "comments": "",
            "retweets": "",
            "likes": ""
        },
        {
            "description": "See top Tweets about these",
            "profile name": "See top Tweets about these",
            "handle": "See top Tweets about these",
            "comments": "Related Topic",
            "retweets": "Related Topic",
            "likes": "Related Topic"
        },
        {
            "comments": "Follow",
            "profile url": "https://twitter.com/i/topics/839543325212319744",
            "description": "Follow",
            "profile name": "Follow",
            "handle": "Animals",
            "retweets": "Follow",
            "likes": "Follow"
        },
        {
            "description": "",
            "profile name": "",
            "handle": "",
            "comments": "",
            "retweets": "",
            "likes": ""
        },
        {
            "comments": "71",
            "profile url": "https://twitter.com/kit_sox",
            "description": "Give me five  #cat #catlovers",
            "profile name": "KitNSox",
            "handle": "1,940",
            "retweets": "184",
            "likes": "1,940"
        }
    ],
    "errors": "[\"'href'\"]"
    }

Twitter - Scrape Following profiles 
####################################

This Twitter API scrapes all the following profiles when given a twitter profile URL in the input.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__followers(url='https://twitter.com/urstrulyMahesh')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__followers(url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "99",
    "body": [
        {
            "name": "KTR",
            "description": "Personal account of Working President of TRS | Minister for Municipal Admin & Urban Dev, Industry & Commerce, ITE&C | MLA from Siricilla, Telangana",
            "handle": "@KTRTRS",
            "url": "https://twitter.com/KTRTRS"
        },
        {
            "name": "rajamouli ss",
            "description": "film director",
            "handle": "@ssrajamouli",
            "url": "https://twitter.com/ssrajamouli"
        },
        {
            "name": "DEVI SRI PRASAD",
            "description": "Music Composer,Singer,Performer.. Composer of Dhinka Chika, Ringa Ringa, AaAnte Amalapuram,Daddy Mummy etc..",
            "handle": "@ThisIsDSP",
            "url": "https://twitter.com/ThisIsDSP"
        },
        {
            "name": "Anil Ravipudi",
            "description": "Film Writer & Director",
            "handle": "@AnilRavipudi",
            "url": "https://twitter.com/AnilRavipudi"
        },
        {
            "name": "BBC Earth",
            "description": "BBC Earth brings you face to face with nature, science & space.",
            "handle": "@BBCEarth",
            "url": "https://twitter.com/BBCEarth"
        }
    ],
    "errors": "[\"'href'\"]"
    }

Twitter - Auto Retweet Post 
############################

When given input URL of post, the API will automatically retweets it. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__auto__retweeter(tweet url='https://twitter.com/home')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__auto__retweeter(tweet url);

Twitter - Scrape Media Exporter 
################################

This API will go to twitter profile and scrape media section.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__media__extractor(profile url='https://twitter.com/MicrosoftIndia')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__media__extractor(profile url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "post description ": "Shri Konsam Ibomcha Singh is awarded Padma Shri. He is an expert in Doll and Toys making craft, a traditional craft of Manipur.PM @narendramodi Ji has converted Padma Awards into People's Padma.\n#PeoplesPadma #PadmaAwards #PadmaAwards2022 #PadmaShri",
            "post link": "https://twitter.com/KirenRijiju/status/1506187151330873350/photo/1"
        },
        {
            "post description ": "Shri Kaajee Singh \u2018Vidyaarthee\u2019 has been conferred with Padma Shri for promoting folk cultural music & for the growth of the instrument Shree Maadal.PM @narendramodi Ji has converted Padma Awards into People's Padma.\n#PeoplesPadma #PadmaAwards #PadmaAwards2022 #PadmaShri"
        },
        {
            "post description ": "On World Water Day, let\u2019s commit to save every drop of precious water. And join the Jal Jeevan Mission launched by hon'ble PM @narendramodi Ji to ensure water conservation and access to clean drinking water for our citizens.#WorldWaterDay"
        },
        {
            "post description ": "Tribal Communities of India no longer feel alienated. Hon\u2019ble Prime Minister Shri @narendramodi Ji's mantra of Sabka Saath, Sabka Vikas, Sabka Vishwas, Sabka Prayas has won the hearts and souls of all sections of the society.",
            "post link": "https://twitter.com/narendramodi"
        },
        {
            "post description ": "\u091c\u0928\u091c\u093e\u0924\u0940\u092f \u0917\u094c\u0930\u0935 \u0926\u093f\u0935\u0938!To give a befitting tribute to our brave Tribal Freedom Fighters PM Shri @narendramodi ji had declared 15th November, the birthday of Veer Birsa Munda as Janjatiya Gaurav Divas. #JanjatiyaGauravDivas",
            "post link": "https://twitter.com/KirenRijiju/status/1504857515598655494/photo/1"
        }
    ],
    "errors": "[]"
    }

Twitter - Auto message  
########################

When given twitter handle, this API messages in twitter.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.Twitter__Messenger(Search_people='shikha',input_0='hi')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.Twitter__Messenger(Search_people,input_0);

Twitter - Auto post  
#####################

This twitter API, Auto posts on twitter. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter__auto__post(Tweet_text='hello how are you',file_path_3='file path')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter__auto__post(Tweet_text,file_path_3);

Twitter - Login
###############

This Twitter API will login to twitter when given username and password.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter_login(username='m',password='ctrl+V')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter_login(username,password);

Twitter - Follow Profile
########################

When given profile URL in the input, this API will follow the profile.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter_follow(profile_url='https://twitter.com/aajtak')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter_follow(profile_url);

Twitter - Unfollow Profile
##########################

When given profile URL in the input, this API will unfollow the profile.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.twitter_unfollow(profile_url='https://twitter.com/narendramodi')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.twitter_unfollow(profile_url);

