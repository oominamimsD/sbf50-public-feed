# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-15T01:00:29Z**
- feed_generated_utc: 2026-10-15T01:00:32+00:00
- source_sha256: `2c24feaa5078672cd2cd9d35691e3f4b8ac51ec992fd34871ac37b410c69bc2f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-15T01:00+00:00, close=81624.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-15T01:00+00:00, close=81624.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-15T00:00+00:00, close=81639.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PONS_USDT|0.314500|-8.46|-23.38|-8.49|6925693|3.17|
|FET_USDT|0.198700|-4.51|-12.27|-4.54|10833811|5.02|
|BAT_USDT|0.169800|-3.83|71.23|-3.86|23341306|1.77|
|INJ_USDT|7.647000|-2.43|4.62|-2.46|31605727|1.31|
|FARTCOIN_USDT|0.153970|-2.15|-3.87|-2.18|7841981|0.65|
|PUMPFUN_USDT|0.004745|-2.12|-24.33|-2.15|21443643|2.11|
|AAVE_USDT|153.730000|-1.93|-10.49|-1.96|25276955|0.65|
|ENA_USDT|0.195390|-1.65|-14.35|-1.68|37417385|0.51|
|ZRO_USDT|1.905000|-1.06|-9.69|-1.09|9897110|0.53|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|153.730000|153.130000|153.730000|1.28|N|Y/Y|Y/Y|Y|N|
|BAT_USDT|0.169800|0.168840|0.169800|0.49|N|Y/Y|N/N|Y|N|
|ENA_USDT|0.195390|0.194750|0.195390|1.74|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.153970|0.154050|0.153970|1.47|Y|Y/Y|Y/Y|Y|Y|
|FET_USDT|0.198700|0.196700|0.198700|0.22|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.647000|7.609000|7.647000|1.04|N|Y/Y|Y/Y|Y|N|
|PONS_USDT|0.314500|0.316200|0.314500|0.72|N|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.004745|0.004718|0.004745|0.27|N|Y/Y|Y/Y|Y|N|
|ZRO_USDT|1.905000|1.885100|1.905000|0.88|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=154.460000, depth_time=2026-10-15T01:00:22+00:00, book20_bid_proxy_usdt=344922, book20_ask_proxy_usdt=326882, funding_indicative=0.000058, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=25276955. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=0.178290, depth_time=2026-10-15T01:00:12+00:00, book20_bid_proxy_usdt=22309, book20_ask_proxy_usdt=30704, funding_indicative=0.000023, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.83%, turnover=23341306. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=0.197920, depth_time=2026-10-15T01:00:25+00:00, book20_bid_proxy_usdt=120811, book20_ask_proxy_usdt=184763, funding_indicative=-0.000017, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.65%, turnover=37417385. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-15T01:00:01+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=0.157060, depth_time=2026-10-15T01:00:17+00:00, book20_bid_proxy_usdt=55765, book20_ask_proxy_usdt=56948, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.15%, turnover=7841981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=0.200000, depth_time=2026-10-15T01:00:09+00:00, book20_bid_proxy_usdt=1142040, book20_ask_proxy_usdt=857150, funding_indicative=0.000010, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.51%, turnover=10833811. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=7.699000, depth_time=2026-10-15T01:00:15+00:00, book20_bid_proxy_usdt=236364, book20_ask_proxy_usdt=239033, funding_indicative=0.000139, next_funding_utc=2026-10-15T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.43%, turnover=31605727. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PONS_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=0.337400, depth_time=2026-10-15T01:00:07+00:00, book20_bid_proxy_usdt=188340, book20_ask_proxy_usdt=180688, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.46%, turnover=6925693. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=0.004808, depth_time=2026-10-15T01:00:19+00:00, book20_bid_proxy_usdt=1641873, book20_ask_proxy_usdt=1519978, funding_indicative=0.000050, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.12%, turnover=21443643. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-15T01:00:00+00:00, last15m_closed_end=2026-10-15T01:00+00:00, prior8high=1.917600, depth_time=2026-10-15T01:00:27+00:00, book20_bid_proxy_usdt=26054, book20_ask_proxy_usdt=62231, funding_indicative=0.000023, next_funding_utc=2026-10-15T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.06%, turnover=9897110. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
