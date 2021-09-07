# OPNSense Captive Portal QRCode Login
Allows to log in to OPNSense with QR code

Notice. This is a very simple QRCode login and is not encrypted. It is intended to be used with vouchers where logins are only temporarily available.

The text in the QR code must be structured like this:
{"username":"VOUCHERUSERNAME","password":"VOUCHERPASSWORD"}

The login is based on the OPNSense Default Template.
