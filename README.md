Disclaimer: Please note that we no longer support older versions of SDKs and Modules. We recommend that the latest versions are used.

# README

# Contents

- Introduction
- Prerequisites
- Installing the payment module
- License

# Introduction

This CartThrob module provides an easy method to integrate with the payment gateway.
 - The httpdocs directory contains the files that need to be uploaded to the root of your Expression Engine installation directory
 - Supports CartThrob versions: **3.0+**
 - Supports Expression Engine versions: **3.0+**

# Prerequisites

- The module requires the following prerequisites to be met in order to function correctly:
    - The 'bcmath' php extension module: https://www.php.net/manual/en/book.bc.php

> Please note that we can only offer support for the module itself. While every effort has been made to ensure the payment module is complete and bug free, we cannot guarantee normal functionality if unsupported changes are made.

# Installing and configuring the module

1. Copy the contents of the httpdocs folder to your root Expression Engine directory, clicking 'Yes' merge folders
2. Log in to the admin area of Expression Engine, then navigate to the developer tools (Wrench icon) in the top right
3. Click 'Add-on Manager'
4. Locate your 'CartThrob Add-on' in the "Thrid Party Add-Ons" section and click manage
5. Navigate to and click the 'PAYMENTS' tab
6. In the "Select a gateway to edit its settings" dropdown choose "Cardstream (Hosted)"
7. Configure the "Cardstream (Hosted)" payment gateway settings. Once configured, scroll down and locate "Allow Gateway Selection in Checkout Form?". Find "Cardstream (Hosted)" and check it, then click 'submit'. The module has now been added to the checkout page
8. By default we have set the module to the use the test details. To use your live details simply replace the test details in the text boxes with the ones supplied from your Cardstream live letter

License
----
MIT
