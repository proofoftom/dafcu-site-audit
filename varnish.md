# Varnish

Varnish is an HTTP accelerator that serves both static content and anonymous pages at lightning speed. By serving data from virtual memory, a response is returned without needing to access the application server, which in turns frees application container workers to build more dynamic requests. Each Varnish container can handle thousands of requests per second, much faster than a site's framework alone.

Varnish can also improve the availability of your site. For example, if a PHP fatal error breaks your site, anonymous page requests can still be served by Varnish and end-users won't realize anything is wrong.

Once installing Varnish on your server, there's The Drupal module allows for a user-friendly integration to Drupal requiring minimum system administration skills.

* http://drupal.org/project/varnish
 
Combined with the [expire](https://www.drupal.org/project/expire), the Drupal Varnish module is beginning to implement dynamic cache expiration, which will allow for much longer page lifetimes (and thus higher cache hit-rates!).