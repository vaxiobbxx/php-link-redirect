# php link redirect
You can use and modify this

Usage:

```php
<?php
function redirect($url, $statusCode = 303)
{
   header('Location: ' . $url, true, $statusCode);
   die();
}

redirect('https://discord.gg/CVKpAeb');
?>
```
