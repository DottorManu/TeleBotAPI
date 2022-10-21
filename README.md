# TeleBotAPI
PHP Framework for Telegram BotAPI

## Installing

`sudo apt install git`
<br>
`git clone https://github.com/DottorManu/TeleBotAPI`

## Getting Started
```php
<?php
include 'bot.php';
$bot = new Bot('BOT-TOKEN');
```

## Your First Command
```php
if ($bot->text == '/start'){
 $bot->sendMessage($bot->user_id,'It Works!');
}
```
