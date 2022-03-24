Amazon
******************************

Amazon - Login
##############

This API logins to the amazon through credentials passed in email and password. By default it logins to amazon.com, but you can login to others by passing login url in login_url.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_login(login_url='https://www.amazon.com/ap/signin?ie=UTF8&openid.pape.max_auth_age=0&openid.return_to=https%3A%2F%2Fwww.amazon.com%2Fgp%2Fcss%2Fhomepage.html%3Fref_%3Dnav_youraccount_switchacct&openid.identity=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.assoc_handle=usflex&_encoding=UTF8&openid.mode=checkid_setup&openid.claimed_id=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0&switch_account=signin&ignoreAuthState=1&disableLoginPrepopulate=1&ref_=ap_sw_aa',email='m',password='m')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_login(login_url,email,password);

Amazon - Logout
###############

This amazon API will logout of the amazon account.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_logout(home_url='https://www.amazon.com/')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_logout(home_url);

Amazon - Search
###############

This API will search a input keyword given in amazon.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_search(keyword='shoes')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_search(keyword);

Amazon - Select Brand
#####################

This API will select brand on the amazon search results page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_select_brand(Brand='Nike')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_select_brand(Brand);

Amazon - Select Category
########################

It selects the category passed in category when search is made.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_select_category(category='search-alias=stripbooks-intl-ship')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_select_category(category);

Amazon - Get Reviews
####################

It fetches the reviews data from reviews page opened in browser.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_get_reviews()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_get_reviews();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "100",
    "body": [
        {
            "Review Link": "https://www.amazon.com/gp/customer-reviews/RLDWZJJGF7Y6/ref=cm_cr_dp_d_rvw_ttl?ie=UTF8&ASIN=B018RLACN8",
            "Stars": "4.0 out of 5 stars",
            "Review": "Report abuse"
        },
        {
            "Review Link": "https://www.amazon.com/gp/customer-reviews/RQU9026HV9LKQ/ref=cm_cr_dp_d_rvw_ttl?ie=UTF8&ASIN=B018RLACN8",
            "Stars": "5.0 out of 5 stars",
            "Review": "Report abuse"
        },
        {
            "Review Link": "https://www.amazon.com/gp/customer-reviews/RZG5EBB72LY2T/ref=cm_cr_dp_d_rvw_ttl?ie=UTF8&ASIN=B018RLACN8",
            "Stars": "5.0 out of 5 stars",
            "Review": "Report abuse"
        },
        {
            "Review Link": "https://www.amazon.com/gp/customer-reviews/R1XTGP7LDLM05H/ref=cm_cr_dp_d_rvw_ttl?ie=UTF8&ASIN=B018RLACN8",
            "Stars": "4.0 out of 5 stars",
            "Review": "Report abuse"
        }
    ],
    "errors": "[]"
    }

Amazon - Add to Cart
####################

This Amazon API will add the product to cart, when given product url in the input

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_add_to_cart(product_link='https://www.amazon.in/boAt-BassHeads-100-Headphones-Black/dp/B071Z8M4KX/ref=sr_1_6?dchild=1&keywords=earphones&qid=1606549897&sr=8-6')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_add_to_cart(product_link);

Amazon - Search Result Scraper
##############################

It scrapes data from amazon search results page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_search_results()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_search_results();

**Response Data**

