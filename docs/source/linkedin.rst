Linkedin
******************************

Linkedin Url Bot
################

It opens url.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedintest()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedintest();

LinkedIn - Sent Requests
########################

This API scrapes all the sent requests.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___sent___requests___export(cookies='cookies list')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___sent___requests___export(cookies);

LinkedIn - Scrape Post Comments
###############################

This API scrapes the comments of the post.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___post___commenters(cookies='cookies list',post_link='https://www.linkedin.com/posts/shikha-bhatia-713709154_programming-python-artificialintelligence-activity-6836184041318866944-erZY/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___post___commenters(cookies,post_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "6",
    "success_score": "98",
    "body": [
        {
            "commentor": "Terence Battles",
            "comment": "Do you think if I get a job there they could help me get my account back?  \ud83d\ude43\ud83d\ude02"
        },
        {
            "commentor": "Abhishek Balawan",
            "comment": "Hello Nathan, I am enthusiastic about working at @meta. Please go through my profile and let me know if I am suitable for any roles."
        },
        {
            "commentor": "Akshita Aggarwal",
            "comment": "Its my dream\u2764 maybe one day\u2764"
        },
        {
            "commentor": "Swatika Das",
            "comment": "Commenting for better reach"
        },
        {
            "commentor": "swati maurya",
            "comment": "Dreams \ud83e\udd72\ud83d\ude05but trying best to get this\ud83d\ude07"
        }
    ],
    "errors": "[\"'NoneType' object has no attribute 'replace'\"]"
    }

LinkedIn - Scrape Company URLs
##############################

This API searches a keyword and then filters with company and scrapes the data on single page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___company___url___finder(cookies='cookies list',Search='amazon')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___company___url___finder(cookies,Search);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "4",
    "success_score": "98",
    "body": [
        {
            "company": "Amazon",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "24.6M followers",
            "type": "Internet \u2022 Seattle, WA"
        },
        {
            "company": "Amazon Web Services (AWS)",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "6.8M followers",
            "type": "Information Technology & Services \u2022 Seattle, WA"
        },
        {
            "company": "Amazon Science",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "220K followers",
            "type": "Research \u2022 Seattle, Washington"
        },
        {
            "company": "Amazon Lab126",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "179K followers",
            "type": "Consumer Electronics \u2022 Sunnyvale, CA"
        },
        {
            "company": "Amazon Robotics",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "89.5K followers",
            "type": "Computer Software \u2022 North Reading, MA"
        }
    ],
    "errors": "[\"'NoneType' object has no attribute 'replace'\"]"
    }

LinkedIn - Scrape Followers Detailss
####################################

This API opens followers list and scrapes all details.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___followers___insights()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___followers___insights();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "name": "Charita Mavuri",
            "designation": "Automotive|Telematics|Infotainment|Electric Vehicle|CAN|CANoe|CANalyser",
            "followers": "146 followers",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "Charita Mavuri",
            "designation": "\ud83d\udcbbDigital Marketer\ud83d\udcf1Bulk Whatsapp #Bulkemailmarketing #Instagrammarketing #Facebookmarketing #Goggleadwords",
            "followers": "22 followers",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "Charita Mavuri",
            "designation": "Consultant at Deloitte India (Offices of the US)",
            "followers": "80 followers",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "Charita Mavuri",
            "designation": "Test Engineer at Tata Consultancy Services",
            "followers": "19 followers",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "Charita Mavuri",
            "designation": "Senior Digital Marketing Executive at Yellowka IQ",
            "followers": "2.1K followers",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        }
    ],
    "errors": "[]"
    }

LinkedIn - Event Inviter
########################

For a created event, this API should invite people from LinkedIn

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___event___inviter(event_link='https://www.linkedin.com/events/6907227782129307648/analytics/',Search_by_name='anand')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___event___inviter(event_link,Search_by_name);

LinkedIn - Scrape Companies Employees 
######################################

When given company URL, this API will scrape all the employee data available 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___companies___employees(Search='google')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___companies___employees(Search);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "name": "Namrata R.View Namrata R.\u2019s profile",
            "designation": "Human Resources",
            "city": "Hyderabad",
            "profile_link": "https://www.linkedin.com/in/namrata-r-664769b6?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAABisWmwBac7nP-N8JI1xdB7CrGg1SGhtOT0"
        },
        {
            "name": "Ibrahim AView Ibrahim A\u2019S profile",
            "designation": "Human Resources",
            "city": "Hyderabad",
            "profile_link": "https://www.linkedin.com/in/namrata-r-664769b6?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAABisWmwBac7nP-N8JI1xdB7CrGg1SGhtOT0"
        },
        {
            "name": "Ankit ParasharView Ankit Parashar\u2019s profile",
            "designation": "Human Resources",
            "city": "Hyderabad",
            "profile_link": "https://www.linkedin.com/in/namrata-r-664769b6?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAABisWmwBac7nP-N8JI1xdB7CrGg1SGhtOT0"
        },
        {
            "name": "Moulica BharadwajView Moulica Bharadwaj\u2019s profile",
            "designation": "Human Resources",
            "city": "Hyderabad",
            "profile_link": "https://www.linkedin.com/in/namrata-r-664769b6?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAABisWmwBac7nP-N8JI1xdB7CrGg1SGhtOT0"
        },
        {
            "name": "Diwakar S.View Diwakar S.\u2019s profile",
            "designation": "Human Resources",
            "city": "Hyderabad",
            "profile_link": "https://www.linkedin.com/in/namrata-r-664769b6?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAABisWmwBac7nP-N8JI1xdB7CrGg1SGhtOT0"
        }
    ],
    "errors": "[]"
    }

LinkedIn - Auto Withdrawal connect
##################################

This API goes to the withdraw section and removes withdraw.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___withdraw()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___withdraw();

LinkedIn - Auto Unfollow
########################

This API will unfollow the profile URL given

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___unfollow(cookies='cookies list',profile_link='https://www.linkedin.com/in/srushtigaur/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___unfollow(cookies,profile_link);

LinkedIn - Auto Unconnect Connections
#####################################

This API will go to LinkedIn connections and Unconnects them.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___unconnect()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___unconnect();

LinkedIn - Auto Post
####################

This API will Auto Post on LinkedIn when test to post.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___poster(What_do_you_want_to_talk_about='Hi everyone')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___poster(What_do_you_want_to_talk_about);

LinkedIn - Auto Like Post
#########################

When given profile URL, this API likes all the posts given.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___liker(company posts url='https://www.linkedin.com/company/entab-newdelhi/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___liker(company posts url);

LinkedIn - Auto Follow
######################

When given URL of a profile, this API will automatically follows the given profile.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___follow(profile link to follow='https://www.linkedin.com/in/nealpann/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___follow(profile link to follow);

LinkedIn - Auto Endorse
#######################

This API will go to a connect profiles of the profile URL given as input and auto endorse all the skills.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___endorse(profile_link='https://www.linkedin.com/in/deepakagnihotri19/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___endorse(profile_link);

LinkedIn - Auto Commenter 
##########################

This API goes to the profile posts and comments all the posts.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___auto___commenter___run(profile_link='https://www.linkedin.com/in/muskan-goel-559bb7185/',Add_a_comment='hi there nice post')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___commenter___run(profile_link,Add_a_comment);

