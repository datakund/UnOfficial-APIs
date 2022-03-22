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

