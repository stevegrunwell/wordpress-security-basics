###  Disable file editing

WordPress constant that will disable the plugin and theme editors

```php
define( 'DISALLOW_FILE_EDIT', true );
```

<div class="fragment">
  <p>&hellip;or disable _everything_, including the plugin installer</p>
  <pre><code class="php">define( 'DISALLOW_FILE_MODS', true );</code></pre>
  <p><em>This will break automatic updates!</em></p>
</div>