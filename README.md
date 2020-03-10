DrupalCommerce
==============

This module enables the use of http://www.cardstream.com payment gateway using the Drupal Commerce project http://www.drupalcommerce.org/

COMPATIBILITY
------------

Compatible with version 1.5 of Drupal Commerce. 

INTRODUCTION
------------

This module enables the drupal commerce customers to pay for their items using the cardstream hosted
form payment gateway.

What does it do?
----------------
Presents the option to pay with credit card or debit card via the cardstream payment
gateway.


INSTALLATION
------------

 1. Unzip / untar and copy the 'commerce_cardstream_hosted' folder into the modules directory
    usually: '/sites/all/modules/'. Advanced users may use wget or drush to complete this.

 2. Login into your drupal commerce install and enable the module under Administration -> Modules. The module will be in the group Commerce - Payment. To do this, check the box next to 'p3 Hosted Form' and click 'save configuration' at the bottom from the menu on the left hand side. 

 3. Hover over store settings at the top navigation bar and click on 'Payment Methods' from the drop down list. Find 'Debit or Credit Card (via p3 Form)' from the list and select edit. Enter your merchantID and Signature key. Click save.

OPERATION
---------

The module will write to the log if a payment fails the signature check.  This is something to look
out for as it could indicate tampering.


