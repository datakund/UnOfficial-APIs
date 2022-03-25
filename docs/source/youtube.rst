Youtube
******************************

YouTube - Login
###############

This API will login Youtube through google. Inputs - username/ email and password

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_login(username='username',password='password')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_login(username,password);

YouTube - Login Cookies
#######################

This API will login YouTube through cookies. Inputs - YouTube login cookies.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_login_cookie(cookies='cookies list')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_login_cookie(cookies);

YouTube - Auto Like
###################

This API will like the YouTube Video. Input: YouTube video link

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_auto_like(video_url='https://www.youtube.com/watch?v=SUelbSa-OkA')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_auto_like(video_url);

YouTube - Auto Comment
######################

This API will comment on the YouTube video. Input: YouTube video link and comment.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_auto_comment(video_link='https://www.youtube.com/watch?v=4GnVDPD01as')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_auto_comment(video_link);

YouTube - Auto Subscribe
########################

This API will auto subscribe channel in YouTube. Inputs: YouTube channel link.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_auto_subscribe(channel_url='https://www.youtube.com/channel/UCR9sFzaG9Ia_kXJhfxtFMBA')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_auto_subscribe(channel_url);

YouTube - Watch Video
#####################

This API will watch video for n given seconds.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_watch_video(Video_Url='https://www.youtube.com/watch?v=SUelbSa-OkA',Time='')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_watch_video(Video_Url,Time);

YouTube - Video Upload
######################

This API will upload video, input:  video path, video title, video description, kid type, public or not and file type.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_upload(video_path='file path',title='d',description='d',kid_type='Yes, it's Made for Kids',type='Private')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_upload(video_path,title,description,kid_type,type);

YouTube - Upload to Playlist
############################

This API will upload video in playlist, inputs: video path, playlist name, file type, kids.... 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_upload_to_playlist(video_path='file path',title='d',description='d',kid_type='Yes, it's Made for Kids',playlist='DataKund',type='Private')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_upload_to_playlist(video_path,title,description,kid_type,playlist,type);

YouTube - Search
################

This API will search a given keyboard in YouTube, Input: Keyword.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_search()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_search();

YouTube - Search Results
########################

This API will scrape video details on the search results.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_search_results()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_search_results();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "channel": "funnyplox\nfunnyplox\nVerified",
            "link": "https://www.youtube.com/watch?v=DXUAyRRkI6k",
            "title": "Funny Cats and Kittens Meowing Compilation",
            "viewsandtime": "446M views8 years ago"
        },
        {
            "channel": "Siti Nazihah\nSiti Nazihah",
            "link": "https://www.youtube.com/shorts/katD5xvV2t8",
            "title": "Cat crying",
            "viewsandtime": "19M views1 year ago"
        },
        {
            "channel": "Aww Animals\nAww Animals\nVerified",
            "link": "https://www.youtube.com/watch?v=ByH9LuSILxU",
            "title": "Baby Cats - Cute and Funny Cat Videos Compilation #34 | Aww Animals",
            "viewsandtime": "59M views1 year ago"
        },
        {
            "channel": "Talking Tom\nTalking Tom\nVerified",
            "link": "https://www.youtube.com/watch?v=jvkW1MKSyOc",
            "title": "ALL Talking Tom Shorts - Hyper Marathon",
            "viewsandtime": "571M views4 years ago"
        },
        {
            "channel": "Natural World Triumph\nNatural World Triumph\nVerified",
            "link": "https://www.youtube.com/watch?v=2MP5Ov_H4Go",
            "title": "Funny Cats and Kittens Meowing Sound Effects Compilation 2022",
            "viewsandtime": "71M views1 year ago"
        }
    ],
    "errors": "[]"
    }

YouTube - Get Video Info
########################

This API will get the video details, input: YouTube video URL.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_get_video_info(Video_Url='https://www.youtube.com/watch?v=SUelbSa-OkA')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_get_video_info(Video_Url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "ChannelLink": "https://www.youtube.com/channel/UCVUdHi-tdW5AKdzMiTPG97Q",
        "Desc": "Here is a video of cats and kittens meowing to confuse your pets\nPuppies & Babies & Kitties OH MY! New videos all the time!\n\ud83d\udc49 Subscribe: https://www.tinyurl.com/funnyplox\ud83d\udc49 Twitch: https://www.twitch.tv/funnyplox\ud83d\udc49 Submit: http://www.funnyplox.com/submit\nIf you see a clip that you own that you did not submit or give consent for use, we have likely received false permissions and would be happy to resolve this for you!Please drop us a line at info(@)funnyplox.com\n\ud83d\udc36\ud83d\udc76\ud83c\udffb\ud83d\udc31\n\ud83d\udc49 For every 100 likes, new puppies and kittens are born!\n#cats #funny #funnycatvideos",
        "Views": "446,914,041 views",
        "ChannelName": "funnyplox",
        "DisLikes": "Dislike",
        "Comments": "6,540 Comments",
        "Title": "Funny Cats and Kittens Meowing Compilation",
        "Duration": "4:22",
        "Likes": "1.7M",
        "Subscribers": "5.69M subscribers",
        "Publish_Date": "10 Nov 2013"
    },
    "errors": "[]"
    }

