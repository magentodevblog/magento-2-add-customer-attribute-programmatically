# Magento 2 - How to add customer attribute programmatically

This is a Magento 2 module example on how to add custom attribute into a Customer via install script.

# Installation

- Copy the content of the repo to the <b>app/code/Dev/CustomerAttribute</b>
- Run command: <b>php bin/magento setup:upgrade</b>
- Run command: <b>php bin/magento setup:static-content:deploy </b>  (Use -f for force deploy on 2.2.x or later)
- Now flush cache: <b>php bin/magento cache:flush</b>

# Support

If you encounter any problems or bugs, please <a href="https://github.com/magentodevblog/magento-2-add-customer-attribute-programmatically/issues">open an issue</a> on GitHub.
