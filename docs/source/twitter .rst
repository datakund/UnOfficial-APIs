Twitter 
******************************

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

