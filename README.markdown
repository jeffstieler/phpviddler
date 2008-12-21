phpViddler API Library
======================

A PHP Wrapper class for Viddler’s REST Interface. Wraps each method into their own functions and includes an open source XML Parser.

For more information, visit [our developer site](http://developers.viddler.com/projects/api-wrappers/phpviddler/)

Installation Instructions
-------------------------
phpViddler is meant to be installed into most any PHP-powered web site or application.

1. Download the most recent version.
2. Upload phpviddler.php and xmlparser.php to your server.
3. Include phpviddler.php in your web site or application.
4. Initiate Viddler class $v = new Phpviddler();
5. Setup API Key variable $v->apikey=KEY_HERE

Licensing
---------
phpViddler is dual-licensed under the MIT and GPL licenses. The details of these licenses are included with the zip file.

Third-party software included
-----------------------------
* [XML Library](http://keithdevens.com/software/phpxml) by Keith Devens, version 1.2b (optional)

At present we include the XML Library as a means to parse the REST API’s responses, though it is configurable to turn off for applications that already have an XML Parser. See readme for details.