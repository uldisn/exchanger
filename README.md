# Exchanger

[![Build status](http://img.shields.io/travis/florianv/exchanger/master.svg?style=flat-square)](https://travis-ci.org/florianv/exchanger)
[![Total Downloads](https://img.shields.io/packagist/dt/florianv/exchanger.svg?style=flat-square)](https://packagist.org/packages/florianv/exchanger)
[![Scrutinizer](https://img.shields.io/scrutinizer/g/florianv/exchanger.svg?style=flat-square)](https://scrutinizer-ci.com/g/florianv/exchanger)
[![Version](http://img.shields.io/packagist/v/florianv/exchanger.svg?style=flat-square)](https://packagist.org/packages/florianv/exchanger)

Exchanger is a PHP framework to work with currency exchange rates from various services such as
**[Fixer](https://apilayer.com/marketplace/fixer-api)**, **[Currency Data](https://apilayer.com/marketplace/currency_data-api)**,
**[Exchange Rates Data](https://apilayer.com/marketplace/exchangerates_data-api)** or **[Abstract](https://www.abstractapi.com)**.
Looking for a simple library based on Exchanger ? Check out [Swap](https://github.com/florianv/swap) !

## Sponsors

<table>
   <tr>
      <td><img src="https://assets.apilayer.com/apis/fixer.png" width="50px"/></td>
      <td><a href="https://apilayer.com/marketplace/fixer-api">Fixer</a> is a simple and lightweight API for foreign exchange rates that supports up to 170 world currencies.</td>
   </tr>
   <tr>
     <td><img src="https://assets.apilayer.com/apis/currency_data.png" width="50px"/></td>
     <td><a href="https://apilayer.com/marketplace/currency_data-api">Currency Data</a> provides reliable exchange rates and currency conversions for your business up to 168 world currencies.</td>
   </tr>
   <tr>
     <td><img src="https://assets.apilayer.com/apis/exchangerates_data.png" width="50px"/></td>
     <td><a href="https://apilayer.com/marketplace/exchangerates_data-api">Exchange Rates Data</a> provides reliable exchange rates and currency conversions for your business with over 15 data sources.</td>
   </tr>   
   <tr>
     <td><img src="https://global-uploads.webflow.com/5ebbd0a566a3996636e55959/5ec2ba29feeeb05d69160e7b_webclip.png" width="50px"/></td>
     <td><a href="https://www.abstractapi.com/">Abstract</a> provides simple exchange rates for developers and a dozen of APIs covering thousands of use cases.</td>
   </tr>  
</table>

## Documentation

The documentation for the current branch can be found [here](https://github.com/florianv/exchanger/blob/master/doc/readme.md).

## Services

Here is the complete list of the currently implemented services:

| Service | Base Currency | Quote Currency | Historical |
|---------------------------------------------------------------------------|----------------------|----------------|----------------|
| [Fixer](https://apilayer.com/marketplace/fixer-api) | EUR (free, no SSL), * (paid) | * | Yes |
| [Currency Data](https://apilayer.com/marketplace/currency_data-api) | USD (free), * (paid) | * | Yes |
| [Exchange Rates Data](https://apilayer.com/marketplace/exchangerates_data-api) | USD (free), * (paid) | * | Yes |
| [Abstract](https://www.abstractapi.com) | * | * | Yes |
| [coinlayer](https://coinlayer.com) | * Crypto (Limited standard currencies) | * Crypto (Limited standard currencies) | Yes |
| [European Central Bank](https://www.ecb.europa.eu/home/html/index.en.html) | EUR | * | Yes |
| [National Bank of Georgia](https://nbg.gov.ge) | * | GEL | Yes |
| [National Bank of the Republic of Belarus](https://www.nbrb.by) | * | BYN (from 01-07-2016),<br>BYR (01-01-2000 - 30-06-2016),<br>BYB (25-05-1992 - 31-12-1999) | Yes |
| [National Bank of Romania](http://www.bnr.ro) | RON, AED, AUD, BGN, BRL, CAD, CHF, CNY, CZK, DKK, EGP, EUR, GBP, HRK, HUF, INR, JPY, KRW, MDL, MXN, NOK, NZD, PLN, RSD, RUB, SEK, TRY, UAH, USD, XAU, XDR, ZAR | RON, AED, AUD, BGN, BRL, CAD, CHF, CNY, CZK, DKK, EGP, EUR, GBP, HRK, HUF, INR, JPY, KRW, MDL, MXN, NOK, NZD, PLN, RSD, RUB, SEK, TRY, UAH, USD, XAU, XDR, ZAR | Yes |
| [National Bank of Ukranie](https://bank.gov.ua) | * | UAH | Yes |
| [Central Bank of the Republic of Turkey](http://www.tcmb.gov.tr) | * | TRY | Yes |
| [Central Bank of the Republic of Uzbekistan](https://cbu.uz) | * | UZS | Yes |
| [Central Bank of the Czech Republic](https://www.cnb.cz) | * | CZK | Yes |
| [Central Bank of Russia](https://cbr.ru) | * | RUB | Yes |
| [Bulgarian National Bank](http://bnb.bg) | * | BGN | Yes |
| [WebserviceX](http://www.webservicex.net) | * | * | No |
| [1Forge](https://1forge.com) | * (free but limited or paid) | * (free but limited or paid) | No |
| [Cryptonator](https://www.cryptonator.com) | * Crypto (Limited standard currencies) | * Crypto (Limited standard currencies)  | No |
| [CurrencyDataFeed](https://currencydatafeed.com) | * (free but limited or paid) | * (free but limited or paid) | No |
| [Open Exchange Rates](https://openexchangerates.org) | USD (free), * (paid) | * | Yes |
| [Xignite](https://www.xignite.com) | * | * | Yes |
| [Currency Converter API](https://www.currencyconverterapi.com) | * | * | Yes (free but limited or paid) |
| [xChangeApi.com](https://xchangeapi.com) | * | * | Yes |
| [fastFOREX.io](https://www.fastforex.io) | USD (free), * (paid) | * | No |
| [exchangerate.host](https://www.exchangerate.host) | * | * | Yes |
| Array | * | * | Yes |

## Credits

- [Florian Voutzinos](https://github.com/florianv)
- [All Contributors](https://github.com/florianv/exchanger/contributors)

## License

The MIT License (MIT). Please see [LICENSE](https://github.com/florianv/exchanger/blob/master/LICENSE) for more information.
