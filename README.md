# Amazon Payment Services plugin for Magento
<a href="https://paymentservices.amazon.com/" target="_blank">Amazon Payment Services</a> plugin offers seamless payments for Magento platform merchants.  If you don't have an APS account click [here](https://paymentservices.amazon.com/) to sign up for Amazon Payment Services account.


## Getting Started
We know that payment processing is critical to your business. With this plugin we aim to increase your payment processing capabilities. Do you have a business-critical questions? View our quick reference [documentation](https://paymentservices.amazon.com/docs/EN/index.html) for key insights covering payment acceptance, integration, and reporting.


## Configuration and User Guide
You can download the archive [file](/magento2-aps-2.2.3.zip) of the plugin and install it to Magento. Detailed guide is included in the repository [here](/Magento%20Extension%20User%20Guide_v1.1.pdf).
   

## Payment Options

* Integration Types
   * Redirection
   * Merchant Page
   * Hosted Merchant Page
   * Installments
   * Embedded Hosted Installments

* Payment methods
   * Mastercard
   * VISA
   * American Express
   * VISA Checkout
   * valU
   * mada
   * Meeza
   * KNET
   * NAPS
   * Apple Pay
   

## Changelog

| Plugin Version | Release Notes |
| :---: | :--- |
| 2.4.0 | STCPay is added as a new payment option | 
| 2.3.0 | * Fix - Customer login mandatory for Subscription products <br/> * Fix - Invoice generation on child orders resolved <br/> * Fix - Failed orders not showing in subscription listing <br/> * Fix - Subscriptions listing not showing proper status  <br/> * Fix - Country name issue with version dependency resolved <br/> * Fix - Shipping and billing region id issue resolved <br/> * Fix - Recurring cron issue for inactive products <br/> * Fix - Payment cron issue of Apple Code <br/> * Fix - Credit memo issue resolved <br/> * Fix - Mada bin changes |
| 2.2.3 |   * Fix - Logout after redirection related to session is resolved <br/> * Fix - Apple Pay code simplification | 
| 2.2.2 |   * Fix - Namespace change <br/> * Fix - Shipping and tax calculation corrections in Apple Pay of Product / Cart pages <br/> * Fix - Back button click handling after a successful transaction | 
| 2.2.1 |   * Fix - Fixed Apple Pay floating point issue | 
| 2.2.0 |   * New - Installments are embedded in Debit/Credit Card payment option | 
| 2.1.0 |   * New - ApplePay is activated in Product and Cart pages | 
| 2.0.0 |   * New - Integrated payment options: MasterCard, Visa, AMEX, mada, Meeza, KNET, NAPS, Visa Checkout, ApplePay, valU <br/> * New - Tokenization is enabled for Debit/Credit Cards and Installments <br/> * New - Partial/Full Refund, Single/Multiple Capture and Void events are managed in order details | 


## API Documentation
This plugin has been implemented by using following [API library](https://paymentservices-reference.payfort.com/docs/api/build/index.html)


## Further Questions
Have any questions? Just get in [touch](https://paymentservices.amazon.com/get-in-touch)

## License
Released under the [MIT License](/LICENSE).
