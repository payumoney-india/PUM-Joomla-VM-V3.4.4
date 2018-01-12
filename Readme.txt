#PayUMoney-Integration-Kit-Joomla-Virtue-Mart

PayU Payment Processor Integration Kit for Joomla-Virtue-Mart
This library provides support for payment gateway PayUMoney 
**************************How to install Virtuemart **********************************************************
Download "com_virtuemart.3.0.9_extract_first" from google or any extrnal sorce.

Go to Extension and then extension manager.
Click on choose file and upload first "com_virtuemart.3.0.9.zip"(As per Joomla instruction).
Click on choose file and upload second "com_virtuemart.3.0.9_ext_aio.zip"(As per Joomla instruction).
Click on choose file and upload second "com_tcpdf_1.0.0.zip"(As per Joomla instruction).
__________________________________________________________________________________________________________

# Installation
Install virtuemart component 3x first
Upload the plugin_payu_pm_virtuemart_3x.zip using extension manager in joomla.
Enable payu payment method in plugin manager.
#Configuration
Go to component, Click on virtuemart.
Click on Payment Method.
Click on New button to add the new payment method.
Click the Payment Method Information tab.
Give the Payment method name, and select YES to publish.
Choose the payu Payment Method in dropdown box.
Then Click on Save button to generate the configuration parameters.
Go to the Configuration tab.
Now you can fill the parameters listed in Configuration tab.
You should give the payu merchant Key, SALT and Mode=Test for testing mode in the listed parameters on configuration tab. These parameters are Mandatory.
Then click Save & Close.
********************************* Error regarding Path like path not set etc. *****************************************

Create a folder with the name "vmfiles" at below path :

data\localweb

In vmfiles create 2 folder with name respective : "invoices" , "keys".
__________________________________________________________________________________________________________