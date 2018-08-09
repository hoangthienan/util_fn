FN (function)
====

Simple library to build tiny PHP application.

## Usage

```php
<?php

go1\util_fn\Fn::run(
    function (go1\util_fn\Fn $fn, stdClass $payload) {
        return "[example.1] Hello {$payload->name}!\n";
    }
);
```

Execute it: `echo '{"name":"world"}' | php hello-world.php`

More examples can be found under `./examples/`.