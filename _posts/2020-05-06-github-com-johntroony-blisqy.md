---
title: Blisqy
categories: ['python', 'sql', 'sql-injection']
---
## [Blisqy](https://github.com/JohnTroony/Blisqy)

### Version 0.2 - Exploit Time-based blind-SQL injection in HTTP-Headers (MySQL/MariaDB).


Blisqy is a tool to aid Web Security researchers to find Time-based Blind SQL injection on HTTP Headers and also exploitation of the same vulnerability.

The exploitation enables slow data siphon from a database (currently supports MySQL/MariaDB only) using bitwise operation on printable ASCII characters, via a blind-SQL injection.

For interoperability with other Python tools and to enable other users utilise the features provided in Blisqy, the modules herein can be imported into other Python based scripts.

When testing for Time-based Blind SQL injections, any network lag or congestion can affect the effectiveness of your fuzzing or exploitation. To compensate for the possible network lags and uncertainties that might cause delays, Blisqy time comparison is dynamic and it's calculated at runtime for each test. The tests utilizes `greenlet`(alight-weight cooperatively-scheduled execution unit) to provide a high-level synchronous API on top of `libevevent` loop. It provides a fast and efficient way of carrying out the payload tests in a short time, also, one particular test should not affect  another because they are not fully done in a sequential method.