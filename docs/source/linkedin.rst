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
        dk.linkedin___sent___requests___export()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___sent___requests___export();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "name": "Jim D.",
            "bio": "Wealth Coach at Disciplined Traders",
            "sent_time": "4 days ago",
            "profile_link": "https://www.linkedin.com/in/jim-d-45358/"
        },
        {
            "name": "Ryan Daws",
            "bio": "Wealth Coach at Disciplined Traders",
            "sent_time": "4 days ago",
            "profile_link": "https://www.linkedin.com/in/jim-d-45358/"
        },
        {
            "name": "Rachael Reid",
            "bio": "Wealth Coach at Disciplined Traders",
            "sent_time": "4 days ago",
            "profile_link": "https://www.linkedin.com/in/jim-d-45358/"
        },
        {
            "name": "Chris Comer",
            "bio": "Wealth Coach at Disciplined Traders",
            "sent_time": "4 days ago",
            "profile_link": "https://www.linkedin.com/in/jim-d-45358/"
        },
        {
            "name": "Megan Davis",
            "bio": "Wealth Coach at Disciplined Traders",
            "sent_time": "4 days ago",
            "profile_link": "https://www.linkedin.com/in/jim-d-45358/"
        }
    ],
    "errors": "[]"
    }

LinkedIn - Scrape Post Comments
###############################

This API scrapes the comments of the post.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___post___commenters(post_link='https://www.linkedin.com/posts/shikha-bhatia-713709154_programming-python-artificialintelligence-activity-6836184041318866944-erZY/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___post___commenters(post_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "commentor": "Simran Singh Bansal",
            "comment": "There are already many other scrappers available in the market which done the same job. How your tool is different from all others?"
        },
        {
            "commentor": "Jairaj Sahgal",
            "comment": "Wow, this looks awesome. Kudos to developers."
        }
    ],
    "errors": "[]"
    }

LinkedIn - Scrape Company URLs
##############################

This API searches a keyword and then filters with company and scrapes the data on single page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___company___url___finder(Search='amazon')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___company___url___finder(Search);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "company": "Amazon",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "24.7M followers",
            "type": "Internet \u2022 Seattle, WA"
        },
        {
            "company": "Amazon Web Services (AWS)",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "6.8M followers",
            "type": "Information Technology & Services \u2022 Seattle, WA"
        },
        {
            "company": "Amazon Ads",
            "companyurl": "https://www.linkedin.com/company/amazon/",
            "followers": "142K followers",
            "type": "Marketing & Advertising \u2022 Seattle, WA"
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
        }
    ],
    "errors": "[]"
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
        dk.linkedin___auto___unfollow()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___auto___unfollow();

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

LinkedIn - Scrape Activities 
#############################

This API scrapes profile activity when profile URL is given in the input. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___activities___extractor(profile_link='https://www.linkedin.com/in/muskan-goel-559bb7185/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___activities___extractor(profile_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": [
        {
            "profile name": "https://www.linkedin.com/company/andaaz-fashion/?miniCompanyUrn=urn%3Ali%3Afs_miniCompany%3A26669843",
            "post description": "I\u2019m #hiring. Know anyone who might be interested?#customerservice #customersupport #customersupportexecutive #customerservicejobs #customercareexecutive #customersupportjobs",
            "activity": "Status is offline\nMuskan Goel\n\u2022 3rd+\nHR Executive - Actively Hiring for Customer Service Executives\n4d \u2022\n4 days ago",
            "post date": "4d \u2022"
        },
        {
            "profile name": "https://www.linkedin.com/company/andaaz-fashion/?miniCompanyUrn=urn%3Ali%3Afs_miniCompany%3A26669843",
            "post description": "Must have an outfit in your wardrobe is Anarkali..Product Code: LSTV02550.For More Information Tap Below The Given Link:.https://lnkd.in/d4ucKus9.#fashionwithandaaz #ethnicwear #georgette #usa #andaazfashion",
            "activity": "Muskan Goel likes this",
            "post date": "5d \u2022"
        },
        {
            "profile name": "https://www.linkedin.com/company/andaaz-fashion/?miniCompanyUrn=urn%3Ali%3Afs_miniCompany%3A26669843",
            "post description": "Let\u2019s color our differences and water our dying hopes, Let\u2019s reunite and celebrate this festival of togetherness..Product code: LSTV01252 ,5128,2003.Shop Now.#fashionwithandaaz #holi #holifestivalofcolours #colors",
            "activity": "Muskan Goel likes this",
            "post date": "1w \u2022"
        },
        {
            "profile name": "https://www.linkedin.com/company/andaaz-fashion/?miniCompanyUrn=urn%3Ali%3Afs_miniCompany%3A26669843",
            "post description": "Tag women of your life who support you who inspires you and wish them Happy women's day.Product code: Dmv11089,2006,LSTV03436,LSTV01035.Get Extra 10% off on all Ethnic Wear.\u00a0Discount Code: NEW10.#fashionwithandaaz #womenempowerment #InternationalWomensDay2022",
            "activity": "Muskan Goel likes this",
            "post date": "1w \u2022"
        },
        {
            "profile name": "https://www.linkedin.com/company/andaaz-fashion/?miniCompanyUrn=urn%3Ali%3Afs_miniCompany%3A26669843",
            "post description": "I'm Still Not Over On This Lehenga With Jacket Fit.Product Code: 1946.For More Information Tap Below The Given Link:.https://lnkd.in/dECYAuvA.#FashionWithAndaaz #lehengacholi #usa #ethnicwear #andaazfashion",
            "activity": "Muskan Goel likes this",
            "post date": "2w \u2022"
        }
    ],
    "errors": "[]"
    }

