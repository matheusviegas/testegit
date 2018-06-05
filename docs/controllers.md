---
currentMenu: controllers
---

## Creating a new Controller

This is the main structure of a controller. Must extend the base Controller from App\Core\Controller and call the construct of the super class.

Within the constructor of the super class, you can inform the role required for access this controller (optional, if not informed its gona be a public one).

```php
<?php
namespace App\Controllers;
use App\Core\Controller;

class ExampleController extends Controller {

    public function __construct() {
        parent::__construct();
    }

    public function index() {
    	// do something
    }
}
```
