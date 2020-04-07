### Given a file `wp-content/plugins/hello-world.php` with the following content:

```php
<?php

add_filter('the_content', 'hello_world');

function hello_world ( $content ){
  return "<h1>Hello World</h1>" . $content;
}
```

### Answer the following questions:

1. Why can't I see this plugin when viewing https://my-site.com/wp-admin/plugins.php?
1. If enabled, what would this plugin do?
