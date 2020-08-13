# wpdb-standalone
WordPress standalone database class cleaned up from WP specific variables and function calls.

### Example Usage

```php
require_once( dirname(__FILE__).'/wpdb.php' );

$wpdb = new wpdb( 'user', 'password', 'database_name', 'localhost' );
$data = $wpdb->get_results( "SELECT * FROM users WHERE 1=1" );
```
