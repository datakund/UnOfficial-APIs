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

