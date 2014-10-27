# Overview #
paypal payment

[android, ios] [phonegap cli] [crosswalk]

requires paypal developer account https://developer.paypal.com/

ios is not yet tested.

this repository was forked from https://github.com/paypal/PayPal-Cordova-Plugin and edited for phonegap plugin support
# Install phonegap plugin #

## Phonegap build service (config.xml) ##
```c
not yet supported
```
## Phonegap cli ##
```c
cordova plugin add https://github.com/cranberrygame/com.cranberrygame.phonegap.plugin.paypal

[android, ios]

//Get live client id
https://developer.paypal.com/ - Dashboard - My apps - [specific app] - Live credentials - Show - Click "Upgrade to a Premier or Business account" -... - Client ID:

//Get sandbox client id
https://developer.paypal.com/ - Dashboard - My apps - [specific app] - Sandbox credentials - Client ID:
```
## Crosswalk ##
```c
XDK PORJECTS - your_xdk_project - CORDOVA 3.X HYBRID MOBILE APP SETTINGS - PLUGINS AND PERMISSIONS - Third Party Plugins - Add a Third Party Plugin - Get Plugin from the Web -

Name: paypal
Plugin ID: com.cranberrygame.phonegap.plugin.paypal
Repo URL: https://github.com/cranberrygame/com.cranberrygame.phonegap.plugin.paypal

[android, ios]

//Get live client id
https://developer.paypal.com/ - Dashboard - My apps - [specific app] - Live credentials - Show - Click "Upgrade to a Premier or Business account" -... - Client ID:

//Get sandbox client id
https://developer.paypal.com/ - Dashboard - My apps - [specific app] - Sandbox credentials - Client ID:
```
# API #
See https://github.com/paypal/PayPal-Cordova-Plugin
# Examples #
See https://github.com/paypal/PayPal-Cordova-Plugin
# Test #
//Create test account for sandbox
Dashboard - Sandbox - Accounts - Create Account - Account type: Personal (buyer account) - ... - Create Account

Test with test account
# Useful links #

Test REST API transactions
Test PayPal payments
Test credit card payments
https://developer.paypal.com/docs/integration/direct/test-the-api/

Credentials (client id)
https://github.com/paypal/PayPal-Android-SDK#credentials
https://github.com/paypal/PayPal-iOS-SDK#credentials

Phonegap related c2 plugins (+Crosswalk)
https://www.scirra.com/forum/viewtopic.php?t=109586

Games/Apps made with phonegap related c2 plugins (+Crosswalk)
https://www.scirra.com/forum/viewtopic.php?t=115517

Construct 2: an easy html5 games/apps maker
https://www.scirra.com/