LinkedIn - Auto Accept Invitations
##################################

This API accepts all the invitations received in your LinkedIn profile. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___accept___invitations()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___accept___invitations();

LinkedIn - Scrape Profile URLs
##############################

This API searches and scrapes the profile URLs for given keyword from the search results.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___profile___url___finder()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___profile___url___finder();

LinkedIn - Scrape Company Details
#################################

This API will scrape company details from the given LinkedIn company URL.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___companies___info(linkedin_url='chrome://new-tab-page/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___companies___info(linkedin_url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "employees_link": "https://chromeenterprise.google/",
        "followers": "39,672 followers",
        "profile_img_url": "https://media-exp1.licdn.com/dms/image/C4E0BAQEOyhqF9PPyYQ/company-logo_200_200/0/1595968418149?e=1655942400&v=beta&t=OLq8oZHb3u6OnmyT7BcHP1oSzwkidT-VUTEovw0hEMI",
        "cover_image_url": "https://media-exp1.licdn.com/dms/image/C4D1BAQH6MoETYkLdNg/company-background_10000/0/1595883574596?e=1647925200&v=beta&t=EpyymnxX-PkAhZEtpZI6QLLembhqqKpQa3SFogHcZrE",
        "about": "Google Chrome Enterprise provides the OS, browser, and devices your business needs to cloud-power your workforce.It empowers IT with the cloud-first, user-friendly business capabilities of Chrome OS, Chrome Browser, and Chrome\ndevices. For more than a decade, Google has provided the reliable and secure Chrome Browser. Now with t...see more\n... see more",
        "location": "39,672 followers",
        "type": "Information Technology & Services"
    },
    "errors": "[]"
    }

LinkedIn - Messenger  
######################

This API will message the profile when given profile name.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___message___sender(profile_link='https://www.linkedin.com/in/leilagharani/',Write_a_message='hope you are having a geat day')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___message___sender(profile_link,Write_a_message);

LinkedIn Bot - Scrape Connections
#################################