.. code-block:: json

    {
    "resume_variable": "n",
    "success_score": "91",
    "body": [
        {
            "link": "https://aax-eu.amazon.in/x/c/QuW1NdKNp5w9rH9-57vlOs4AAAF_ugM3bgMAAAH2AcEsG6A/https://www.amazon.in/stores/page/23268EDA-C09A-437E-9C65-8359CFB3776C/?_encoding=UTF8&store_ref=SB_A0498819YRLHHKAJWTNY&pd_rd_plhdr=t&aaxitk=b127485a01fb7184e3736bfbe0ee7f09&hsa_cr_id=4165156300502&lp_asins=B095PC3QPV%2CB08SW9W2FY%2CB08T1769X9&lp_query=bag&lp_slot=auto-sparkle-hsa-tetris&ref_=sbx_be_s_sparkle_lsi4d_logo&pd_rd_w=ht3e9&pf_rd_p=47ac07ef-304a-41df-a673-0b368707e6c6&pd_rd_wg=Rneg6&pf_rd_r=AR6ADH81F6QWKG8C92W8&pd_rd_r=54b43976-f6c5-458d-93b7-83e0df83867d",
            "title": "Shop Mokobara",
            "brand": "Shop Mokobara",
            "price": ""
        },
        {
            "link": "https://aax-eu.amazon.in/x/c/QuW1NdKNp5w9rH9-57vlOs4AAAF_ugM3bgMAAAH2AcEsG6A/https://www.amazon.in/stores/page/23268EDA-C09A-437E-9C65-8359CFB3776C/?_encoding=UTF8&store_ref=SB_A0498819YRLHHKAJWTNY&pd_rd_plhdr=t&aaxitk=b127485a01fb7184e3736bfbe0ee7f09&hsa_cr_id=4165156300502&lp_asins=B095PC3QPV%2CB08SW9W2FY%2CB08T1769X9&lp_query=bag&lp_slot=auto-sparkle-hsa-tetris&ref_=sbx_be_s_sparkle_lsi4d_ls&pd_rd_w=ht3e9&pf_rd_p=47ac07ef-304a-41df-a673-0b368707e6c6&pd_rd_wg=Rneg6&pf_rd_r=AR6ADH81F6QWKG8C92W8&pd_rd_r=54b43976-f6c5-458d-93b7-83e0df83867d",
            "price": "4,990."
        },
        {
            "title": "Sponsored",
            "brand": "Sponsored"
        },
        {
            "title": "Northzone Lightweight School Bags Backpacks for Boys Girls Stylish Men and Women Casual Travel Laptop Bag College Office (Navy Blue) 40L",
            "link": "https://www.amazon.in/gp/slredirect/picassoRedirect.html/ref=pa_sp_atf_aps_sr_pg1_1?ie=UTF8&adId=A05394663FX1LMT6O5MZL&url=%2FNorthzone-Polyester-School-Backpack-Compartment%2Fdp%2FB08678P2T7%2Fref%3Dsr_1_1_sspa%3Fcrid%3D32Y73OKYIPT8E%26keywords%3Dbag%26qid%3D1648093247%26sprefix%3Dbag%252Caps%252C294%26sr%3D8-1-spons%26psc%3D1&qualifier=1648093247&id=1860839822434776&widgetName=sp_atf",
            "price": "549"
        },
        {
            "title": "Northzone Anti Theft Backpack 15.6 Inch Laptop Bag with USB Charging Port and Water Resistant Fabric",
            "link": "https://www.amazon.in/gp/slredirect/picassoRedirect.html/ref=pa_sp_atf_aps_sr_pg1_1?ie=UTF8&adId=A0278458AD6C7QDE1FIA&url=%2FNorthzone-Backpack-Laptop-Charging-Resistant%2Fdp%2FB09LSDD7LY%2Fref%3Dsr_1_2_sspa%3Fcrid%3D32Y73OKYIPT8E%26keywords%3Dbag%26qid%3D1648093247%26sprefix%3Dbag%252Caps%252C294%26sr%3D8-2-spons%26psc%3D1&qualifier=1648093247&id=1860839822434776&widgetName=sp_atf",
            "price": "549"
        }
    ],
    "errors": "[\"'href'\"]"
    }

Amazon - Click Next 
####################

This API is automated to click next on the amazon search page

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_click_next()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_click_next();

Amazon - Auto Buy
#################

It goes to product url given as input and clicks on buy button.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_buy(product_url='https://www.amazon.in/boAt-BassHeads-100-Headphones-Black/dp/B071Z8M4KX/ref=sr_1_6?dchild=1&keywords=earphones&qid=1606552809&sr=8-6')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_buy(product_url);