YouTube - Get Channel Info
##########################

This API will get the channel details, input: YouTube channel URL.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_get_channel_info(channel_link='https://www.youtube.com/c/zeenews/about')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_get_channel_info(channel_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "subscribers": "5.69M subscribers",
        "joined": "",
        "description": "This funny dog got lost in the rug. Hide and seek champion dog video! Thisfunny dog hid from its owner and could not be found.\nPuppies & Babies & Kitties OH MY! New videos all the time!\n\ud83d\udc49 Subscribe: https://www.tinyurl.com/funnyplox\ud83d\udc49 Submit: http://www.funnyplox.com/submit\nIf you see a clip that you own that you did not submit or give consent foruse, we have likely received false permissions and would be happy to resolve this for you! Please drop us a line at info(@)funnyplox.com\n\ud83d\udc36\ud83d\udc76\ud83d\udc31\n\ud83d\udc49 For every 100 likes, new puppies and kittens are born!\n#funnydog #dogvideos #dog",
        "location": "",
        "links": [
            "https://www.youtube.com/playlist?list=PLvKo-7UxiUK5a-8MTfoo3ffeFvRIpy6bx",
            "https://www.youtube.com/playlist?list=PLvKo-7UxiUK5a-8MTfoo3ffeFvRIpy6bx",
            "https://www.youtube.com/watch?v=Jgf19L_mbiY&list=PLvKo-7UxiUK5a-8MTfoo3ffeFvRIpy6bx"
        ],
        "title": "funnyplox",
        "views": ""
    },
    "errors": "[]"
    }

YouTube - Get Transcript 
#########################

This API will scrape the transcript of video given, input : video URL

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_get_transcript(Video_Url='https://www.youtube.com/watch?v=zIwLWfaAg-8')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_get_transcript(Video_Url);

YouTube - Get Playlist Videos
#############################

This API scrapes link and title of the videos in the playlist passed in playlist_link.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_get_playlist_videos(playlist_link='https://www.youtube.com/playlist?list=WL')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_get_playlist_videos(playlist_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "Title": "RRR - Audio Announcement | NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | M.M. Keeravaani",
            "Video_Link": "https://www.youtube.com/watch?v=a_1i3XCB7WY&list=PL4uyuv0FVO9wufaVJBzG_EP8BR7T63pDx&index=1&t=33s"
        },
        {
            "Title": "RRR - Audio Announcement | NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | M.M. Keeravaani",
            "Video_Link": "https://www.youtube.com/watch?v=dtZ14XTwwos&list=PL4uyuv0FVO9wufaVJBzG_EP8BR7T63pDx&index=2"
        },
        {
            "Title": "RRR - Audio Announcement | NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | M.M. Keeravaani",
            "Video_Link": "https://www.youtube.com/watch?v=Gt9WzC4WDEA&list=PL4uyuv0FVO9wufaVJBzG_EP8BR7T63pDx&index=3"
        },
        {
            "Title": "RRR - Audio Announcement | NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | M.M. Keeravaani",
            "Video_Link": "https://www.youtube.com/watch?v=VPT_EIo89cc&list=PL4uyuv0FVO9wufaVJBzG_EP8BR7T63pDx&index=4"
        },
        {
            "Title": "RRR - Audio Announcement | NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | M.M. Keeravaani",
            "Video_Link": "https://www.youtube.com/watch?v=xdpJWh5u-EI&list=PL4uyuv0FVO9wufaVJBzG_EP8BR7T63pDx&index=5"
        }
    ],
    "errors": "[]"
    }

YouTube - Get Video Tags
########################

This API scrapes the video tags and tag links whose video link is given in input.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_get_video_tags(video_link='https://www.youtube.com/watch?v=4GnVDPD01as')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_get_video_tags(video_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "taglinks": [
            "https://www.youtube.com/hashtag/komurambheemudo",
            "https://www.youtube.com/hashtag/rrrmovie",
            "https://www.youtube.com/hashtag/rrrsongs"
        ],
        "tags": "#KomuramBheemudo #RRRMovie #RRRSongs"
    },
    "errors": "[]"
    }

YouTube - Get Watch History
###########################

