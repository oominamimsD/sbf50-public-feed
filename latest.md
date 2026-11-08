# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T12:45:31Z**
- feed_generated_utc: 2026-11-08T12:45:33+00:00
- source_sha256: `9e933d20742acd9a205912b64045c49f21212424bd5ce2bd8c828958735f6560`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T12:45+00:00, close=75892.9, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.030324|-8.92|73.07|-9.14|16374942|4.62|
|ONE_USDT|0.001906|-6.41|62.33|-6.63|25406005|0.53|
|TIA_USDT|0.422000|-4.43|-13.89|-4.65|7015240|2.37|
|ENA_USDT|0.152980|-3.28|-21.14|-3.50|30102241|1.31|
|WLD_USDT|0.325700|-2.94|-19.46|-3.16|23939226|3.07|
|AAVE_USDT|130.030000|-1.66|-4.04|-1.88|9696333|0.77|
|LINK_USDT|10.709000|-1.24|-7.44|-1.46|63625379|1.87|
|ADA_USDT|0.179900|-0.93|-7.07|-1.15|9992132|5.56|
|SUI_USDT|0.849700|-0.86|-5.79|-1.08|23171376|1.18|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.030000|129.850000|130.030000|0.80|N|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179900|0.179300|0.179900|3.21|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.152980|0.152210|0.152980|3.87|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030324|0.027111|0.030324|1.61|N|Y/N|N/N|Y|N|
|LINK_USDT|10.709000|10.718000|10.709000|2.31|Y|N/Y|Y/Y|Y|N|
|ONE_USDT|0.001906|0.001872|0.001906|0.41|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.849700|0.846400|0.849600|2.04|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.422000|0.422800|0.422000|4.09|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.325700|0.326600|0.325700|4.63|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=131.250000, depth_time=2026-11-08T12:45:22+00:00, book20_bid_proxy_usdt=437355, book20_ask_proxy_usdt=692039, funding_indicative=0.000064, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=9696333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=0.181000, depth_time=2026-11-08T12:45:27+00:00, book20_bid_proxy_usdt=10143770, book20_ask_proxy_usdt=10415220, funding_indicative=-0.000029, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.93%, turnover=9992132. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=0.155490, depth_time=2026-11-08T12:45:17+00:00, book20_bid_proxy_usdt=202747, book20_ask_proxy_usdt=250032, funding_indicative=-0.000016, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=30102241. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=0.033952, depth_time=2026-11-08T12:45:08+00:00, book20_bid_proxy_usdt=6228, book20_ask_proxy_usdt=12744, funding_indicative=0.000632, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.92%, turnover=16374942. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=10.807000, depth_time=2026-11-08T12:45:23+00:00, book20_bid_proxy_usdt=656977, book20_ask_proxy_usdt=347549, funding_indicative=0.000007, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.24%, turnover=63625379. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=0.002063, depth_time=2026-11-08T12:45:11+00:00, book20_bid_proxy_usdt=11375, book20_ask_proxy_usdt=13456, funding_indicative=-0.001058, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.41%, turnover=25406005. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=0.855800, depth_time=2026-11-08T12:45:27+00:00, book20_bid_proxy_usdt=1873105, book20_ask_proxy_usdt=1275493, funding_indicative=0.000035, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.86%, turnover=23171376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=0.427700, depth_time=2026-11-08T12:45:14+00:00, book20_bid_proxy_usdt=291558, book20_ask_proxy_usdt=329415, funding_indicative=-0.000041, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.43%, turnover=7015240. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T12:44:59+00:00, last15m_closed_end=2026-11-08T12:45+00:00, prior8high=0.330100, depth_time=2026-11-08T12:45:19+00:00, book20_bid_proxy_usdt=3688231, book20_ask_proxy_usdt=4042025, funding_indicative=-0.000075, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.94%, turnover=23939226. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
