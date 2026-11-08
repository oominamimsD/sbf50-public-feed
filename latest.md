# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T21:30:25Z**
- feed_generated_utc: 2026-11-08T21:30:26+00:00
- source_sha256: `ed3e8cf447ef6a25075d337467559d8bb1f7d27194df712f4d4a29679c1b965a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T21:30+00:00, close=75674.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-08T21:00+00:00, close=75718.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-08T20:00+00:00, close=75894.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ONE_USDT|0.001665|-14.98|42.94|-14.51|14513929|0.60|
|ZEC_USDT|1226.400000|-3.48|-0.92|-3.01|1506842969|0.08|
|NEAR_USDT|3.599000|-2.75|-16.90|-2.28|32299070|2.78|
|LIT_USDT|3.112400|-2.53|-3.64|-2.06|7414760|0.32|
|HYPE_USDT|75.960000|-1.89|-13.37|-1.42|23707402|0.26|
|TRUMPOFFICIAL_USDT|1.168000|-1.76|-31.93|-1.29|5004337|8.56|
|WLD_USDT|0.320800|-1.56|-18.92|-1.09|23297188|3.12|
|ARB_USDT|0.167320|-1.51|0.68|-1.04|18138516|0.60|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ARB_USDT|0.167320|0.166560|0.167320|1.00|N|Y/Y|N/N|Y|N|
|HYPE_USDT|75.960000|76.095000|75.960000|2.38|Y|Y/Y|Y/Y|Y|Y|
|LIT_USDT|3.112400|3.163600|3.112500|8.06|Y|Y/Y|Y/Y|Y|Y|
|NEAR_USDT|3.599000|3.606000|3.599000|2.59|Y|Y/Y|Y/Y|Y|Y|
|ONE_USDT|0.001665|0.001667|0.001665|1.03|N|Y/Y|N/N|Y|N|
|TRUMPOFFICIAL_USDT|1.168000|1.166000|1.168000|0.05|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.320800|0.319600|0.320800|0.64|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1226.400000|1237.310000|1226.460000|1.57|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- ARB_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=0.167590, depth_time=2026-11-08T21:30:22+00:00, book20_bid_proxy_usdt=67579, book20_ask_proxy_usdt=122814, funding_indicative=-0.000001, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.51%, turnover=18138516. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=77.158000, depth_time=2026-11-08T21:30:16+00:00, book20_bid_proxy_usdt=36614, book20_ask_proxy_usdt=111496, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.89%, turnover=23707402. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=3.212800, depth_time=2026-11-08T21:30:14+00:00, book20_bid_proxy_usdt=22574, book20_ask_proxy_usdt=27738, funding_indicative=0.000050, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=7414760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=3.666000, depth_time=2026-11-08T21:30:12+00:00, book20_bid_proxy_usdt=3550745, book20_ask_proxy_usdt=3157582, funding_indicative=0.000100, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=32299070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=0.001808, depth_time=2026-11-08T21:30:06+00:00, book20_bid_proxy_usdt=9546, book20_ask_proxy_usdt=20646, funding_indicative=-0.000079, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-14.98%, turnover=14513929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=1.179000, depth_time=2026-11-08T21:30:18+00:00, book20_bid_proxy_usdt=2001846, book20_ask_proxy_usdt=2449775, funding_indicative=-0.000120, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.76%, turnover=5004337. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=0.324400, depth_time=2026-11-08T21:30:20+00:00, book20_bid_proxy_usdt=3950930, book20_ask_proxy_usdt=3943696, funding_indicative=-0.000053, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=23297188. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-08T21:30:01+00:00, last15m_closed_end=2026-11-08T21:30+00:00, prior8high=1268.660000, depth_time=2026-11-08T21:30:09+00:00, book20_bid_proxy_usdt=87865, book20_ask_proxy_usdt=149026, funding_indicative=0.000024, next_funding_utc=2026-11-09T00:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=1506842969. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
