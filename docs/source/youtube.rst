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

