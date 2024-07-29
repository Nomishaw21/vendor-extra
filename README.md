### Cloning :
- Clone this repo in vendor_extra in your working directory by :
```
git clone https://github.com/Nomishaw21/vendor_extra vendor/extra
```
Make these changes in **device.mk**
```
# signed
$(call inherit-product-if-exists, vendor/extra/product.mk)
```
