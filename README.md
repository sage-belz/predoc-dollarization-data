# Data for the pre-doctoral data exercise

This repo contains five files covering monthly and annual data from 31 emerging
market countries. The sample period is 2000 to 2020. The repo contains all the
data necessary to complete the assignment.

## Files

### `deposit_rates.csv`
| column | meaning |
|---|---|
| `iso3` | country, ISO 3166-1 alpha-3 |
| `date` | `YYYY-MM` |
| `i_lc` | interest rate on local-currency deposits, simple percent per annum |
| `i_fc` | interest rate on foreign-currency deposits, simple percent per annum |
| `fc_currency` | which foreign currency the country's foreign-currency deposits are denominated in |

### `exchange_rates.csv`
| column | meaning |
|---|---|
| `iso3`, `date` | as above |
| `e_usd` | local currency per US dollar |
| `e_eur` | local currency per euro |

### `prices.csv`
| column | meaning |
|---|---|
| `iso3`, `date` | as above |
| `cpi` | consumer price index, level |
| `cpi_source` | which series the index comes from |

### `gdp.csv`
| column | meaning |
|---|---|
| `iso3` | as above |
| `year` | `YYYY` |
| `ngdp` | GDP at current prices, local currency |
| `rgdp` | GDP at constant prices, local currency |

### `deposits.csv`
| column | meaning |
|---|---|
| `iso3`, `year` | as above |
| `dep_lc` | deposits denominated in local currency, **in local currency units** |
| `dep_fc` | deposits denominated in foreign currency, **in units of foreign currency** |
| `fc_currency` | which foreign currency that is |

## Notes

Coverage is uneven. Some countries start later than 2000 and a few series end
before 2020. The country panel is unbalanced by construction and you are not expected to make it balanced.

Deposit rates come from the IMF and national central banks. Exchange rates, GDP, and prices are derived from IMF data.    Deposits data are from national sources and international compilations.  

**These files were constructed for a teaching exercise. Do not use them for research.** 

## Sources

International Monetary Fund, Monetary and Financial Statistics, Exchange Rates
and Consumer Price Index databases; International Monetary Fund, World Economic
Outlook; Eduardo Levy Yeyati, *Financial Dollarizations and De-dollarizations in
the New Millennium*, Fondo Latinoamericano de Reservas (FLAR), 2020; and national
central banks and statistical offices.

---

<sup>This assignment was created by Sage Belz for the sole purpose of instruction and is not to be reproduced or distributed without permission from the author.</sup>
