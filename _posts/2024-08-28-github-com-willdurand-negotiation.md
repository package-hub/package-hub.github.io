---
title: Negotiation
categories: ['php', 'content-negotiation', 'negotiation']
---
## [Negotiation](https://github.com/willdurand/Negotiation)

### Content Negotiation tools for PHP.


``` php
$negotiator = new \Negotiation\Negotiator();

$acceptHeader = 'text/html, application/xhtml+xml, application/xml;q=0.9, */*;q=0.8';
$priorities   = array('text/html; charset=UTF-8', 'application/json', 'application/xml;q=0.5');

$mediaType = $negotiator->getBest($acceptHeader, $priorities);

$value = $mediaType->getValue();
// $value == 'text/html; charset=UTF-8'
```

The `Negotiator` returns an instance of `Accept`, or `null` if negotiating the
best media type has failed.
