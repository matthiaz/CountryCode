# CountryCode
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![If this project has business value for you then don't hesitate to support me with a small donation.](https://img.shields.io/badge/Donations-via%20Paypal-blue.svg)](https://www.paypal.me/PeterK93)

Methods for working with 2-character country codes (validation, name from code).

## ⚠️CAUTION
When using method `getName()`, multibyte strings will be returned.

### Usage Exaples

```php
use peterkahl\CountryCode\CountryCode;

# Validate a country code string:
if (CountryCode::isValid('uk'))
{
  echo 'valid';
}
else
{
  echo 'invalid';
}

# Get name from country code:
echo CountryCode::getName('RE'); # Réunion
```