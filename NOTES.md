# Steps

To enable development mode

```
cd path/to/install
php public/index.php development enable
```

To disable development mode

```
cd path/to/install
php public/index.php development disable
```

# Authentication

```
htpasswd -cs data/users.htpasswd david
```

# Debugging

```
# php.ini
zend_extension = /usr/local/xdebug/xdebug.so
xdebug.remote_enable=on
xdebug.remote_handler=dbgp
xdebug.remote_host=localhost
xdebug.remote_port=9000
```