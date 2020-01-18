# Singapore APIs 🇸🇬 [![Twitter: @jackveiga](https://img.shields.io/badge/contact-@jackveiga-red.svg?style=flat)](https://twitter.com/jackveiga) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-blue.svg?style=flat)](http://makeapullrequest.com)

This is an attempt to list all useful APIs available in Singapore for developers to use, open to anyone to contribute to.

# Table of Contents

* [Education](#education)
* [Environment](#environment)
* [Finance](#finance)
* [Transportation](#transportation)
* [Others](#others)

# APIs

### Education

API | Description | Auth | HTTPS | Link |
|---|---|---|---|---|
| **NUSMods** | Unofficial API for consolidating NUS module information. Modules are the NUS equivalent of courses | `apiKey` | Yes | [View](https://github.com/nusmodifications/nusmods-api) |

### Environment

API | Description | Auth | HTTPS | Link |
|---|---|---|---|---|
| **Rainfalls** | Rainfall readings across Singapore | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/rainfall) |
| **UV Index** | Latest UV index information | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/uv-index) |
| **Wind speed** | Wind speed readings across Singapore | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/wind-speed) |
| **Wind direction** | Wind direction readings across Singapore | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/wind-direction) |
| **2 Hours Weather Forecast** | Latest weather forecast for the next 2 hours | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/2-hour-weather-forecast) |
| **24 Hour Weather Forecast** | Latest 24 hour weather forecast | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/24-hour-weather-forecast) |
| **4 Day Weather Forecast** | Latest weather forecast for the next 4 days | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/4-day-weather-forecast) |
| **Air Temperature** | Air temperature readings across Singapore | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/air-temperature) |
| **Air Quality: PSI** | Latest PSI readings | No | Yes | [View](https://developers.data.gov.sg/environment/air-temperature) |
| **Air Quality: PM2.5** | Latest PM2.5 information retrieved hourly from NEA | `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/pm25) |
| **Humidity** | Relative humidity readings across Singapore| `apiKey` | Yes | [View](https://developers.data.gov.sg/environment/relative-humidity) |

### Finance

API | Description | Auth | HTTPS | Link |
|---|---|---|---|---|
| **DBS Deposits** | Generates list of deposit accounts | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/32) |
| **DBS Cards** | Enables customers to apply for a new debit card | `OAuth2` | Yes | [View](https://www.dbs.com/developers/index.html#/documentation/28) |
| **DBS Loans** | Enables customers to instantly evaluate their eligibility for loans | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/22) |
| **DBS Public Information** | Offers quick access to DBS' public information such as on DBS ATMs, branch details and articles | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/7) |
| **DBS Bill Payments** | Enables customers to settle payments electronically to credit cards, loans and other billing organizations | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/25) |
| **DBS Fund Transfers** | Allows customers to transfer money to their own account, third-party accounts or external accounts | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/5) |
| **DBS GIRO** | Facilitates GIRO arrangements with billing parties, including setting up, retrieving and managing automatic payments | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/23) |
| **DBS Payees** | Provides payee management functionalities such as adding new payees, retrieving payee details, and retrieving registered payee lists | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/3) |
| **DBS Paylah** |Allows partner merchants to make payment requests via PayLah! for online checkout | `OAuth2` | Yes | [View](https://www.dbs.com/developers/#/documentation/33) |
| **OCBC Authorization** | Enable OCBC Customers to grant develop app access to OCBC transactional APIs | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Authorization) |
| **OCBC Current Accounts** | Provides a list of OCBC Current Accounts | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Accounts_Current) |
| **OCBC Deposit Accounts** | Provides a list of OCBC deposit accounts for everyday deposits and withdrawals | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Deposit_Accounts) |
| **OCBC Savings Accounts** | Provides a list of OCBC Savings Accounts | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Accounts_Savings) |
| **OCBC Credit Card Advisor** | Provides credit card suggestions based on user's lifestyle | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=CCSuggestion) |
| **OCBC Cheque Status** | Check the status of an user's cheque | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Cheque_Status) |
| **OCBC ATM** | Provides a list of OCBC Bank ATMs with their location details to facilitate your users in finding them | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=ATM_Locator) |
| **OCBC Account Balance** | Provide a list of OCBC accounts and the balances your users have | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Transactional_AccountBalance) |
| **OCBC Account Transaction History** | Provides a list of customer account transaction history | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Transactional_AccountTransactionHistory) |
| **OCBC GIRO Sign Up** | Faster bill payments with GIRO Sign Up API | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Transactional_DirectDebitAuthorization) |
| **OCBC Pay Anyone** | Send money securely from your OCBC deposit account to anyone | `OAuth2` | Yes | [View](https://api.ocbc.com/store/site/pages/api_documentation.jag?name=Transactional_PayAnyone) |
| **CurrencyScoop** | Worldwide Currency Rates and Conversion API | `api_key` | Yes | [View](https://currencyscoop.com/api-documentation) |

### Transportation

API | Description | Auth | HTTPS | Link |
|---|---|---|---|---|
| **MRT API** | SMRT train stations live train arrival timings 💰 | `apiKey` | Yes | [View](https://mrtapi.com/) |
| **ArriveLah** | Fast simple API for bus arrival times| `apiKey` | Yes | [View](https://github.com/cheeaun/arrivelah) |
| **Taxi Availability** | Locations of available taxis| `apiKey` | Yes | [View](https://developers.data.gov.sg/transport/taxi-availability) |
| **Traffic Images** | Latest images from traffic cameras all around Singapore | `apiKey` | Yes | [View](https://developers.data.gov.sg/transport/traffic-images) |
| **Car Park Availability** | Latest carpark availability| `apiKey` | Yes | [View](https://developers.data.gov.sg/data-gov-sg-apis/apis/get/transport/carpark-availability) |

### Others

API | Description | Auth | HTTPS | Link |
|---|---|---|---|---|
| **IRAS** | Organization search, stamp duty calculator, GST register.. | `apiKey` | Yes | [View](https://apiservices.iras.gov.sg/iras/devportal/product) |
| **One Map 2.0** | Singapore Land Authority REST API services for Singapore addresses | `apiKey` | Yes | [View](https://docs.onemap.sg/) |
| **Calendarific** | Allows developers to fetch dates of national, bank, public holidays and observances in their applications | `apiKey` | Yes | [View](https://calendarific.com) |

### Contributions

Pull requests are welcome. Please follow the [guidelines](https://github.com/jackveiga/singapore-apis/blob/master/CONTRIBUTING.md).

# License

<a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
