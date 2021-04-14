# PoC-BrokenAuth-AppSpace6.2.4

AppSpace version 6.2.4 is vulnerable to Broken Authentication and found that pages can be called directly, though there is no data in it but the framework is exposed with layouts, menus and functionalities. This supports in stealing session data i.e. cookie information to gain unauthorized access. However, this could also be used to check functionalities available and implemented in any organization

For POC, <URL>/medianet/mail.aspx can be hit directly for checking the exposure.
