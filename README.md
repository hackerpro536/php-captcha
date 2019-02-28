Project information
----------------------------
- Started: 20 September 2019.
- Project Manager: [HackerPro536 (LE VAN PHU)](http://levanphu.info) <hackerpro536@gmail.com>.
- Copyrights: 2019 LP Group.
- Version: 0.1
Category
------------------------
Simple Captcha
Installation
----------------
### System requirements
- PHP version:  7.0 and lasted.
- MySQL version: Recommend 5.6 and above.

Please keep in mind that this project is licensed by [LP Group](http://levanphu.info):

 1. Only authenticated developers can download from the link above.
 2. Published website must be PMS authorised clients.

Any other cases of uses not mentioned above is prohibited. If you have illegal copy of this project, please kindly to contact us for our further supporting.

PMS Group
==========

 1. HackerPro536 (LE VAN PHU) - CEO.

## Attribution

- Important! Make sure you call session_start() before calling the simple_php_captcha() function
- Requires PHP GD2 library
- Backgound images must be in PNG format
- Fonts must be either TTF or OTF
- Backgrounds and fonts must be specified using their full paths (tip: use $_SERVER['DOCUMENT_ROOT'] . '/' . [path-to-file])
- Angles should not exceed approximately 15 degrees, as the text will sometimes appear outside of the viewable area
- Creates a function called simple_php_captcha() in the global namespace
- Uses the $_SESSION['simple-php-captcha'] session variable
