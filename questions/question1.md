### Given a file `wp-content/plugins/hello-world.php` with the following content:

```php
<?php

add_filter('the_content', 'hello_world');

function hello_world ( $content ){
  return "<h1>Hello World</h1>" . $content;
}
```

### Answer the following questions:

1. Why isn't this visible on https://my-site.com/wp-admin/plugins.php?
1. If it was visible, what would this plugin do if enabled?
