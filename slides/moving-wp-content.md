###  Moving wp-content

WordPress allows you to move your wp-content/ directory to another location

```php
// Absolute server path
define( 'WP_CONTENT_DIR', dirname( __FILE__ ) . '/content' );

// No trailing slash!
define( 'WP_CONTENT_URL', 'http://example.com/content' );
```

Another example of security through obscurity