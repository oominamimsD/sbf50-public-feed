# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-01T06:30:26Z**
- feed_generated_utc: 2026-11-01T06:30:28+00:00
- source_sha256: `04c65ea9aa4973407ca64fc4b47d873a2079ea3f61e6ae3817a423c116951d5b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-01T06:30+00:00, close=77922.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-01T06:00+00:00, close=77875.6, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-01T04:00+00:00, close=77753.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|LSK_USDT|0.233230|-21.24|38.89|-21.70|30912909|0.86|
|XPL_USDT|0.073470|-9.64|1.74|-10.10|5349178|2.72|
|BLESS_USDT|0.009597|-9.15|18.29|-9.61|6389689|2.08|
|ENA_USDT|0.188500|-2.84|0.91|-3.30|44098704|0.53|
|ZEC_USDT|1248.720000|-2.78|9.03|-3.24|950190186|0.16|
|NEAR_USDT|4.390000|-1.92|-0.27|-2.38|53459384|4.56|
|XLM_USDT|0.169250|-1.44|0.49|-1.90|20488570|0.59|
|BEAT_USDT|0.097900|-0.64|46.09|-1.10|6007116|1.02|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BEAT_USDT|0.097900|0.096700|0.097900|1.08|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009597|0.009421|0.009597|2.04|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.188500|0.186890|0.188500|2.34|N|Y/Y|Y/Y|Y|N|
|LSK_USDT|0.233230|0.232660|0.233230|0.70|N|Y/Y|N/N|Y|N|
|NEAR_USDT|4.390000|4.363000|4.390000|0.91|N|Y/Y|N/N|Y|N|
|XLM_USDT|0.169250|0.168140|0.169250|2.04|N|Y/Y|Y/N|Y|N|
|XPL_USDT|0.073470|0.069100|0.073480|1.19|N|Y/Y|N/N|Y|N|
|ZEC_USDT|1248.720000|1242.600000|1248.740000|1.13|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BEAT_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=0.099240, depth_time=2026-11-01T06:30:25+00:00, book20_bid_proxy_usdt=15468, book20_ask_proxy_usdt=13349, funding_indicative=0.000214, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.64%, turnover=6007116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=0.009802, depth_time=2026-11-01T06:30:13+00:00, book20_bid_proxy_usdt=20882, book20_ask_proxy_usdt=16712, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.15%, turnover=6389689. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=0.190590, depth_time=2026-11-01T06:30:15+00:00, book20_bid_proxy_usdt=181703, book20_ask_proxy_usdt=106916, funding_indicative=-0.000009, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.84%, turnover=44098704. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LSK_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=0.247730, depth_time=2026-11-01T06:30:08+00:00, book20_bid_proxy_usdt=5642, book20_ask_proxy_usdt=4143, funding_indicative=-0.002580, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-21.24%, turnover=30912909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=4.417000, depth_time=2026-11-01T06:30:20+00:00, book20_bid_proxy_usdt=3658038, book20_ask_proxy_usdt=3295085, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=53459384. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=0.169530, depth_time=2026-11-01T06:30:23+00:00, book20_bid_proxy_usdt=172463, book20_ask_proxy_usdt=137419, funding_indicative=0.000100, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=20488570. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XPL_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=0.086230, depth_time=2026-11-01T06:30:10+00:00, book20_bid_proxy_usdt=284927, book20_ask_proxy_usdt=325102, funding_indicative=0.000050, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.64%, turnover=5349178. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-01T06:30:01+00:00, last15m_closed_end=2026-11-01T06:30+00:00, prior8high=1254.790000, depth_time=2026-11-01T06:30:18+00:00, book20_bid_proxy_usdt=204084, book20_ask_proxy_usdt=688272, funding_indicative=-0.000127, next_funding_utc=2026-11-01T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=950190186. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
