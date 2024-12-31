# WordPress i Cloudflare

Ustawienie DNS potrafi namieszać z redirect loop w WordPressie.

Szybkie rozwiązanie to

```php
define('FORCE_SSL_ADMIN', false);
```
Można też skorzystać z wtyczki[^0].

[0]: https://community.cloudflare.com/t/endless-redirect-with-wordpress/3914

#wordpress
