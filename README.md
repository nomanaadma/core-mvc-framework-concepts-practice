# Dream MVC

### Disclaimer

Its was a practice of core concepts of mvc framework.
It can be used to create small applications but It's not advisable to use this for scalable projects as this is still an alpha project I'm using to learn and exercise.
If you are inclined to help with bugs corrections and developing new features you are free to do so.

See demo app created on this framework [AppDreamMVC](https://github.com/nomanaadma/AppDreamMVC)

### Prerequisites

* Apache Server
* PHP 7.2+

### Config File

Modify the app/config/config.php file according to your needs. You can use example.config.php file inside the same folder as an example based on my local settings.

``` php
// Database Configuration
define('DB_HOST', '<databaseHost>');
define('DB_USER', '<databaseUser>');
define('DB_PASS', '<databasePassword>');
define('DB_NAME', '<databaseName>');
```

Modify it like this

``` php
// Database Configuration
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'appdreammvc');

```

### htaccess file

Modify .htaccess file inside the public folder to match the name of your installation folder

### Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.