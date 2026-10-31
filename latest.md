# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T00:30:22Z**
- feed_generated_utc: 2026-10-31T00:30:24+00:00
- source_sha256: `4e2f0ff0812b356177c8a3f7884b026c9b6adfea404e03f0b4c2d96543b4bb17`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1199; contracts: 1191; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T00:30+00:00, close=77270, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-31T00:00+00:00, close=77313.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.013941|-26.31|-60.16|-25.92|5831334|2.86|
|EVAA_USDT|1.164600|-9.16|121.87|-8.77|6700061|1.72|
|BTW_USDT|1.140600|-4.91|-33.00|-4.52|9778281|3.51|
|TRX_USDT|0.326380|-2.71|-0.89|-2.32|9706634|0.31|
|HYPE_USDT|90.023000|-2.51|14.81|-2.12|139818466|0.11|
|XMR_USDT|591.290000|-1.70|-2.58|-1.31|9982609|0.17|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.013941|0.013043|0.013941|0.27|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.140600|1.135400|1.141300|0.68|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.164600|1.105200|1.164600|1.23|N|Y/Y|N/N|Y|N|
|HYPE_USDT|90.023000|89.059000|90.000000|1.71|N|Y/Y|N/N|Y|N|
|TRX_USDT|0.326380|0.325930|0.326280|1.05|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|591.290000|588.230000|591.300000|1.19|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-31T00:30:03+00:00, last15m_closed_end=2026-10-31T00:30+00:00, prior8high=0.014277, depth_time=2026-10-31T00:30:08+00:00, book20_bid_proxy_usdt=5072, book20_ask_proxy_usdt=7796, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-26.31%, turnover=5831334. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-31T00:30:03+00:00, last15m_closed_end=2026-10-31T00:30+00:00, prior8high=1.170200, depth_time=2026-10-31T00:30:13+00:00, book20_bid_proxy_usdt=17414, book20_ask_proxy_usdt=11403, funding_indicative=-0.000244, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-4.91%, turnover=9778281. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-31T00:30:03+00:00, last15m_closed_end=2026-10-31T00:30+00:00, prior8high=1.161600, depth_time=2026-10-31T00:30:11+00:00, book20_bid_proxy_usdt=4001, book20_ask_proxy_usdt=5574, funding_indicative=0.000179, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-9.16%, turnover=6700061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-10-31T00:30:03+00:00, last15m_closed_end=2026-10-31T00:30+00:00, prior8high=90.278000, depth_time=2026-10-31T00:30:17+00:00, book20_bid_proxy_usdt=239208, book20_ask_proxy_usdt=29934, funding_indicative=0.000050, next_funding_utc=2026-10-31T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.51%, turnover=139818466. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T00:30:03+00:00, last15m_closed_end=2026-10-31T00:30+00:00, prior8high=0.331360, depth_time=2026-10-31T00:30:14+00:00, book20_bid_proxy_usdt=76287, book20_ask_proxy_usdt=60796, funding_indicative=-0.000628, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.71%, turnover=9706634. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-31T00:30:03+00:00, last15m_closed_end=2026-10-31T00:30+00:00, prior8high=593.400000, depth_time=2026-10-31T00:30:20+00:00, book20_bid_proxy_usdt=16661, book20_ask_proxy_usdt=5065, funding_indicative=0.000526, next_funding_utc=2026-10-31T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.70%, turnover=9982609. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
