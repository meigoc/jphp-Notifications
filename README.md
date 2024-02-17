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

// show function
// INFORMATION
Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'INFORMATION');
// NOTICE
Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'NOTICE');
// SUCCESS
Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'SUCCESS');
Notifications::success($title, $message)
// WARNING
Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'WARNING');
Notifications::warning($title, $message)
// ERROR
Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'ERROR');
Notifications::error($title, $message)
// CUSTOM
Notifications::show('Funny lib :>', 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque posuere nisl sed mauris porta cursus.', 'CUSTOM');

// Crash notification
Notifications::attachException(UXTrayNotification $notify, \Exception $e)

// And...
Notifications::showAccountWelcome();
Notifications::showAccountUnavailable();
Notifications::showExecuteUnableStop();
Notifications::showInvalidValidation();
Notifications::errorDeleteFile($file);
Notifications::errorCopyFile($file);
Notifications::showProjectIsDeleted();
Notifications::showProjectIsDeletedFail();
Notifications::showAccountAuthWelcome(array $data)
Notifications::showAccountAuthorizationExpired()
Notifications::showException(\Exception $e)
```
