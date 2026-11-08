# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T02:30:26Z**
- feed_generated_utc: 2026-11-08T02:30:27+00:00
- source_sha256: `d0d3b3bab5dded541303c76b9167ecc910e4abad698eebbff0aad872a2a7849b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T02:30+00:00, close=75700.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T02:00+00:00, close=75713.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T00:00+00:00, close=75836.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AIN_USDT|0.142780|-8.34|-38.49|-8.31|9570750|1.40|
|ONE_USDT|0.001967|-3.41|67.53|-3.38|26655061|0.51|
|QNT_USDT|193.870000|-2.50|-3.57|-2.47|43096549|0.52|
|ENA_USDT|0.155420|-1.74|-19.89|-1.71|27796562|0.64|
|WLD_USDT|0.330600|-1.48|-18.24|-1.45|25543173|3.02|
|PEPE_USDT|0.000005|-1.23|-2.91|-1.20|38782902|1.66|
|TIA_USDT|0.436800|-1.08|-10.87|-1.05|7035188|2.29|
|ZEC_USDT|1244.500000|-1.05|-3.11|-1.02|1801395751|0.08|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AIN_USDT|0.142780|0.142030|0.142790|0.50|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.155420|0.155120|0.155420|0.55|N|Y/Y|Y/Y|Y|N|
|ONE_USDT|0.001967|0.001939|0.001967|0.45|N|Y/Y|N/N|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.91|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|193.870000|193.700000|193.870000|0.39|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.436800|0.435700|0.436800|1.81|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.330600|0.330100|0.330600|1.03|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1244.500000|1239.010000|1244.500000|1.21|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AIN_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=0.146520, depth_time=2026-11-08T02:30:07+00:00, book20_bid_proxy_usdt=9584, book20_ask_proxy_usdt=9293, funding_indicative=0.000271, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-8.34%, turnover=9570750. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=0.158290, depth_time=2026-11-08T02:30:15+00:00, book20_bid_proxy_usdt=254213, book20_ask_proxy_usdt=216542, funding_indicative=-0.000064, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.74%, turnover=27796562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=0.002149, depth_time=2026-11-08T02:30:10+00:00, book20_bid_proxy_usdt=8119, book20_ask_proxy_usdt=10768, funding_indicative=-0.000084, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.41%, turnover=26655061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=0.000005, depth_time=2026-11-08T02:30:20+00:00, book20_bid_proxy_usdt=55352, book20_ask_proxy_usdt=51861, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.23%, turnover=38782902. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=196.400000, depth_time=2026-11-08T02:30:11+00:00, book20_bid_proxy_usdt=64388, book20_ask_proxy_usdt=77454, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.50%, turnover=43096549. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=0.439600, depth_time=2026-11-08T02:30:22+00:00, book20_bid_proxy_usdt=330563, book20_ask_proxy_usdt=351184, funding_indicative=0.000021, next_funding_utc=2026-11-08T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.08%, turnover=7035188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=0.333700, depth_time=2026-11-08T02:30:10+00:00, book20_bid_proxy_usdt=3336334, book20_ask_proxy_usdt=3992425, funding_indicative=-0.000101, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.48%, turnover=25543173. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T02:30:00+00:00, last15m_closed_end=2026-11-08T02:30+00:00, prior8high=1258.450000, depth_time=2026-11-08T02:30:25+00:00, book20_bid_proxy_usdt=352405, book20_ask_proxy_usdt=98420, funding_indicative=0.000100, next_funding_utc=2026-11-08T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.05%, turnover=1801395751. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
