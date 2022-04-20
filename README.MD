# Zoho Coupon and Discount
## Description:
<p>A plugin help you handle hassle free coupons and discount. 

In Zoho books, list of coupons are stored as custom module records.

We have a lookup field in invoice. Whenever the coupon record is associated with invoice, the custom function triggers and updated discount value in the invoice.</p>
  
#### Components Used:
<li> Custom Field  - A lookup field in invoice to associate the coupon module record.</li>
<li>Custom Module  - The module to maintain coupon details. this module contains Coupon Name, Coupon discount percentage,   Maximum discount amount, Coupon validity date and Description fields.</li>
<li>Connections    - To update the invoice with discount from custom function through Oauth Authendication.</li>