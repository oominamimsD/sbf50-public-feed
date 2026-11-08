# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T12:30:23Z**
- feed_generated_utc: 2026-11-08T12:30:24+00:00
- source_sha256: `6429bc54e1279912c92a2ae19d16184a16c974d59be70f842ac27add0b2e7acc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T12:30+00:00, close=75948, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030016|-9.85|71.31|-10.14|16303190|3.00|
|ONE_USDT|0.001917|-5.86|63.29|-6.15|25322613|0.52|
|TIA_USDT|0.423400|-4.12|-13.60|-4.41|6799750|2.36|
|ENA_USDT|0.153920|-2.69|-20.66|-2.98|29474391|0.65|
|WLD_USDT|0.326700|-2.65|-19.21|-2.94|22960363|3.06|
|AAVE_USDT|130.340000|-1.42|-3.81|-1.71|9657882|0.77|
|LINK_USDT|10.753000|-0.83|-7.06|-1.12|62805996|0.93|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.340000|129.850000|130.340000|0.72|N|Y/Y|Y/N|Y|N|
|ENA_USDT|0.153920|0.152210|0.153920|0.95|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030016|0.027111|0.030016|1.99|N|Y/N|N/N|Y|N|
|LINK_USDT|10.753000|10.718000|10.752000|1.87|N|N/Y|Y/Y|Y|N|
|ONE_USDT|0.001917|0.001872|0.001917|0.29|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.423400|0.422800|0.423300|1.50|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.326700|0.327300|0.326700|1.89|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T12:30:00+00:00, last15m_closed_end=2026-11-08T12:30+00:00, prior8high=131.250000, depth_time=2026-11-08T12:30:19+00:00, book20_bid_proxy_usdt=337433, book20_ask_proxy_usdt=335249, funding_indicative=0.000059, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.42%, turnover=9657882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T12:30:00+00:00, last15m_closed_end=2026-11-08T12:30+00:00, prior8high=0.155490, depth_time=2026-11-08T12:30:14+00:00, book20_bid_proxy_usdt=345798, book20_ask_proxy_usdt=261933, funding_indicative=-0.000002, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.69%, turnover=29474391. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T12:30:00+00:00, last15m_closed_end=2026-11-08T12:30+00:00, prior8high=0.033952, depth_time=2026-11-08T12:30:07+00:00, book20_bid_proxy_usdt=3668, book20_ask_proxy_usdt=4574, funding_indicative=0.000597, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.85%, turnover=16303190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T12:30:00+00:00, last15m_closed_end=2026-11-08T12:30+00:00, prior8high=10.807000, depth_time=2026-11-08T12:30:22+00:00, book20_bid_proxy_usdt=572933, book20_ask_proxy_usdt=409812, funding_indicative=0.000017, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.83%, turnover=62805996. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T12:30:00+00:00, last15m_closed_end=2026-11-08T12:30+00:00, prior8high=0.002128, depth_time=2026-11-08T12:30:09+00:00, book20_bid_proxy_usdt=8823, book20_ask_proxy_usdt=14121, funding_indicative=-0.001142, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.86%, turnover=25322613. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T12:30:00+00:00, last15m_closed_end=2026-11-08T12:30+00:00, prior8high=0.427700, depth_time=2026-11-08T12:30:12+00:00, book20_bid_proxy_usdt=290923, book20_ask_proxy_usdt=358552, funding_indicative=-0.000032, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.12%, turnover=6799750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T12:30:00+00:00, last15m_closed_end=2026-11-08T12:30+00:00, prior8high=0.330100, depth_time=2026-11-08T12:30:17+00:00, book20_bid_proxy_usdt=3875797, book20_ask_proxy_usdt=3791212, funding_indicative=-0.000061, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=22960363. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
