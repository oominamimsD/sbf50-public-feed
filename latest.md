# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-25T16:00:15Z**
- feed_generated_utc: 2026-10-25T16:00:18+00:00
- source_sha256: `0d129a19294838ac16245ea681c19e06ff792b871408843b5fc8803fc2f24199`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1179; contracts: 1171; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-25T16:00+00:00, close=80602.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ORDER_USDT|0.047050|-30.19|52.01|-31.24|5057515|2.13|
|IRYS_USDT|0.038440|-16.52|201.25|-17.57|24748123|5.20|
|BTW_USDT|1.659400|-4.70|-26.87|-5.75|12180699|4.82|
|SUI_USDT|0.916800|-0.88|-6.62|-1.93|65719310|1.09|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.659400|1.650000|1.658900|1.90|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.038440|0.034410|0.038440|1.04|N|Y/Y|Y/Y|Y|N|
|ORDER_USDT|0.047050|0.045840|0.047050|0.59|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.916800|0.907500|0.916800|0.94|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-25T15:59:59+00:00, last15m_closed_end=2026-10-25T16:00+00:00, prior8high=1.701000, depth_time=2026-10-25T16:00:12+00:00, book20_bid_proxy_usdt=10081, book20_ask_proxy_usdt=18033, funding_indicative=-0.008757, next_funding_utc=2026-10-25T20:00:00+00:00, funding_cycle_h=4, 24h_change=-4.70%, turnover=12180699. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-25T15:59:59+00:00, last15m_closed_end=2026-10-25T16:00+00:00, prior8high=0.040280, depth_time=2026-10-25T16:00:10+00:00, book20_bid_proxy_usdt=42215, book20_ask_proxy_usdt=27692, funding_indicative=-0.000162, next_funding_utc=2026-10-25T17:00:00+00:00, funding_cycle_h=1, 24h_change=-16.52%, turnover=24748123. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ORDER_USDT: quote_utc=2026-10-25T15:59:59+00:00, last15m_closed_end=2026-10-25T16:00+00:00, prior8high=0.048570, depth_time=2026-10-25T16:00:07+00:00, book20_bid_proxy_usdt=83828, book20_ask_proxy_usdt=64417, funding_indicative=-0.000984, next_funding_utc=2026-10-25T17:00:00+00:00, funding_cycle_h=1, 24h_change=-30.19%, turnover=5057515. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-10-25T15:59:59+00:00, last15m_closed_end=2026-10-25T16:00+00:00, prior8high=0.919900, depth_time=2026-10-25T16:00:14+00:00, book20_bid_proxy_usdt=1245498, book20_ask_proxy_usdt=1335139, funding_indicative=0.000007, next_funding_utc=2026-10-26T00:00:00+00:00, funding_cycle_h=8, 24h_change=-0.88%, turnover=65719310. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
