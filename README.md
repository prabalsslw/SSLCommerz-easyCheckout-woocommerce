# SSLCommerz easyCheckout for WooCommerce

> SSLCOMMERZ is the first payment gateway in Bangladesh opening doors for merchants to receive payments on the internet via their online stores. Their customers will be able to buy products online using their credit cards as well as bank accounts. If you are a merchant, you have come to the right place! WooCommerce plugin for SSLCommerz payment gateway with Dynamic IPN Support.

## Getting Started

### Prerequisites

1. Wordpress 5.1.*
2. WooCommerce 3.6.*
3. cURL php extension.

### Installation

1. Download zip file or Clone the repository.
2. Go to `Plugins > Add New`.
3. Click on `Upload Plugin` button.
4. Go to `Choose File` and upload the Zip file of plugin.
5. Active the plugin.
6. Use your Sandbox Store ID/Password for test environment or Use your Live Store ID/Password for Live environment.
7. If you don't have sandbox store credentials then create it from [Here](https://developer.sslcommerz.com/registration/ "SSLCommerz Sandbox Registration")

**[NOTE]** This plugin will automatically set the IPN url, there is no need to set IPN in merchant panel when using this.

### Configuration

1. Open Admin Panel.

![Payments Menu](images/screenshot-1.png)

2. Navigate to ```Woocommerce > Settings > Payments``` tab.

![Payments Menu](images/screenshot-2.png)
![Payments Menu](images/screenshot-3.png)

3. Click on SSLCommerz to edit the settings. If you do not see SSLCommerz in the list at the top of the screen make sure you have activated the plugin in the WordPress Plugin Manager.
4. Enable the Payment Method, give a proper title and description to show on the checkout page,  fill up stroe id and store passowrd fields carefully, select success and fail/cancel page.
5. You can enable or disable Hosted/Popup mode from `Hosted EasyCheckout` 
6. Setup is complete. Check if everything is working properly.


## FAQ

### What is WooCommerce?
> WooCommerce is an open-source e-commerce plugin for WordPress. 

### What is SSLCommerz?
> SSLCOMMERZ is the first payment gateway in Bangladesh opening doors for merchants to receive payments on the internet via their online stores. Their customers will be able to buy products online using their credit cards as well as bank accounts.

### What is a Payment Gateway?
> Payment Gateway is a service that allows merchant to accept secure credit card transactions online. It essentially connects a merchant website to a transaction processor like bank to take payment from a customer for an order.

### What is IPN?
> This is an important and interesting part of integration. If somehow your consumer pays your payable amount to BANK Side and SSLCommerz accept it as SUCCESS but your website/Connectivity/Customer Network got downtime and unable to update the payment at your side you can use IPN (Instant Payment Notification). It will send a notification to your set up URL in SSLCommerz Merchant Dashboard to notify you and your database even if your user unable to return back to your website.

### I want to enable EMI option, how it works?
> To enable EMI option first you have to make an agreement with us. To do that please communicate with the Business person, you have communicate at the time of Store registration. Besides this in live, you will have EMI configuration option after login to your Merchant report panel go to My Stores>EMI Settings.

### I want my customer will bear the gateway charges. How can I do that?
> Yes, We have solution for this, you can configure this from your merchant panel or mail to `operation@sslcommerz.com` .

### What is the Minimum amount of transaction?
> The minimum amount of transaction should be more than `10TK` .


## Contributors
> Prabal Mallick, Md. Rakibul Islam
> 
> Email: integration@sslcommerz.com
