---
title: NovaGram
categories: ['php', 'telegram', 'bot']
---
## [NovaGram](https://github.com/skrtdev/NovaGram)

### An Object-Oriented PHP library for Telegram Bots

An example code of a simple bot.  
Works with both getUpdates and Webhooks
```php
use skrtdev\NovaGram\Bot;
use skrtdev\Telegram\Message;

$Bot = new Bot('YOUR_TOKEN');

$Bot->onCommand('start', function (Message $message) {
    $message->reply('Hey! Nice to meet you. Use /info to know more about me.');
});

$Bot->onCommand('info', function (Message $message) {
    $message->reply('Well, I\'m just an example, but you can learn more about NovaGram at novagram.gaetano.eu.org');
});
```
