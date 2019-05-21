# Plugin loader - Plugin for IO CMS

```php
$plugin = new PluginLoader(__DIR__ . '/plugins', ['plugin-loader']);
$plugin->load('path', 'url'); // Load path and url
$plugin->load('!routes'); // Load all but routes, that has not already been loaded
$plugin->load('routes'); // Load routes
```

## Libraries used

- https://github.com/jenstornell/php-plugin-loader