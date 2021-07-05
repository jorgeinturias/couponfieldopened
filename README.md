# cuponfieldopened
Magento 2 Cupon field opened

### Set up? ###

1. clone the repository
2. create folder app/code/Int/DiscountCollapsed when located at the root of the Magento site
3. copy the content of this repository within the folder
4. install the module php bin/magento setup:upgrade

Add product to the cart and check the cart render a discount widget that is expanded by default.
Go to the checkout and the same applies.

For both areas, the discount widget is still fully javascript powered as per default Luma behaviour.
--> for instance, you can collapse the discount and expand it again.