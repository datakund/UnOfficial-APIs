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

This API will upload video, input:  video path, video title, video description, and file type.

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

