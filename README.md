# Awesome Market Data Resources

A practical directory for researching commodities, electronic components, and shipbuilding markets, with a visual guide to the free price-history and analysis tools on **Market Pulse Scope**.

[**Explore Market Pulse Scope**](https://marketpulsescope.com/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources) · [**Try the free tools**](https://marketpulsescope.com/tools/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources) · [**Feature guide with screenshots**](docs/market-pulse-scope.md) · [**Data resource directory**](#start-here-a-defensible-research-workflow)

## Featured: Market Pulse Scope

**From price lookup to price analysis.**

Browse available historical prices online for free, compare market trends, work through purchasing calculations, and convert price units and currencies in your browser.

Market Pulse Scope covers commodities, electronic components, and shipbuilding prices. Coverage and available history vary by product and region. The site supports English, Chinese, Japanese, Spanish, Korean, and French.

This directory is maintained by the creator of Market Pulse Scope. The website is featured here as an independently developed research tool, not as an endorsement by any resource listed below.

![Market Pulse Scope homepage with free tool links, weekly movers, commodity prices, market news, and five-year recorded-price watch](assets/marketpulsescope-home-tools.png)

*Local application preview captured in October 2026. Quotes are dated observations, not a live market feed; production appearance and data may differ.*

### Five free price analysis tools

| Tool | What you can do | Open |
| --- | --- | --- |
| **Price Trend Comparison** | Compare up to five markets in one chart. Switch between actual prices and cumulative percentage changes. | [Compare trends](https://marketpulsescope.com/tools/price-trend-comparison/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources) |
| **Commodity Price Converter** | Convert price units and currencies. Use reference or manual FX, and explicit physical assumptions where needed. | [Convert a price](https://marketpulsescope.com/tools/commodity-price-converter/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources) |
| **Commodity Price Calculator** | Calculate purchase costs from quantity, unit price, and optional freight. | [Calculate a cost](https://marketpulsescope.com/tools/commodity-price-calculator/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources) |
| **Historical Price Comparison** | Compare two quote dates or overlay two historical periods on one elapsed-time chart. | [Compare history](https://marketpulsescope.com/tools/historical-price-comparison/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources) |
| **Price Change Calculator** | Calculate absolute and percentage price changes from entered values or available recorded quotes. | [Calculate a change](https://marketpulsescope.com/tools/price-change-calculator/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources) |

![Price Trend Comparison showing copper and silver cumulative percentage changes over the same historical period](assets/marketpulsescope-trend-comparison.png)

*Compare recorded movements, not forecasts. Normalized percentage changes share a baseline; actual prices can use separate scales when units or currencies differ.*

[**See every tool with screenshots and example workflows**](docs/market-pulse-scope.md)

### More than a chart

- **Historical prices:** inspect available dated observations, zoom and pan through charts, and switch between regions when quoted data is available.
- **Five-year price watch:** explore commodities near their recorded five-year high or low, with separate high/low views. This uses available regional observations, not a guarantee of complete market history or a trading signal.
- **Weekly movers:** scan gainers and losers alongside price tables and compact trend charts.
- **Search and context:** search prices and onsite news, and follow market developments alongside the data.
- **Personal watchlist:** keep selected markets close at hand, with account-linked selections for signed-in users.

### Free access, clear limits

Online viewing of available price history and use of the five tools are currently free. CSV downloads still require an account and are subject to the website's daily limits. Free viewing does not grant rights to bulk scraping, database copying, or commercial redistribution. Read the [data-use terms](https://marketpulsescope.com/data-license).

Calculations are for reference, not market quotations or financial or purchasing advice. Data may be delayed, incomplete, or inaccurate. This repository does **not** publish a price dataset, database, website source code, API credentials, or scraping code.

The resource directory below complements the website with official datasets, standards bodies, industry associations, exchanges, and filings. Consult original publishers and their current terms before relying on a figure.

## Start here: a defensible research workflow

1. **Define the observation.** Record the product, geography, unit, currency, market layer (spot, contract, producer, import, or retail), and time zone.
2. **Prefer the original publisher.** Use a government agency, standards body, exchange, company filing, or industry association before an aggregator.
3. **Read the methodology.** Note sampling, revisions, seasonal adjustment, taxes, freight, and whether the series is an index or a level.
4. **Triangulate.** Confirm an important claim with an independent source that measures a different part of the market.
5. **Preserve provenance.** Save the URL, publication date, access date, unit, and transformation steps with every chart or conclusion.

## Cross-market and macro data

| Resource | Best for | Access notes |
|---|---|---|
| [FRED](https://fred.stlouisfed.org/) | Discovering and charting economic time series from many official publishers | Free; inspect each series page for the original source, units, frequency, and revisions |
| [U.S. Bureau of Labor Statistics Data](https://www.bls.gov/data/) | Producer prices, import/export prices, employment, and productivity | Free; API and downloadable tables are available |
| [U.S. Bureau of Economic Analysis](https://www.bea.gov/data) | GDP, industry accounts, trade in value added, and input-output context | Free; API and release calendars are available |
| [World Bank Commodity Markets](https://www.worldbank.org/en/research/commodity-markets) | Pink Sheet monthly and annual commodity series plus the Commodity Markets Outlook | Free downloads; check dataset terms and revision dates |
| [IMF Primary Commodity Prices](https://www.imf.org/en/Research/commodity-prices) | Monthly international commodity series, country indices, and methodology | Free; documentation and downloadable workbooks are provided |
| [OECD Data Explorer](https://data-explorer.oecd.org/) | Cross-country indicators, industrial activity, trade, and leading indicators | Free; confirm dataset-specific licensing and update schedules |
| [UN Comtrade](https://comtradeplus.un.org/) | Product-level international merchandise trade by reporter and partner | Free tiers and APIs; classification changes can break long time series |

## Semiconductors and electronics

| Resource | Best for | Access notes |
|---|---|---|
| [World Semiconductor Trade Statistics](https://www.wsts.org/) | Global semiconductor billings, historical tables, and industry forecasts | Some historical reports are free; detailed products may require membership |
| [Semiconductor Industry Association Resources](https://www.semiconductors.org/resources/) | Policy reports, industry overviews, supply-chain analysis, and links to WSTS releases | Free public reports |
| [SEMI Market Data](https://www.semi.org/en/products-services/market-data) | Fab capacity, equipment, materials, packaging, and manufacturing outlooks | Mix of public summaries and paid products |
| [U.S. Census Manufacturers' Shipments, Inventories, and Orders](https://www.census.gov/manufacturing/m3/) | Monthly manufacturing orders, shipments, and inventories, including electronics categories | Free; use category definitions carefully |
| [FRED: Semiconductor and Related Device Manufacturing PPI](https://fred.stlouisfed.org/series/PCU334413334413) | A U.S. producer-price index for the semiconductor manufacturing industry | Free; this is an index, not a chip spot-price series |
| [SEC EDGAR](https://www.sec.gov/edgar/search/) | Filings from listed semiconductor, equipment, and electronics companies | Free; company statements should be treated as issuer disclosures, not independent estimates |
| [JEDEC Standards](https://www.jedec.org/standards-documents) | Definitions and standards for memory devices, modules, packaging, and interfaces | Many documents are accessible after free registration; respect document terms |

## Energy, metals, and agriculture

| Resource | Best for | Access notes |
|---|---|---|
| [U.S. Energy Information Administration Open Data](https://www.eia.gov/opendata/) | Petroleum, natural gas, coal, electricity, inventories, and forecasts | Free; API registration may be required |
| [International Energy Agency Data](https://www.iea.org/data-and-statistics) | Global energy balances, demand, supply, and transition indicators | Mix of free and licensed datasets |
| [USGS National Minerals Information Center](https://www.usgs.gov/centers/national-minerals-information-center) | Mineral production, trade, consumption, and commodity summaries | Free public reports and datasets |
| [USDA WASDE](https://www.usda.gov/about-usda/general-information/staff-offices/office-chief-economist/commodity-markets/wasde-report) | Monthly global supply-and-demand balances for major agricultural commodities | Free; revisions and marketing-year definitions matter |
| [USDA Quick Stats](https://quickstats.nass.usda.gov/) | U.S. crop, livestock, acreage, yield, and production observations | Free account and API key may be required |
| [CFTC Commitments of Traders](https://www.cftc.gov/MarketReports/CommitmentsofTraders/index.htm) | Futures positioning by trader category | Free; not a direct measure of physical supply or demand |
| [London Metal Exchange](https://www.lme.com/en/Market-data) | Exchange notices, contracts, warehouse context, and selected market data | Real-time and historical depth varies by product and license |

## Shipping and shipbuilding

| Resource | Best for | Access notes |
|---|---|---|
| [UNCTAD Review of Maritime Transport](https://unctad.org/topic/transport-and-trade-logistics/review-of-maritime-transport) | Seaborne trade, fleet structure, shipbuilding, demolitions, ports, and connectivity | Free annual flagship report with extensive statistics |
| [UNCTADstat](https://unctadstat.unctad.org/) | Maritime profiles, liner shipping connectivity, trade, and development indicators | Free; definitions are published with datasets |
| [International Maritime Organization](https://www.imo.org/) | Global shipping regulation, safety, emissions, and implementation documents | Free public material; some standards are sold separately |
| [U.S. Maritime Administration Data and Reports](https://www.maritime.dot.gov/data-reports) | U.S. fleet, ports, trade, shipbuilding, and maritime program data | Free public datasets and reports |
| [Baltic Exchange](https://www.balticexchange.com/en/data-services/market-information0.html) | Benchmark methodology and freight-market information | Many benchmark values and histories are licensed |

## A quick source-quality checklist

Before using a series, ask:

- Who publishes it, and who originally collected it?
- Is it a price level, index, quote, transaction average, forecast, or survey balance?
- Do the unit, geography, product specification, currency, and tax/freight treatment match the question?
- Is the observation preliminary, revised, seasonally adjusted, or backfilled?
- Are redistribution and commercial use permitted?
- Can an independent source confirm the direction or underlying driver?

## Return to the market monitor

[**Continue research on Market Pulse Scope →**](https://marketpulsescope.com/?utm_source=github&utm_medium=referral&utm_campaign=awesome_market_data_resources)

No Market Pulse Scope dataset is mirrored in this repository; the link takes you to the live website.

## Contributing

Suggestions are welcome when a resource has a clear publisher, durable URL, documented methodology, and legitimate public or licensed access. Please describe the publisher, coverage, frequency, access model, and why the source is useful. Do not submit copied datasets, paywalled material, credentials, confidential documents, affiliate links, or unverified price claims.

## Disclaimer

This directory is for research and education. Inclusion does not imply endorsement. Availability, licensing, and methodology can change. Always review the publisher's current terms and documentation. Nothing here is financial, investment, procurement, or trading advice.


