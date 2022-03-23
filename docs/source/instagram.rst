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
    "resume_variable": "n",
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

Instagram - Auto-Follow profiles
################################

This API will Auto-Follow Instagram profile, when given profile URL as input.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram_autofollow(profile url='https://www.instagram.com/9gag/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram_autofollow(profile url);

Instagram - Auto-Like Post
##########################

This Bot will Auto-Like post, when given post URL.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram_auto_like(post_url='https://www.instagram.com/p/CbEmdpwA1Zp/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram_auto_like(post_url);

Instagram - scrape hashtag post details 
########################################

This Instagram API, when given hashtag in input, it scrapes all the post details relating to it. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram_hashtag(Search='#hair')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram_hashtag(Search);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "11",
    "success_score": "100",
    "body": [
        {
            "post url": "https://www.instagram.com/p/Cbami9cM0XU/",
            "profile name": "thiscataura",
            "post description": "thiscatauraToo cute! \ud83d\ude3b\ud83d\ude0d @thiscatauraTag someone who would adopt them!\ud83d\udcf7: @waffle_n_bekko Follow @thiscatauraFollow @thiscatauraFollow @thiscataura-#catloversclub #catlove #catlover #cats #cat #catmemes #catnoir #cats_of_instagram #catmom #catsofig #catmodel #catsoftheday #cat_features #cats\ud83d\udc31 #catslover #catofinstagram #catphoto #catsagram #catscatscats #catolicos #cats_of_instworld #catlife9 h",
            "profile url": "https://www.instagram.com/thiscataura/"
        },
        {
            "post url": "https://www.instagram.com/p/Cbai8hBJKRI/",
            "profile name": "cat_moments_diary",
            "post description": "cat_moments_diaryNeed Dollar.$$$$$\ud83d\udcb5\ud83d\udc31Don't forget Like \ud83d\udc96 follow @cat_moments_diary ,Comment \ud83d\udcddfor more cute cats \ud83d\udc97and Follow me\ud83d\udc31...Share With Friends ..\ud83d\ude0dTag A Cat Lover \u2764\ufe0f\ud83d\udc31#CrazyCatLady #catloversclub #catsofinstagram #ilovemycat #instagramcats #nature #catoftheday #lovecats #furry #lovekittens #adorable #catlover #instacat #thedailykitten #cat #catsagram #dallascat #instagood #kitten #kitty #pet #animals #petstagram #photooftheday10 h",
            "profile url": "https://www.instagram.com/cat_moments_diary/"
        },
        {
            "post url": "https://www.instagram.com/p/CbbQ390MexE/",
            "profile name": "meowparlour",
            "post description": "meowparlourGatsby has a lot of opinions about the level of service he is getting here, and he is not afraid of voicing them.3 h",
            "profile url": "https://www.instagram.com/meowparlour/"
        },
        {
            "post url": "https://www.instagram.com/p/CbaPwRfqMHW/",
            "profile name": "the_most_spoiled_cat",
            "post description": "the_most_spoiled_cat\ud83c\uddee\ud83c\uddf9Un raggio di sole\u2600\ufe0fOgnuno ha qualcosa da scaldare nel suo cuore e da illuminare nella sua mente.\ud83c\uddec\ud83c\udde7A ray of sunshine\u2600\ufe0f...#prayforukraine #raggiodisole #primavera #gattoalsole #gatto #ilmiogatto #amoilmiogatto #cat #catlover #gattoitaliano12 h",
            "profile url": "https://www.instagram.com/the_most_spoiled_cat/"
        },
        {
            "post url": "https://www.instagram.com/p/CbbL_ikpsfe/",
            "profile name": "0308macka",
            "post description": "0308macka\u2601\u2601\u2601\u2601\u685c\u304c\u54b2\u304d\u59cb\u3081\u305f\u306e\u306b\u2026\u5bd2\u304f\u306a\u3044\u304b\uff1f\ud83c\udf38\ud83c\udf38\ud83c\udf38\ud83c\udf38\u305d\u3046\u306d\u3002\u3067\u3082\u305d\u3093\u306a\u306b\u843d\u3061\u8fbc\u307e\u306a\u3044\u3067\u3002\u9031\u672b\u306f\u304d\u3063\u3068\u6696\u304b\u304f\u306a\u3063\u3066\u685c\u3082\u6e80\u958b\u306b\u306a\u308b\u308f\u3088\u3002#\u306a\u3093\u3066\u8a71\u3057\u3066\u306f\u306a\u3044\u3060\u308d\u3046#cat_of_instagram #cat #mygreatcat #britishshorthair #britishshorthairs #\u30d6\u30ea\u30c6\u30a3\u30c3\u30b7\u30e5\u30b7\u30e7\u30fc\u30c8\u30d8\u30a2 #\u732b\u00a0 #\u30d6\u30ea\u30c6\u30a3\u30c3\u30b7\u30e5\u30b7\u30e7\u30fc\u30c8\u30d8\u30a2\u30fc#\u30d6\u30ea\u30b7\u30e7\u30fc #\u3076\u308a\u5546\u4f1a #whitecatsofinstagram #\u3057\u308d\u306d\u3053#\u306d\u3053\u3089\u90e8 #\u767d\u732b#\u732b\u597d\u304d\u3055\u3093\u3068\u7e4b\u304c\u308a\u305f\u3044 #cats #\u3075\u308f\u3082\u3053\u90e8 #ilovecats #catsofinstagram #\u732b\u306e\u3044\u308b\u66ae\u3089\u3057 #\u732b\u3068\u306e\u66ae\u3089\u3057 #\u732b\u597d\u304d\u306a\u4eba\u3068\u7e4b\u304c\u308a\u305f\u3044Edited\u00a0\u00b7\u00a04 h",
            "profile url": "https://www.instagram.com/0308macka/"
        }
    ],
    "errors": "[]"
    }

Instagram - Scrape Post Comments 
#################################

This API will Scrape comments on the Instagram post.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram__comments(post url='https://www.instagram.com/p/Ca7ytkwgRQQ/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram__comments(post url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "14",
    "success_score": "100",
    "body": [
        {
            "post likes": "2,288 likes",
            "post description": "Emotional damage",
            "title": "wayfarer_ys",
            "profile url": "https://www.instagram.com/wayfarer_ys/",
            "posted": "1 w"
        },
        {
            "post likes": "1,401 likes",
            "post description": "Wait you guys are going to offices \ud83d\ude02",
            "title": "shashikunwar",
            "profile url": "https://www.instagram.com/shashikunwar/",
            "posted": "1 w"
        },
        {
            "post likes": "511 likes",
            "post description": "Relatable \ud83d\ude02",
            "title": "iajabkhan",
            "profile url": "https://www.instagram.com/iajabkhan/",
            "posted": "1 w"
        },
        {
            "post likes": "531 likes",
            "post description": "That's most definitely going to be me",
            "title": "jc",
            "profile url": "https://www.instagram.com/jc/",
            "posted": "1 w"
        },
        {
            "post likes": "70 likes",
            "post description": "Dislike",
            "title": "judith___c",
            "profile url": "https://www.instagram.com/judith___c/",
            "posted": "1 w"
        }
    ],
    "errors": "[]"
    }

Instagram - Scrape profile details 
###################################

This API scrapes Instagram profile details, when given Instagram profile URL.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram__profile__scraper(profile url='https://www.instagram.com/9gag/tagged/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram__profile__scraper(profile url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "profile name": "9gag",
        "no of posts": "29,102",
        "followers": "58.2m",
        "description ": "9GAG: Go Fun The WorldApp PageBuilding Memeland, one meme at a time. Join our discord now\ud83d\udc47\ud83c\udffb discord.gg/memeland",
        "following": "30"
    },
    "errors": "[]"
    }

Instagram - Scrape all post URL in given profile 
#################################################

This API when given profile URL will scrape all the post URL in the given profile.  

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.instagram__profile__post(profile url='https://www.instagram.com/9gag/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.instagram__profile__post(profile url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "post url": "https://www.instagram.com/p/CbbVkSJPqDe/"
        },
        {
            "post url": "https://www.instagram.com/p/CbasU1-PA8k/"
        },
        {
            "post url": "https://www.instagram.com/p/CbZq7iCA-AD/"
        },
        {
            "post url": "https://www.instagram.com/p/CbY-Yy1NZym/"
        },
        {
            "post url": "https://www.instagram.com/p/CbYzC8QppiP/"
        }
    ],
    "errors": "[]"
    }

