# Implementing

## Billing Portal

PayStand provides every partner with a Billing Portal; an instance of checkout configured for their account, found a static URL. Also known as a Payment Page, a Checkout Page, and (every so often) a Preset (in that every Billing Portal has a "preset set of conditions").

Partners use their Billing Portals in invoices, emails, embed in their websites, and sometimes just direct their customers to the URL separately as a convenient way to accept a payment.

Click on the Image below to give it a try:


[![Pay Now Powered By PayStand](https://github.com/emmaldon/slate/blob/master/source/images/PayNow.jpg)](https://acmecargovendor-portal.paystand.co target="_blank") 

### Test cards
PayStand test card numbers

| Card Number        | Notes           | 
| ------------- |:-------------:| -----:|
| 4000000000000077     | Charge will succeed and funds will be added directly to your available balance. | 
| 4242424242424242     | Charge will succeed.    |   
| 4000000000000002 | Charge will be declined with a card declined.    |    
| 4000000000000069 | Charge will be declined with an expired card. |
| 4000000000000127 | Charge will be declined with an incorrect cvc. |

<aside class="notice">
<b>Currency</b>
Billing Portals and Pay Now buttons all operate in your account's default currency (either USD or CAD).
</aside>