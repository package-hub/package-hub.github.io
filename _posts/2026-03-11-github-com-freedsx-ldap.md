---
title: LDAP
categories: ['php', 'ldap', 'openldap']
---
## [LDAP](https://github.com/FreeDSx/LDAP)

### A Pure PHP LDAP Library.

FreeDSx LDAP is a pure PHP LDAP library. It has no requirement on the core PHP LDAP extension. This library currently implements
most client functionality described in [RFC 4511](https://tools.ietf.org/html/rfc4511) and some very limited LDAP server
functionality. It also implements some other client features from various RFCs:

* Paging Control Support ([RFC 2696](https://tools.ietf.org/html/rfc2696))
* VLV Control Support ([draft-ietf-ldapext-ldapv3-vlv-09](https://www.ietf.org/archive/id/draft-ietf-ldapext-ldapv3-vlv-09.txt))
* Server Side Sort Control ([RFC 2891](https://tools.ietf.org/html/rfc2891))
* Password Modify Request ([RFC 3062](https://tools.ietf.org/html/rfc3062))
* String Representation of Search Filters ([RFC 4515](https://tools.ietf.org/search/rfc4515))
* SASL authentication / integrity layer support for certain mechanisms ([RFC 4513](https://tools.ietf.org/search/rfc4513))

It supports encryption of the LDAP connection through TLS via the OpenSSL extension if available.