This API scrapes the title and link of the videos in watch history which is currently opened in browser.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_get_watch_history()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_get_watch_history();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "link": "/watch?v=qhWhxe7Wjv0"
        },
        {
            "title": "#RRR - usa lo \u0c0e\u0c28\u0c4d\u0c1f\u0c40\u0c06\u0c30\u0c4d \u0c2b\u0c3e\u0c28\u0c4d\u0c38\u0c4d || usa ntr fans hangamaa",
            "link": "/watch?v=esw2Wd0jfN0&t=34s"
        },
        {
            "title": "Bheemla Nayak Climax BGM | Bheemla Nayak Climax Fight BGM | Bheemla Nayak BGM Climax | Movie Mastiz",
            "link": "/watch?v=2ysvJBOglrA"
        },
        {
            "title": "Yazin Nizar about Dosti (Kannada) Song - RRR | M M Keeravaani | NTR, Ram Charan | SS Rajamouli",
            "link": "/watch?v=IckTwhYnk5c"
        },
        {
            "title": "Vijay Yesudas about Priyam - RRR | Maragathamani | NTR, Ram Charan, Ajay Devgn, Alia | SS Rajamouli",
            "link": "/watch?v=3GxXrCM6d7s"
        }
    ],
    "errors": "[]"
    }

YouTube - Channel Videos
########################

This API will scrape video details in the channel from page opened in browser.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_channel_videos()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_channel_videos();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "Video_Link": "/watch?v=nvJT6ymY8l4"
        },
        {
            "Title": "Mareyadha Haadugalu Jukebox | Vol 1 | P Kalinga Rao | Kuvempu | Kannada Folk Songs",
            "Video_Link": "/watch?v=TWQ2FCewRwo"
        },
        {
            "Title": "Mareyadha Haadugalu Jukebox | Vol 1 | P Kalinga Rao | Kuvempu | Kannada Folk Songs",
            "Video_Link": "/watch?v=Bd4uADxgoS0"
        },
        {
            "Title": "Mareyadha Haadugalu Jukebox | Vol 1 | P Kalinga Rao | Kuvempu | Kannada Folk Songs",
            "Video_Link": "/watch?v=HkCEdq4eYT8"
        },
        {
            "Title": "Mareyadha Haadugalu Jukebox | Vol 1 | P Kalinga Rao | Kuvempu | Kannada Folk Songs",
            "Video_Link": "/watch?v=wsdNabb8gNo"
        }
    ],
    "errors": "[]"
    }

YouTube - Watch Later Videos
############################

This API scrapes link and title of the videos in watch later list.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_watch_later_videos()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_watch_later_videos();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "Title": "RRR Trailer (Telugu) - NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | 25th March 2022",
            "Video_Link": "https://www.youtube.com/watch?v=Gt9WzC4WDEA&list=WL&index=1"
        },
        {
            "Title": "RRR Trailer (Telugu) - NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | 25th March 2022",
            "Video_Link": "https://www.youtube.com/watch?v=dtZ14XTwwos&list=WL&index=2"
        },
        {
            "Title": "RRR Trailer (Telugu) - NTR, Ram Charan, Ajay Devgn, Alia Bhatt | SS Rajamouli | 25th March 2022",
            "Video_Link": "https://www.youtube.com/watch?v=a_1i3XCB7WY&list=WL&index=3&t=33s"
        }
    ],
    "errors": "[]"
    }

YouTube - Check YouTube Exists
##############################

It returns title of video passed in video_url if exists, otherwise returns None in title

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_check_video_exists(video_url='https://www.youtube.com/watch?v=8sYK7838927')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_check_video_exists(video_url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "Title": "Naatu Naatu Song (Telugu)| RRR Songs NTR,Ram Charan | MM Keeravaani | SS Rajamouli|Telugu Songs 2021"
    },
    "errors": "[]"
    }

YouTube - Create Playlist
#########################

It creates new playlist with the name given in input variable. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_create_playlist()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_create_playlist();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "playlist_link": "https://www.youtube.com/playlist?list=PL1Hy5whX8xEkFIKVTwc2-U96-zpTMlAgk"
    },
    "errors": "[]"
    }

YouTube - Delete Video from Watch latter
########################################

It deletes the video whose title is passed in title from the watch later videos.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_delete_video_from_watch_later(title='')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_delete_video_from_watch_later(title);

YouTube - Find Click Video
##########################

It will click on the video whose title is passed in searchtext.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_find_click_video(searchtext='')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_find_click_video(searchtext);

YouTube - Play Pause Video
##########################

It play or pause the video playing currently on browser.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_play_pause_video()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_play_pause_video();

YouTube - Play Next Video
#########################

It clicks on next video to play next video

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_play_next_video()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_play_next_video();

YouTube - Forward Video
#######################

It forwards the video currently playing on browser with 5 seconds.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.youtube_forward_video()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.youtube_forward_video();

