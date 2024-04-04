
# Fakturama 2 to Modified Shop 2.x/3.x Connector

This piece of code is the connection between a Fakturama instance on your pc and your online webshop powered by modified Shop.

## Prerequsites

- up and running installation of Fakturama (tested with 2.1.3), you can get it from here [www.fakturama.info](https://www.fakturama.info)
- up and running installation of either modified Shop 2.0.x or 3.x, you can get it from here [www.modified-shop.org](https://www.modified-shop.org)
- PHP 8.0 or higher is required

## Installation

- download and upload/move the 'facturama_connector.php' to your admin directory of your shop (see note at the end). No further installation needed.

## Usage

Go to Fakturama Preferences, Webshop and enter your webshop url followed by 'ADMIN_DIR/facturama_connector.php'. Replace ADMIN_DIR with your actual admin directory name (see note at the end). If your shop runs under www.domain.tld and your admin directory is just admin, the full url would be https://www.domain.tld/admin/fakturama_connector.php.
Enter also your username and password you're using to access your admin area. Any user with access to products and orders can be used.
Click on Settings Webshop and try to pull the order status from the webshop. If all went well, you can return to the main window of Fakturama and click on the Webshop button to actually synchronize your Fakturama with the online shop.


### Note about admin directory

the legacy default name was 'admin', newer installations of modified Shop get a random directory name now by default, e.g. admin_HJ4x54x

