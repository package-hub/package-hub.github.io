---
title: tax
categories: ['php']
---
## [tax](https://github.com/commerceguys/tax)

### A PHP 5.5+ tax library.


[Zone](https://github.com/commerceguys/zone/blob/master/src/Model/ZoneInterface.php) 1-1 [TaxType](https://github.com/commerceguys/tax/blob/master/src/Model/TaxTypeInterface.php) 1-n [TaxRate](https://github.com/commerceguys/tax/blob/master/src/Model/TaxRateInterface.php) 1-n [TaxRateAmount](https://github.com/commerceguys/tax/blob/master/src/Model/TaxRateAmountInterface.php)

Each tax type has a zone and one or more tax rates.
Each tax rate has one or more tax rate amounts.

Example:
- Tax type: French VAT
- Zone: "France (VAT)" (covers "France without Corsica" and "Monaco")
- Tax rates: Standard, Intermediate, Reduced, Super Reduced
- Tax rate amounts for Standard: 19.6% (until January 1st 2014), 20% (from January 1st 2014)

The base interfaces don't impose setters, since they aren't needed by the service classes.
Extended interfaces ([TaxTypeEntityInterface](https://github.com/commerceguys/tax/blob/master/src/Model/TaxTypeEntityInterface.php), ([TaxRateEntityInterface](https://github.com/commerceguys/tax/blob/master/src/Model/TaxRateEntityInterface.php), ([TaxRateAmountEntityInterface](https://github.com/commerceguys/tax/blob/master/src/Model/TaxRateAmountEntityInterface.php)) are provided for that purpose,
as well as matching [TaxType](https://github.com/commerceguys/tax/blob/master/src/Model/TaxType.php), [TaxRate](https://github.com/commerceguys/tax/blob/master/src/Model/TaxRate.php) and [TaxRateAmount](https://github.com/commerceguys/tax/blob/master/src/Model/TaxRateAmount.php) classes that can be used as examples or mapped by Doctrine.
