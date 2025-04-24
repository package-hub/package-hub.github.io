---
title: Bad-Pdf
categories: ['python', 'ntlm-hashes', 'badpdf']
---
## [Bad-Pdf](https://github.com/deepzec/Bad-Pdf)

### Steal Net-NTLM Hash using Bad-PDF


Bad-PDF create malicious PDF file to steal NTLM(NTLMv1/NTLMv2) Hashes from windows machines, it utilize vulnerability disclosed by checkpoint team to create the malicious PDF file. Bad-Pdf reads the NTLM hashes using Responder listener.

~~This method work on all PDF readers(Any version)~~  most of the EDR/Endpoint solution fail to detect this attack.

Reference : https://research.checkpoint.com/ntlm-credentials-theft-via-pdf-files/
