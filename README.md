# phpdesktop
PHP Desktop is an open source project founded by Czarek Tomczak in 2012 to provide a way for developing native desktop GUI applications using web technologies such as PHP, HTML5, JavaScript and SQLite.

In a certain sense phpdesktop acts as a PHP to EXE compiler. It embeds a web browser, a multithreaded web server and a PHP interpreter. All embedded into a single application. The web server embedded is Mongoose (the MIT-licensed version). Supported browsers are Internet Explorer and Google Chrome. The package with Chrome embedded has no external dependencies, everything is included in the phpdesktop binaries and works out of the box on a user's computer.

All popular PHP frameworks are supported, see the PHP frameworks support wiki page for example configurations for CakePHP, CodeIgniter, Laravel, Symfony, Yii and Zend Framework. You can create a standalone executable for distribution with the help of the Inno Setup installer. PHP sources can be protected with the many of the available PHP encoders. PHP Desktop is released under non-restrictive license, thus it is free for commercial use.

It is one of the top goals for PHP Desktop to be stable, to work reliably. PHP Desktop does not suffer from memory leaks. PHP by design was never intended for running long hours/days, as desktop applications usually do. This is not a concern when using PHP Desktop, as it is running an internal web server and serving pages through CGI. So when PHP script ends execution PHP-CGI process is killed and all memory is always freed.
