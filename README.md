# jphp-Notifications
Notifications straight from DevelNext!


    unpack meigo.zip
    insert files to 'meigo/ui' to SRC root


# Types of notifications:
[INFORMATION, NOTICE, SUCCESS, WARNING, ERROR, CUSTOM]
![types](https://github.com/meigoc/jphp-Notifications/assets/73817505/8dd54ef1-31c3-48bd-b40c-bcc7b78d9c6c)

# Examples:
```php
use meigo\ui\Notifications;

         Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'INFORMATION');
         Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'NOTICE');
         Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'SUCCESS');
         Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'WARNING');
         Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'ERROR');
         Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'CUSTOM');

Notifications::showAccountWelcome();
Notifications::showAccountUnavailable();
Notifications::showExecuteUnableStop();
and more...
```
