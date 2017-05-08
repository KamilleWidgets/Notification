Notification
===============
2017-04-18



Widget for displaying a Notification.




This is a widget for the [kamille framework](https://github.com/lingtalfi/Kamille).


Install
===========
using the [kamille installer tool](https://github.com/lingtalfi/kamille-installer-tool)
```bash
kamille winstall Notification
```



Model
===========

The model used by this widget is the notification model from the [Models planet](https://github.com/lingtalfi/Models).





Demo snippet
=========

```php
<?php


$conf = [
    "layout" => [
        "tpl" => "splash/default",
        "conf" => [],
    ],
    "widgets" => [
        "main.notification" => [
            "tpl" => "Notification/default",
            "conf" => [
                "notifications" => [
                    [
                        "type" => "error",
                        "title" => "Oops",
                        "msg" => "Dude, an error occurred, sorry",
                    ],
                ],
            ],
        ],
    ],
];
```






History Log
------------------

- 1.0.0 -- 2017-04-18

    - initial commit