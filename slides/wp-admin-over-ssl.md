###  wp-admin over SSL

Force WordPress to serve login pages over SSL:

```php
define( 'FORCE_SSL_LOGIN', true );
```

Serve **all** admin and login pages over SSL:

```php
define( 'FORCE_SSL_ADMIN', true );
```
<p class="fragment">_Of course, this requires that your site has SSL enabled_</p>