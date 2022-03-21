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