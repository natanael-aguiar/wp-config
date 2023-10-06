# Good settings for your WordPress wp-config

```php
/* SSL */
define('FORCE_SSL_LOGIN', true);
define('FORCE_SSL_ADMIN', true);

/* Custom WordPress URL. */
define('WP_SITEURL',     'http://example.com');

/* Specify maximum number of Revisions. */
define('WP_POST_REVISIONS', '2');

/* Media Trash. */
define('MEDIA_TRASH', true);

/* Remove old versions of images */
define('IMAGE_EDIT_OVERWRITE', true);

/* WordPress debug mode for developers. */
define('WP_DEBUG',         false);
define('WP_DEBUG_LOG',     false);
define('WP_DEBUG_DISPLAY', false);
define('SCRIPT_DEBUG',     false);
define('SAVEQUERIES',      false);

/* WordPress Cache */
define('WP_CACHE', true);

/* Compression */
define('ENFORCE_GZIP',        true);

/* Updates */
define('DISALLOW_FILE_MODS', true);
define('DISALLOW_FILE_EDIT', true);

```
