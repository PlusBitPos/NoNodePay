# **Simple ILCoin Shopping Cart (No Node)**

Start Accepting ILCoin Payments With 0% Fees & No Third-party

Simple ILCoin Shopping Cart is a self-hosted, no node required and open-source cryptocurrency payment processor. It's secure and free.

This shopping cart will allow users to accept ILCoin on their website without having to use a privileged API service. This project does use some public API's to check the blockchain but they require no permission or API Keys.


1. Download the files in the repository : https://github.com/PlusBitPos/Simple-ILCoin-Shopping-Cart-No-Node-
1. Create and configure a database on your webserver
1. Import the included SQL database files using PHPmyadmin or similar database manager
1. Open the config.php file and update the fields
1. Pre-generate 1,000 (or more) address using the tool in /js/addresses.html. Copy the output table and paste into a spreadsheet. Save as an Open Spreadsheet document.
1. Save a copy with the private keys offline, and save another copy to be imported to the database that has the private key column removed. The index or address of an order can later be used to track down the corresponding private key on the offline copy.

Access the admin panel to manage your orders and products with login.php The password to access the admin page is set in your config.php

That's it!

# Video presentation of checkout
![grab-landing-page](https://github.com/PlusBitPos/Simple-ILCoin-Shopping-Cart-No-Node-/blob/master/demo.gif)

# Video presentation of address generation