This LinkedIn API scrapes all the details of your connections when you enter cookies.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___contacts___extractor()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___contacts___extractor();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "name": "Charita Mavuri",
            "connect_ago": "Connected2 days ago",
            "image_link": "https://media-exp1.licdn.com/dms/image/C5603AQE6hETIWs2u3g/profile-displayphoto-shrink_100_100/0/1633835363303?e=1653523200&v=beta&t=P8zrVB13hHm3WmApKfaS4py7Ot_zWysLE8SdFGos0Xk",
            "title": "Automotive|Telematics|Infotainment|Electric Vehicle|CAN|CANoe|CANalyser",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "PARTH DESAI",
            "connect_ago": "Connected3 days ago",
            "image_link": "data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7",
            "title": "Automotive|Telematics|Infotainment|Electric Vehicle|CAN|CANoe|CANalyser",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "Bhagya Sree Vallu",
            "connect_ago": "Connected5 days ago",
            "image_link": "https://media-exp1.licdn.com/dms/image/C5603AQEeO6wrRunuig/profile-displayphoto-shrink_100_100/0/1627480990489?e=1653523200&v=beta&t=u7MGJtUhFzY7PbFvSLWuCK83jZmCNl11t82Kc8X-55E",
            "title": "Automotive|Telematics|Infotainment|Electric Vehicle|CAN|CANoe|CANalyser",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "Mounika kolli",
            "connect_ago": "Connected1 week ago",
            "image_link": "https://media-exp1.licdn.com/dms/image/C5603AQFDCUkvTsdAfQ/profile-displayphoto-shrink_100_100/0/1625849876907?e=1653523200&v=beta&t=kKt1mcvAVRYTJcdFmVEQ08JS9D1BgWbgLJbujcQdsrQ",
            "title": "Automotive|Telematics|Infotainment|Electric Vehicle|CAN|CANoe|CANalyser",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        },
        {
            "name": "suma t",
            "connect_ago": "Connected1 week ago",
            "image_link": "https://media-exp1.licdn.com/dms/image/C5103AQEiKtSaC91bUA/profile-displayphoto-shrink_100_100/0/1538296970796?e=1653523200&v=beta&t=NP-ryMGae5gEUkU2DNt2-ZbPBYQIcg-YO20M8XJbCb4",
            "title": "Automotive|Telematics|Infotainment|Electric Vehicle|CAN|CANoe|CANalyser",
            "profile_link": "https://www.linkedin.com/in/charita-mavuri/"
        }
    ],
    "errors": "[]"
    }

LinkedIn - Profile Scraper 
###########################

This LinkedIn API, scrapes profile details, when given profile URL in the input. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin___profile___scraper(profile_link='https://www.linkedin.com/in/ramaneffect/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin___profile___scraper(profile_link);

Linkedin Click on Next Page
###########################

It clicks on next button

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_click_next()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_click_next();

LinkedIn - login
################

This API will login LinkedIn, when given email ID and password in the input. 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_login()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_login();

LinkedIn - Job Profile Details
##############################

This LinkedIn API, will scrape job details when given "LinkedIn job Post URL" in the input

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_get_job_profile(job_link='https://www.linkedin.com/jobs/view/2303820097/?eBP=NotAvailableFromMidTier&refId=y8WRZ%2FI57CBKvwOuJPqq8w%3D%3D&trackingId=sdU1bdzpF7mMolPbdczmzQ%3D%3D&trk=flagship3_search_srp_jobs')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_get_job_profile(job_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "Industry": "November 9, 2020\nNovember 9, 2020\nNovember 9, 2020\nNovember 9, 2020\nNovember 9, 2020",
        "Company Name": "Apple",
        "Experience": "Summary",
        "Seniority Level": "",
        "Employment Type": "November 9, 2020",
        "Title": "Management Associate, Apple Media Services \u2013 India",
        "Published": "2 weeks ago",
        "Applicants": "Save Management Associate, Apple Media Services \u2013 India at Apple",
        "Roles": "Questions?\nVisit our Help Center.\nManage your account and privacy\nGo to your Settings.",
        "Job Functions": "Full-time\n10,001+ employees \u00b7 Computers and Electronics Manufacturing\nSee how you compare to 1,250 applicants. Try Premium for free\nActively recruiting",
        "Location": "Mumbai, Maharashtra, India"
    },
    "errors": "[]"
    }

LinkedIn - Search People
########################

This API will search a keyword given and applies people filter.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_search_people()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_search_people();

LinkedIn - Search Jobs
######################

This API will search a keyword given and applies jobs filter.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_search_jobs()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_search_jobs();

 LinkedIn - Search Posts
########################

This API will search a keyword given and applies posts filter.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_search_posts()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_search_posts();

LinkedIn - job Location
#######################

This API will search a keyword given and applies job filter.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_enter_job_location()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_enter_job_location();

Linkedin - Send Connection 
###########################

This API will send connect request to the profile URL given in the input.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_send_connection(profile_link='https://www.linkedin.com/in/vikas-gupta-56885b131')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_send_connection(profile_link);

LinkedIn - People Results
#########################

