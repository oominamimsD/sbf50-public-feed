# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T18:45:14Z**
- feed_generated_utc: 2026-11-05T18:45:15+00:00
- source_sha256: `0597004c3aab9e9e739c706f0f1e19bb8c211c139344e6e60bee4b45559893e5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T18:45+00:00, close=76175.9, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T18:00+00:00, close=75920.2, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-05T16:00+00:00, close=76013.2, belowEMA20=True, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002323|-9.96|-88.97|-10.17|17495497|8.60|
|FLUID_USDT|2.376000|-6.16|15.11|-6.37|8904101|8.42|
|BCH_USDT|274.180000|-1.76|-4.89|-1.97|10165865|3.65|
|HYPE_USDT|77.988000|-0.90|-16.97|-1.11|91192198|0.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002323|0.001943|0.002331|6.01|N|Y/N|Y/Y|Y|N|
|BCH_USDT|274.180000|272.300000|274.330000|0.10|N|Y/Y|Y/N|Y|N|
|FLUID_USDT|2.376000|2.364000|2.376000|0.18|N|Y/Y|N/N|Y|N|
|HYPE_USDT|77.988000|77.682000|77.988000|0.73|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T18:45:01+00:00, last15m_closed_end=2026-11-05T18:45+00:00, prior8high=0.003465, depth_time=2026-11-05T18:45:06+00:00, book20_bid_proxy_usdt=44482, book20_ask_proxy_usdt=55482, funding_indicative=-0.015055, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-9.96%, turnover=17495497. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BCH_USDT: quote_utc=2026-11-05T18:45:02+00:00, last15m_closed_end=2026-11-05T18:45+00:00, prior8high=283.300000, depth_time=2026-11-05T18:45:11+00:00, book20_bid_proxy_usdt=44741, book20_ask_proxy_usdt=88240, funding_indicative=0.000100, next_funding_utc=2026-11-06T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.76%, turnover=10165865. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FLUID_USDT: quote_utc=2026-11-05T18:45:01+00:00, last15m_closed_end=2026-11-05T18:45+00:00, prior8high=2.597000, depth_time=2026-11-05T18:45:08+00:00, book20_bid_proxy_usdt=148624, book20_ask_proxy_usdt=235451, funding_indicative=0.000159, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-6.16%, turnover=8904101. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T18:45:01+00:00, last15m_closed_end=2026-11-05T18:45+00:00, prior8high=80.237000, depth_time=2026-11-05T18:45:13+00:00, book20_bid_proxy_usdt=346197, book20_ask_proxy_usdt=68902, funding_indicative=0.000050, next_funding_utc=2026-11-05T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.90%, turnover=91192198. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
