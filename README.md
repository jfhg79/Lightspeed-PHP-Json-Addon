Lightspeed-PHP JsonResponse addon
=================================

![Lightspeed-PHP logo](http://lightspeed-php.com/images/logo.png "Lightspeed-PHP")

**[LIGHTSPEED-PHP](http://lightspeed-php.com) IS A MINIMALISTIC AND FAST PHP FRAMEWORK** aiming to provide basic structure that helps you build your applications faster and more efficiently on solid architecture. It's designed to be small, fast, easy to understand and extend.

Lightspeed-PHP [Github project](https://github.com/kallaspriit/Lightspeed-PHP) | [Homepage](http://lightspeed-php.com)


How to install
--------------
Simply download the archive and unpack it to the root directory of your project. Creates a "json" directory under "library".

Make sure your **application/Autoload.php** contains a rule to autoload the JsonResponse class when needed.

```
else if ($className == 'JsonResponse') {
	require_once LIBRARY_PATH.'/json/JsonResponse.php';
}
```


How to use it
-------------
An example of how to use the json addon in your project is covered [on this tutorial page](http://lightspeed-php.com/tutorial/json).

Up-to-date version of this tutorial is available on the [addons page](http://lightspeed-php.com/add-ons/json).