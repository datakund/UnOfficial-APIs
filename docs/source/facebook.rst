Facebook
******************************

Facebook - Messenger
####################

This Facebook API when given a name and message, this bot will message automatically in Facebook. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.facebook__messenger(Send_message_to='mutyalu ',Message='hi')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.facebook__messenger(Send_message_to,Message);

Facebook - Auto like post
#########################

This API when given post URL, API will automatically like the post.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.facebook__auto__like__post(post url='https://www.facebook.com/groups/1367928843374571/permalink/2238410546326392/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.facebook__auto__like__post(post url);

