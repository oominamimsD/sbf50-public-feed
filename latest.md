# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T03:15:31Z**
- feed_generated_utc: 2026-10-31T03:15:33+00:00
- source_sha256: `cf0c075ee8d3fd0dd8a088d37dac5f1557faebd01a88d05611b344d3d5d37392`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T03:15+00:00, close=77272.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T03:00+00:00, close=77402.4, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.011453|-39.46|-67.27|-39.07|6784755|2.62|
|Q_USDT|0.029600|-37.65|-74.98|-37.26|20043217|6.75|
|BTW_USDT|1.142200|-4.77|-32.90|-4.38|9692260|2.62|
|BEAT_USDT|0.100170|-4.73|37.99|-4.34|8759809|2.00|
|BLESS_USDT|0.009523|-3.32|16.68|-2.93|12575382|1.05|
|EVAA_USDT|1.240600|-3.23|136.34|-2.84|6588919|2.43|
|HYPE_USDT|89.507000|-3.07|14.16|-2.68|115459794|0.11|
|TRX_USDT|0.325360|-3.02|-1.20|-2.63|7697906|0.31|
|PEPE_USDT|0.000005|-2.98|0.99|-2.59|143087493|2.03|
|LIT_USDT|2.760300|-2.26|-16.95|-1.87|5955389|0.36|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.011453|0.011438|0.011469|1.24|N|Y/Y|Y/Y|Y|N|
|BEAT_USDT|0.100170|0.096210|0.100220|1.49|N|Y/Y|N/N|Y|N|
|BLESS_USDT|0.009523|0.009190|0.009523|1.70|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.142200|1.107500|1.142200|1.00|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.240600|1.106900|1.235600|2.27|N|N/Y|N/N|Y|N|
|HYPE_USDT|89.507000|89.156000|89.507000|0.90|N|Y/Y|N/N|Y|N|
|LIT_USDT|2.760300|2.751900|2.758600|1.87|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.77|N|Y/Y|N/N|Y|N|
|Q_USDT|0.029600|0.028320|0.029250|4.14|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.325360|0.321930|0.325270|1.86|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=0.013378, depth_time=2026-10-31T03:15:09+00:00, book20_bid_proxy_usdt=16556, book20_ask_proxy_usdt=5740, funding_indicative=-0.000081, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-39.46%, turnover=6784755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=0.104450, depth_time=2026-10-31T03:15:16+00:00, book20_bid_proxy_usdt=11621, book20_ask_proxy_usdt=7194, funding_indicative=0.000134, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.73%, turnover=8759809. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BLESS_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=0.009692, depth_time=2026-10-31T03:15:18+00:00, book20_bid_proxy_usdt=8380, book20_ask_proxy_usdt=15505, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.32%, turnover=12575382. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=1.291900, depth_time=2026-10-31T03:15:13+00:00, book20_bid_proxy_usdt=13044, book20_ask_proxy_usdt=12159, funding_indicative=-0.000365, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.77%, turnover=9692260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=1.292600, depth_time=2026-10-31T03:15:21+00:00, book20_bid_proxy_usdt=2849, book20_ask_proxy_usdt=2525, funding_indicative=0.000145, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=6588919. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=90.160000, depth_time=2026-10-31T03:15:22+00:00, book20_bid_proxy_usdt=233104, book20_ask_proxy_usdt=41155, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=115459794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=2.792700, depth_time=2026-10-31T03:15:29+00:00, book20_bid_proxy_usdt=31962, book20_ask_proxy_usdt=24434, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=5955389. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=0.000005, depth_time=2026-10-31T03:15:28+00:00, book20_bid_proxy_usdt=41670, book20_ask_proxy_usdt=23428, funding_indicative=-0.000215, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.98%, turnover=143087493. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=0.042830, depth_time=2026-10-31T03:15:11+00:00, book20_bid_proxy_usdt=33293, book20_ask_proxy_usdt=25560, funding_indicative=-0.020000, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-37.65%, turnover=20043217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T03:15:03+00:00, last15m_closed_end=2026-10-31T03:15+00:00, prior8high=0.327100, depth_time=2026-10-31T03:15:22+00:00, book20_bid_proxy_usdt=36617, book20_ask_proxy_usdt=39679, funding_indicative=-0.001675, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=7697906. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
