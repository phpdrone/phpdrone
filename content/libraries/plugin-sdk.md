---
date: 2018-20-05T10:21:05+02:00
title: Drone Plugin PHP SDK 
---

Allows for creating PHP based plugins.

```php
<?php
require __DIR__."/vendor/autoload.php";

// Get the build :
$build = new \DronePluginSdk\Build();

// Get some settings :
var_dump($build->getPluginParameter('my_parameter'));```
```

Full API documentation is available at http://phpdrone.github.io/drone-plugin-sdk/
