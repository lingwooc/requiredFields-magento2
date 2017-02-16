# RequiredFields-magento2
A patch to bring forward the fix to the location of the required fields messages in magento2.

- Issue: https://github.com/magento/magento2/issues/5428
- Commit: https://github.com/magento/magento2/commit/51bc865

This module is no longer required after 2.1.4
# Installation
- Extract over your magento installation.
- php bin/magento setup:upgrade
- php bin/magento setup:di:compile
- php bin/magento setup:static-content:deploy

# Usage
Do nothing except check you css, it's all fixed (for now). When the new version comes out with this fix, just remove this module.
