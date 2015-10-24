# console_log
This is a debug script for php programming.Especially,  WordPress.

## Sample usage ##

Like var_dump(), but console_log() write logs to a prepared file:

```php
<?php

// Write to this log file.
define('CONSOLE_LOG_FILE', '/var/log/console.log');   

// something to debug vriable or literal value.
$foo = 'a';
console_log($foo);
```

