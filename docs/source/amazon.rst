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

Amazon - Select Payment Method
##############################

This API will click on the input passed.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_select_payment_method(payment_method='State Bank of India Debit Card')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_select_payment_method(payment_method);

Amazon - Select Bank
####################

This API will select the bank passed in the input.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_select_bank(bank='Airtel Payments Bank')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_select_bank(bank);

Amazon - Place Order
####################

API will click on "Place your Order" in amazon 

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_place_order()

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_place_order();

Amazon - Fill CVV
#################

This API will fill the CVV in amazon payment page.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_fill_cvv(CVV='w')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_fill_cvv(CVV);

Amazon - Product Info
#####################

This API scrapes product details of the product link given in input.

.. tabs::

   .. code-tab:: py

        #pip install bot_studio
        from bot_studio import *
        dk=bot_studio.new()
        dk.amazon_product_info(product_url='https://www.amazon.in/Airdopes-281-Bluetooth-Wireless-Earbuds/dp/B088FKY6KH/ref=sr_1_11?dchild=1&keywords=earpods&qid=1606564853&sr=8-11')

   .. code-tab:: javascript
		 NodeJS
   
         //npm i datakund
        var datakund=require('datakund');
        datakund.amazon_product_info(product_url);

**Response Data**

.. code-block:: json

    {
    "resume_variable": "0",
    "success_score": "92",
    "body": {
        "Description": "Aloe gel - the ultimate multi tasker If you were looking for that one multitasking hero that can work wonders for both your skin and hair \u2013 your search has finally come to an end! Say hello to our newest soothing aloe gel that can be used for pretty much all your skin and hair needs. From a mask, to a pre-moisturizer hydrator for your skin, and from a conditioner to a setting gel for your hair - this gel can really do it all!",
        "Price": "View Cart",
        "ReviewsLink": "https://www.amazon.in/Plum-Hello-Types-Multi-purpose-Fragrance/product-reviews/B08R8JF76B/ref=cm_cr_dp_d_show_all_btm?ie=UTF8&reviewerType=all_reviews",
        "Title": "Plum Hello Aloe Just Gel | For All Skin & Hair Types | Multi-purpose Aloe Vera gel | 100% Vegan | 100% Fragrance Free | 250 gm",
        "Features": "ULTIMATE MULTITASKING SKIN & HAIR GEL: Say hello to our soothing aloe gel for all skin types that can be used for pretty much all your skin and hair needs. From a mask, to a pre-moisturizer hydrator for your skin, and from a conditioner to a setting gel for your hair - this Aloe Vera gel can really do it all!    99% NATURAL ALOE EXTRACTS: Soothe your skin with this super Aloe Gel that calms your skin leaving a cooling sensation that lasts longer than you expected! 100% FRAGRANCE-FREE & COLOUR-FREE    HOW TO USE: Apply on freshly cleansed skin or hair to soothe, condition, hydrate & nourish. Pro tip: works as a great light natural styler for hair or primer under your makeup!    REAL PEOPLE, REAL RESULTS: 98% users agree that the aloe gel is a multi--tasker!* 8/10 users reported nourished & moisturized skin* 8/10 users felt a soothing effect on inflamed skin* 8/10 users reported frizz-free hair on application** *Self assessment study on 47 subjects **Self assessment study on 34 subjects    MADE WITH LOVE: FDA Approved | SLS Free | Cruelty-Free | Paraben Free | Sulphate-Free| For All Skin Types| For Men & Women | Use in All Seasons",
        "NoOfRatings": "3,081 ratings",
        "Offers": "Brief content visible, double tap to read full content.Full content visible, double tap to read brief content.        Offers     Previous page    Cashback   Amazon Pay Reward - Earn 10% cashback upto Rs. 200 on minimum purchase of \u20b9999 using Fi card. Valid only once per user.Amazon Pay Reward - Earn 10% cashback upto Rs.\u2026      8 offers\nCashbackOffer 1  Amazon Pay Reward - Earn 10% cashback upto Rs. 200 on minimum purchase of \u20b9999 using Fi card. Valid only once per user.  See details\nBack\nOffer 1   Amazon Pay Reward - Earn 10% cashback upto Rs. 200 on minimum purchase of \u20b9999 using Fi card. Valid only once per user.FAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nOffer 2  Amazon Pay Reward - Earn 10% cashback upto Rs. 150 on minimum purchase of \u20b9750 using Dhani OneFreedom Card. Valid only once per user.  See details\nBack\nOffer 2   Amazon Pay Reward - Earn 10% cashback upto Rs. 150 on minimum purchase of \u20b9750 using Dhani OneFreedom Card. Valid only once per user.FAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nOffer 3  Amazon Pay Reward - Earn 10% cashback upto Rs. 200 on minimum purchase of \u20b9500 using postpe card. Valid only once per user.  See details\nBack\nOffer 3   Amazon Pay Reward - Earn 10% cashback upto Rs. 200 on minimum purchase of \u20b9500 using postpe card. Valid only once per user.FAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nOffer 4  Amazon Pay Reward - Earn 10% cashback upto Rs 150 on minimum order of \u20b9500 using slice super card. Valid twice per user.  See details\nBack\nOffer 4   Amazon Pay Reward - Earn 10% cashback upto Rs 150 on minimum order of \u20b9500 using slice super card. Valid twice per user.FAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nOffer 5  Get 10% back up to \u20b9100 on using Amazon Pay UPI to pay for your transaction. No minimum order value. Valid once per customer during the offer period, applicable only on the Amazon app.  See details\nBack\nOffer 5   Get 10% back up to \u20b9100 on using Amazon Pay UPI to pay for your transaction. No minimum order value. Valid once per customer during the offer period, applicable only on the Amazon app.FAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nOffer 6  Amazon Shopping  See details\nBack\nOffer 6   Amazon ShoppingFAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nOffer 7  Get rewards up to \u20b91850 on card approval + 5% back on this product with  Amazon Pay ICICI Bank credit card  for Prime members. 3% back for others.  See details\nBack\nOffer 7   Get rewards up to \u20b91850 on card approval + 5% back on this product with  Amazon Pay ICICI Bank credit card  for Prime members. 3% back for others.FAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nOffer 8  Earn flat \u20b9200 back. Activate now & get \u20b9150 back. And get extra \u20b950 back when you shop with Amazon Pay Later. T&C apply. Check eligibility  See details\nBack\nOffer 8   Earn flat \u20b9200 back. Activate now & get \u20b9150 back. And get extra \u20b950 back when you shop with Amazon Pay Later. T&C apply. Check eligibilityFAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nFAQsWhen will I get the cashback in Amazon Pay balance?Subject to the terms and conditions of each offer, Amazon Pay balance will get added directly to the eligible customer's account within 72 hours post shipment of the product. Amazon Pay balance can be viewed at https://www.amazon.in/gp/payment/statementIf your order is delivered to you in multiple shipments, the cashback would be credited proportionately as each shipment is delivered to you. Example: If you buy two items A of Rs. 600 and B of Rs. 400 in the same cart and you are eligible for cashback in Amazon Pay balance for Rs.100 and the items get shipped separately, you will receive cashback of Rs. 60 when item A is delivered to you and Rs. 40 when item B is delivered to you.\nWhere can I see if I have got the cashback in Amazon Pay balance?Eligible customers can check the credit received on their Amazon.in account under their Balance Statement when they sign in to their registered account. Please note that the account that gets the credit will be the same account that purchased the product, and this cannot be transferred or exchanged.\nWhen can I use the cashback in Amazon Pay balance?The cashback in Amazon Pay balance can be used once it has been credited to the account. This would be within 72 hours after the product ships.\nIs there any limit to the number of cashbacks I can get?There is no explicit limit on the total value of cashback in Amazon Pay balance that a customer can get; however, cashback in Amazon Pay balance is available only on a select number of products and subject to the terms and conditions of each offer. For each purchase of these eligible products with adhering to the minimum threshold, a separate credit in Amazon Pay balance will be done.\nCan I redeem the cashback in Amazon Pay balance for cash?No, Amazon Pay balance cannot be redeemed or exchanged for cash.\nWhat happens if I return a product which had a cashback in Amazon Pay balance?If the cashback in Amazon Pay balance has been credited to your account, it will not be cancelled if you return the product. When you return the product, the remaining value net of the cashback amount will be refunded to you based on the payment method. Please note that if the product is refused at delivery, for a prepaid order, this would be considered similar to a return\nIs the cashback in Amazon Pay balance the same as any bank Cashbacks that are run on the website?Cashback in Amazon Pay balance is different from, and in addition to, the Bank cashbacks that are being advertised during the festive season. You can be eligible for both if you purchase a product that has the cashback in Amazon Pay balance and is eligible for the bank cashback as well, subject to their terms and conditions.\nWhat happens if I changed my mind and cancelled the order for the product with cashback in Amazon Pay balance?If the product has not been shipped and the order is cancelled prior to the issuance of the credit, the cashback will not be issued and the full value of the product will be refunded to you.If the product is shipped and the order is cancelled post shipment, the cashback in Amazon Pay balance credited to the customer's account will not be cancelled and the refund amount to the customer will be net of the cashback value. Example: If you buy an item worth Rs.10000 and receive a cashback in Amazon Pay balance for Rs.1000 and you cancel the order post shipment, you will be entitled to receive only Rs.9000 as your refund amount. The Amazon Pay balance credited to your account will not be cancelled. Rs.9000 will be credited to the original payment instrument used during the order.\nTerms and ConditionsAs part of the promotional offer and subject to the offer specific terms and conditions, you will get a cashback credit in your Amazon Pay balance via an Amazon Gift Card. Amazon Pay balance is a sum of all the balances associated with gift cards in your Amazon account.Amazon Gift Cards (\"Gift Cards\") are issued by QwikCilver Solutions Private Limited (\"QwikCilver\"), a private limited company incorporated under the laws of India and can be redeemed on www.amazon.in or on the mobile site or mobile application thereof (collectively, \"Amazon.in\") across all eligible products available on Amazon.in, excluding ebooks and apps.These offer terms and conditions (\"General Offer Terms\") are in addition to the Amazon.in Conditions of Use & Sale to which you agree by using the Amazon.in website; the terms and conditions applicable for the Gift Card (\"Gift Card Terms\") issued by QwikCilver; and the offer specific terms and conditions available on the [product detail page] (\"Specific Offer Terms\"). To the extent the Amazon.in Conditions of Use & Sale are inconsistent with these Offer Terms; these Offer Terms will prevail with respect to the Offer only. To the extent the Gift Card Terms are inconsistent with these Offer Terms; these Offer Terms shall prevail with respect to the Offer only. To the extent the General Offer Terms are inconsistent with the Specific Offer Terms, the Specific Offer Terms will prevail.Subject to the Specific Offer Terms, the Gift Card will be sent to the registered email ID of the eligible Purchaser by Amazon within 72 hours from the shipment of the product and will reflect as Amazon Pay balance on the Purchaser's account.2Gift Cards, including the Amazon Pay balance will expire one year from the date of issuance by QwikCilver. Gift Cards cannot be used to purchase other gift cards. Gift Cards cannot be reloaded, resold, transferred for value or redeemed for cash, except to the extent required by law.\nPartner Offers   buy 2 get extra 5% off, buy 3 get extra 7% off, buy 4 get extra 10% off!buy 2 get extra 5% off, buy 3 get extra 7% off, buy 4 get\u2026      3 offers\nPartner OffersOffer 1  buy 2 get extra 5% off, buy 3 get extra 7% off, buy 4 get extra 10% off!  See details\nBack\nOffer 1   buy 2 get extra 5% off, buy 3 get extra 7% off, buy 4 get extra 10% off!         Offer 2  Earn 15% back upto \u20b9200 on minimum order of \u20b91000 using Stashfin card. Valid twice per user  See details\nBack\nOffer 2   Earn 15% back upto \u20b9200 on minimum order of \u20b91000 using Stashfin card. Valid twice per user         Offer 3  Get GST  invoice and save up to 28% on business purchases. Sign up for free  See details\nBack\nOffer 3   Get GST  invoice and save up to 28% on business purchases. Sign up for freeBank Offer   Get upto 5% Cashback on HDFC Bank Millennia Credit Cards.Get upto 5% Cashback on HDFC Bank Millennia Cr\u2026      7 offers\nBank OfferOffer 1  Get upto 5% Cashback on HDFC Bank Millennia Credit Cards.  See details\nBack\nOffer 1   Get upto 5% Cashback on HDFC Bank Millennia Credit Cards.How to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offerOffer 2  10%  Instant Discount up to INR 500 on Bank of Baroda Debit Card Transactions. Minimum purchase value INR 1500  See details\nBack\nOffer 2   10%  Instant Discount up to INR 500 on Bank of Baroda Debit Card Transactions. Minimum purchase value INR 1500How to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offerOffer 3  Get 10X CashPoints with HDFC Bank MoneyBack+ Credit Cards and 2X Reward Points with MoneyBack Credit Cards  See details\nBack\nOffer 3   Get 10X CashPoints with HDFC Bank MoneyBack+ Credit Cards and 2X Reward Points with MoneyBack Credit CardsHow to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offerOffer 4  10%  Instant Discount up to INR 500 on Bank of Baroda Credit Card Transactions. Minimum purchase value INR 2000  See details\nBack\nOffer 4   10%  Instant Discount up to INR 500 on Bank of Baroda Credit Card Transactions. Minimum purchase value INR 2000How to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offerOffer 5  10%  Instant Discount up to INR 500 on Federal Bank Debit Card Transactions. Minimum purchase value INR 2000  See details\nBack\nOffer 5   10%  Instant Discount up to INR 500 on Federal Bank Debit Card Transactions. Minimum purchase value INR 2000How to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offerOffer 6  10%  Instant Discount up to INR 500 on Federal Bank Credit Card Transactions. Minimum purchase value INR 2000  See details\nBack\nOffer 6   10%  Instant Discount up to INR 500 on Federal Bank Credit Card Transactions. Minimum purchase value INR 2000How to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offerOffer 7  5%  Instant Discount on HSBC Cashback Card Transactions  See details\nBack\nOffer 7   5%  Instant Discount on HSBC Cashback Card TransactionsHow to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offer\nHow to avail offerSelect eligible card at the time of checkoutNo promo code required to avail the offer\nNext page",
        "Review Terms": "There was a problem filtering reviews right now. Please try again later.",
        "Ratings": "4.1 out of 5"
    },
    "errors": "[]"
    }

