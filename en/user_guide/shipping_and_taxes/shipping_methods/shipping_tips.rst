*****************************************************
How To: Specify a Commentary for all Shipping Methods
*****************************************************

.. note::

    This tutorial is primarily intended for CS-Cart & Multi-Vendor 4.3.7, as the behavior of the used language variable is different in earlier versions.

#. In the Administration panel, go to **Administration → Languages → Translations**.

   .. image:: img/translations.png
       :align: center
       :alt: Go to Administration → Languages → Translations.

#. Find the ``shipping_tips`` language variable.

   .. hint::

       You can use the search menu on the right to find the language variable you need.

#. Enter the desired value of the language variable.

#. Click **Save**.

   .. image:: img/shipping_tips.png
       :align: center
       :alt: Enter the text that you want to display for all shipping methods at the shipping method step.

#. If you go to checkout, you'll see the text that you entered.

   .. note::

       The value of the ``shipping_tips`` language variable will appear for all shipping methods.

   .. image:: img/tip_at_checkout.png
       :align: center
       :alt: The shipping tip will appear at checkout for all the shipping methods of your store.

   .. important::

       In CS-Cart & Multi-Vendor 4.3.5 and earlier the ``shipping_tips`` and ``delivery_times_text`` language variables contained a single description for all shipping methods in your store. These language variables didn't exist in CS-Cart & Multi-Vendor 4.3.6.

