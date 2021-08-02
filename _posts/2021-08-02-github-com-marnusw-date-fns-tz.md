---
title: date-fns-tz
categories: ['javascript', 'date', 'zone-helpers']
---
## [date-fns-tz](https://github.com/marnusw/date-fns-tz)

### Complementary library for date-fns v2 adding IANA time zone support


Time zone support for [date-fns](https://date-fns.org/) v2.0.0 using the
[Intl API](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl). By using
the browser API no time zone data needs to be included in code bundles. Modern browsers all support the
[necessary features](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DateTimeFormat#Browser_compatibility),
and for those that don't a [polyfill](https://github.com/yahoo/date-time-format-timezone) can be used.

If you do not wish to use a polyfill the time zone option can still be used, but only with
time zone offsets such as '-0200' or '+04:00' and not IANA time zone names.
