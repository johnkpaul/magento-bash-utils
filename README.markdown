Installation
===========
Add the magento-bash-utils directory to your bash shell PATH
```chmod -R +x magento-bash-utils```
add ```source mage_aliases``` to your bash profile


Usage
===========
cd into the magento root directory, wherever that is on your filesystem
run the mageworkfromhere command in that directory
now the other commands can be run from anywhere on the filesystem

magesearch
------------
magesearch PATTERN
text search for a string in your local magento codebase

example:
~~~
local@local:~$ magesearch "add to cart"
/opt/workspace/magento/RELEASE_NOTES.txt
/opt/workspace/magento/app/code/core/Mage/Wishlist/Model/Item.php
/opt/workspace/magento/app/code/core/Mage/Wishlist/Block/Item/Configure.php
/opt/workspace/magento/app/code/core/Mage/Catalog/Model/Product/Type/Abstract.php
/opt/workspace/magento/app/code/core/Mage/Catalog/Helper/Product/Compare.php
/opt/workspace/magento/app/code/core/Mage/Checkout/Model/Cart.php
/opt/workspace/magento/app/code/core/Mage/Checkout/Model/Api/Resource/Product.php
/opt/workspace/magento/app/code/core/Mage/XmlConnect/controllers/CartController.php
/opt/workspace/magento/app/code/core/Mage/XmlConnect/Block/Adminhtml/Mobile/Edit/Tab/General.php
/opt/workspace/magento/app/locale/en_US/Mage_XmlConnect.csv
~~~

magecode and magedesign
----------------------
either of these commands will switch your working directory into the code or design directories of your magento installation