when opened a people search result page, this API will scrape all the profile URL in the page

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_people_results()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_people_results();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "Link": "/feed/?doFeedRefresh=true&nis=true"
        },
        {
            "Link": "https://www.linkedin.com/in/sasikiranreddy"
        },
        {
            "Link": "https://www.linkedin.com/in/darshan-kansagara"
        },
        {
            "Link": "https://www.linkedin.com/in/ruqaiyyah-khan-4bb29032"
        },
        {
            "Link": "https://www.linkedin.com/premium/products/?channel=AASAAN&upsellOrderOrigin=premium_people_search_usage_upsell&premiumFeatureType=SEARCH"
        }
    ],
    "errors": "[]"
    }

Linkedin - job Results
######################

This API, when opened job search results page, will scrape all the job URLs in the page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_jobs_results()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_jobs_results();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "Link": "/jobs/view/2946201792/?eBP=NotAvailableFromMidTier&recommendedFlavor=ACTIVELY_HIRING_COMPANY&refId=DSc9jeAc6mCCO%2BG%2FvnDBeQ%3D%3D&trackingId=P5C9ghCGQHE%2FdyM8ZCkH5g%3D%3D&trk=flagship3_search_srp_jobs"
        },
        {
            "Link": "/jobs/view/2932825258/?eBP=NotAvailableFromMidTier&recommendedFlavor=ACTIVELY_HIRING_COMPANY&refId=DSc9jeAc6mCCO%2BG%2FvnDBeQ%3D%3D&trackingId=2PBtzRK3jPdHMPWOVsDb3A%3D%3D&trk=flagship3_search_srp_jobs"
        },
        {
            "Link": "/jobs/view/2971881518/?eBP=NotAvailableFromMidTier&recommendedFlavor=IN_NETWORK&refId=DSc9jeAc6mCCO%2BG%2FvnDBeQ%3D%3D&trackingId=EXbZiNsoRTvOPX9rZn5utg%3D%3D&trk=flagship3_search_srp_jobs"
        },
        {
            "Link": "/jobs/view/2946206006/?eBP=NotAvailableFromMidTier&recommendedFlavor=ACTIVELY_HIRING_COMPANY&refId=DSc9jeAc6mCCO%2BG%2FvnDBeQ%3D%3D&trackingId=BJA%2FsR9M0qjLsmxjKNY%2FuQ%3D%3D&trk=flagship3_search_srp_jobs"
        },
        {
            "Link": "/jobs/view/2942224540/?eBP=NotAvailableFromMidTier&recommendedFlavor=ACTIVELY_HIRING_COMPANY&refId=DSc9jeAc6mCCO%2BG%2FvnDBeQ%3D%3D&trackingId=XlpFzI5OKvKS3l7GswmqlA%3D%3D&trk=flagship3_search_srp_jobs"
        }
    ],
    "errors": "[]"
    }

LinkedIn - Posts Results
########################

When opened post search results page, this API will scrape all the posts details in that page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_posts_results()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_posts_results();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "61",
    "body": [
        {
            "User Link": "https://www.linkedin.com/feed/",
            "Post Text": "Home"
        },
        {
            "User Link": "https://www.linkedin.com/mynetwork/",
            "Post Text": "My Network"
        },
        {
            "User Link": "https://www.linkedin.com/jobs/",
            "Post Text": "Jobs"
        },
        {
            "User Link": "https://www.linkedin.com/messaging/",
            "Post Text": "Messaging"
        },
        {
            "User Link": "https://www.linkedin.com/notifications/",
            "Post Text": "Notifications"
        }
    ],
    "errors": "[\"'href'\"]"
    }

LinkedIn - Comment on Post
##########################

This API will comment on the post, when given post URL and comment to post in the input.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_comment_on_post(post_link='https://www.linkedin.com/posts/jobs44you_covid19-covid-activity-6733590442660782080-YL9r',comment='a')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_comment_on_post(post_link,comment);

LinkedIn - Message Scraper
##########################

When given profile URL, bot scrapes all the messages.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_get_messages(profile_link='https://www.linkedin.com/in/shikha-bhatia-713709154')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_get_messages(profile_link);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "100",
    "body": {
        "Messegetext": "Amazon Robotics\nComputer Software\n89,564 followers\nFollow\nBoston Dynamics\nComputer Software\n341,804 followers\nFollow\nSharkNinja\nConsumer Goods\n40,194 followers\nFollow"
    },
    "errors": "[]"
    }

LinkedIn - Search Companies
###########################

When given a input keyword, the API will search the keyword in Linkedin and apply companies filter.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.linkedin_search_companies()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.linkedin_search_companies();

