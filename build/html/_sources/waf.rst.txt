F5 BIG-IP AWAF on VNG Cloud

Make the app work first
-----------------------

Add the node (the web server)

.. image:: _static/waf/waf1.png

Create the pool (pool of web server)

.. image:: _static/waf/waf2.png

Make sure the health monitor works, the pool is up

.. image:: _static/waf/waf3.png

Create the virtual server (to receive traffic from clients)

.. image:: _static/waf/waf4.png

Source Address Translation = 'Auto Map'
Default Pool = 'word_press_server_pool'

.. image:: _static/waf/waf5.png

Make sure the virtual server is up and ready to serve clients

.. image:: _static/waf/waf6.png

See the statistics

.. image:: _static/waf/waf7.png

.. image:: _static/waf/waf8.png

Testing the website served by the WAF instance

.. image:: _static/waf/waf9.png

Check the statistics

.. image:: _static/waf/waf10.png

Create an Web Application Firewall Policy
-----------------------------------------
Overview

.. image:: _static/waf/waf14.png

Create the log profile

.. image:: _static/waf/waf15.png

.. image:: _static/waf/waf16.png

Create the policy

.. image:: _static/waf/waf11.png

.. image:: _static/waf/waf12.png

.. image:: _static/waf/waf17.png

.. image:: _static/waf/waf18.png

.. image:: _static/waf/waf19.png

Event Logs

.. image:: _static/waf/waf20.png

.. image:: _static/waf/waf21.png

Trying some funny things

.. image:: _static/waf/waf22.png

.. image:: _static/waf/waf23.png

Check the Event Logs again

.. image:: _static/waf/waf24.png

See the detail

.. image:: _static/waf/waf25.png

.. image:: _static/waf/waf26.png

Checkout more advance stuff

.. image:: _static/waf/waf27.png

.. image:: _static/waf/waf28.png

Congratulation! and do not forget to check out `F5 Networks official support page <https://support.f5.com/>`_

