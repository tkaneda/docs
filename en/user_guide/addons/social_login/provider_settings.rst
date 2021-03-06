************************
Social Network Providers
************************

Manage the list of social network providers available in your store under **Website → Social login**. Customers can log in on you store using these providers.

.. important::

    The **Social login** section will appear under **Website** only if you activate **Social login** under **Add-ons → Manage add-ons**.

Use the **+ button** in the top right corner of a page to add new provider or click the **gear button** of the particular provider and choose the required action to edit or delete it.
 
When you add or edit a provider, you can see the following settings. The list of settings can vary depending on a provider:

* **Provider**—choose the social network provider. The button for registration via this provider will be added to the user's sign in form.

* **Status**—the status of the provider in your store—*Active* or *Disabled*.

==========================
Provider-Specific Settings
==========================

When you select a provider, additional settings will appear. This is the list of provider-specific settings:

------
Google
------

* **ID**—the identificator given to you after creating a project at `Google.com <https://code.google.com/apis/console/?pli=1>`_.

* **Secret key**—Secret key given to you after creating a project at `Google.com <https://code.google.com/apis/console/?pli=1>`_.

* **Callback URL**—URL that Google will use for the callback in case of successful authorization.

`Learn more about Googe integration <https://hybridauth.github.io/hybridauth/userguide/IDProvider_info_Google.html>`_ in HybridAuth User Guide.

--------
Facebook
--------

* **ID**—the **App ID** given to you after creating an application at `Facebook.com <https://developers.facebook.com/apps>`_.

* **Secret key**—Secret key given to you after creating an application at `Facebook.com <https://developers.facebook.com/apps>`_.

.. important::

    To finish the setup you need to go to `Facebook.com <https://developers.facebook.com/apps>`_. Open your app page, and switch to the **Facebook Login**. At this tab disable the **Use Strict Mode for Redirect URIs** option, or in the **Valid OAuth redirect URIs** field enter the **URI** such as [STORE_URL]/index.php?dispatch=auth.process&hauth_done=Facebook. For example, https://domain.com/index.php?dispatch=auth.process&hauth_done=Facebook

`Learn more about Facebook integration <https://hybridauth.github.io/hybridauth/userguide/IDProvider_info_Facebook.html>`_ in HybridAuth User Guide.

------
PayPal
------

* **ID**—the App ID given to you after the creating an application at PayPal.

* **Secret key**—the secret key given to you after creating an application at PayPal.

* **Use seamless checkout**—tick this checkbox to allow customers seamlessly checkout with PayPal without the need to log in to PayPal again. `Learn more about seamless checkout <https://developer.paypal.com/docs/integration/direct/identity/seamless-checkout/>`_ at Paypal Developer Portal.

* **Test mode**—tick this checkbox, if you want the PayPal payments functionality work in test mode.

* **Callback URL**—the URL that PayPal will use for the callback in case of successful authorization.

-------
Twitter
-------

* **ID**—the consumer key given to you after creating an application at `Twitter.com <https://dev.twitter.com/apps>`_.

* **Secret key**—the secret key given to you after creating an application at `Twitter.com <https://dev.twitter.com/apps>`_.

* **Callback URL**—the URL that Twitter will use for the callback in case of successful authorization.

`Learn more about Twitter integration <https://hybridauth.github.io/hybridauth/userguide/IDProvider_info_Twitter.html>`_ in HybridAuth User Guide.

-----
Yahoo
-----

* **ID**—the ID given to you after creating an application at `Yahoo.com <https://login.yahoo.com/config/login_verify2?.src=devnet&.done=http%3A%2F%2Fdeveloper.apps.yahoo.com%2Fdashboard%2FcreateKey.html>`_.

* **Secret key**—the secret key given to you after creating an application at `Yahoo.com <https://login.yahoo.com/config/login_verify2?.src=devnet&.done=http%3A%2F%2Fdeveloper.apps.yahoo.com%2Fdashboard%2FcreateKey.html>`_.

`Learn more about Yahoo integration <https://hybridauth.github.io/hybridauth/userguide/IDProvider_info_Yahoo.html>`_ in HybridAuth User Guide.

----
Live
----

* **ID**—the App ID given to you after the creating an application at Live.

* **Secret key**—the secret key given to you after creating an application at Live.

--------
LinkedIn
--------

* **ID**—the consumer key given to you after the creating an application at `LinkedIn.com <https://www.linkedin.com/uas/login?session_redirect=http%3A%2F%2Fwww%2Elinkedin%2Ecom%2FpostLogin%3Fsession_rikey%3Dfpu_41blh0jL5hJkp1eZZ9sPHEr45YEUV4Y9mIsCRy6PInlq-z1MZ80P05D13_1UL8q9F6xC0pCVI-QRVkVsI6WC2zNeWCBXYHa%26l%3Dhttps%253A%252F%252Fwww%252Elinkedin%252Ecom%252Fsecure%252Fdeveloper%26id%3D0%26b%3D959a9590-bca1-4fa1-8e52-6a663be18db3%26h%3DeWBL%26m%3DGET>`_.

* **Secret key**—the secret key given to you after creating an application at `LinkedIn.com <https://www.linkedin.com/uas/login?session_redirect=http%3A%2F%2Fwww%2Elinkedin%2Ecom%2FpostLogin%3Fsession_rikey%3Dfpu_41blh0jL5hJkp1eZZ9sPHEr45YEUV4Y9mIsCRy6PInlq-z1MZ80P05D13_1UL8q9F6xC0pCVI-QRVkVsI6WC2zNeWCBXYHa%26l%3Dhttps%253A%252F%252Fwww%252Elinkedin%252Ecom%252Fsecure%252Fdeveloper%26id%3D0%26b%3D959a9590-bca1-4fa1-8e52-6a663be18db3%26h%3DeWBL%26m%3DGET>`_.

`Learn more about LinkedIn integration <https://hybridauth.github.io/hybridauth/userguide/IDProvider_info_LinkedIn.html>`_ in HybridAuth User Guide.

----------
Foursquare
----------

* **ID**—the App ID given to you after creating an application at Foursquare.

* **Secret key**—the secret key given to you after creating an application at Foursquare.

`Learn more about Foursquare integration <https://hybridauth.github.io/hybridauth/userguide/IDProvider_info_Foursquare.html>`_ in HybridAuth User Guide.
