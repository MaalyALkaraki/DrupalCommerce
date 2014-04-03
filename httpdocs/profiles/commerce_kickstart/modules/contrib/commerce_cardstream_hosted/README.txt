INTRODUCTION
------------

This module enables the drupal commerce customers to pay for their items using the Charity Clear hosted
form payment gateway.  

What does it do? 
----------------
Presents the option to pay with credit card or debit card via the charity clear payment
gateway.


INSTALLATION
------------

 1. Unzip / untar and copy the 'commerce_charityclear_hosted' folder into the modules directory
    usually: '/sites/all/modules/'. Advanced users may use wget or drush to complete this.

 2. Login into your drupal commerce install and enable the module under Administration -> Modules
    The module will be in the group Commerce - Payment.

 3. Enter your Charity Clear Merchant details.  You need your merchant ID, your secret password
    as a minimum.  You can optionally add other changes like payment reference prefix and the payment
	gateway url.
	
OPERATION
---------

The module will write to the log if a payment fails the signature check.  This is something to look
out for as it could indicate tampering.

 
