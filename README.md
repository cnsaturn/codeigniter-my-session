## Intro

Another CodeIgniter session library that utilizes the Native PHP session mechanism instead of the original CI cookie-based OR DB-based way. It takes Memcached as the session datastore, which will boost the performance of your app. Also, it supports all the [original features](http://codeigniter.com/user_guide/libraries/sessions.html), such as flash session.

## Author

* [HU Yang Gang](https://github.com/Situos/codeigniter-my-session), aka. Saturn

## Requirement

* PHP 5.2.0 +
* CodeIgniter 2.0 +

## HOW TO USE?

1.  Drop libraries/MY_Session.php into your application/libraries folder
2.  Drop system/libraries/Cache folder into your system/libraries folder, overwrite the existing files if needed when prompted.
3.  Load the Session library manually OR you can autoload it in config/autoload.php file.
4.  Use it like you are using the original [CI Session library](http://codeigniter.com/user_guide/libraries/sessions.html).
5.  That's all, enjoy! 

## License

The MIT license


