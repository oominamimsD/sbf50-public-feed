# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-31T18:00:16Z**
- feed_generated_utc: 2026-10-31T18:00:18+00:00
- source_sha256: `163e0b002c9b2f9510e036132d0146c25e0a4823401177701cde29c76a17bcc3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-31T18:00+00:00, close=77664.4, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-31T18:00+00:00, close=77664.4, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-31T16:00+00:00, close=77560.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.018188|-8.80|130.22|-9.16|12080484|3.85|
|TRX_USDT|0.307170|-2.57|-6.61|-2.93|6883186|0.33|
|BTW_USDT|1.117800|-2.06|-35.80|-2.42|7214686|0.89|
|Q_USDT|0.032780|-0.87|-58.47|-1.23|10730626|3.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.117800|1.083700|1.117800|0.91|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.018188|0.016785|0.018188|1.30|N|Y/Y|N/N|Y|N|
|Q_USDT|0.032780|0.030480|0.032780|1.43|N|Y/Y|Y/Y|Y|N|
|TRX_USDT|0.307170|0.307650|0.307170|0.74|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-31T18:00:00+00:00, last15m_closed_end=2026-10-31T18:00+00:00, prior8high=1.127900, depth_time=2026-10-31T18:00:13+00:00, book20_bid_proxy_usdt=10530, book20_ask_proxy_usdt=11783, funding_indicative=-0.000303, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.06%, turnover=7214686. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-10-31T18:00:00+00:00, last15m_closed_end=2026-10-31T18:00+00:00, prior8high=0.018790, depth_time=2026-10-31T18:00:08+00:00, book20_bid_proxy_usdt=7072, book20_ask_proxy_usdt=4990, funding_indicative=0.000176, next_funding_utc=2026-10-31T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.80%, turnover=12080484. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-31T18:00:00+00:00, last15m_closed_end=2026-10-31T18:00+00:00, prior8high=0.033260, depth_time=2026-10-31T18:00:16+00:00, book20_bid_proxy_usdt=63974, book20_ask_proxy_usdt=50888, funding_indicative=-0.000617, next_funding_utc=2026-10-31T19:00:00+00:00, funding_cycle_h=1, 24h_change=-0.87%, turnover=10730626. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRX_USDT: quote_utc=2026-10-31T18:00:00+00:00, last15m_closed_end=2026-10-31T18:00+00:00, prior8high=0.313720, depth_time=2026-10-31T18:00:11+00:00, book20_bid_proxy_usdt=59578, book20_ask_proxy_usdt=66337, funding_indicative=-0.000552, next_funding_utc=2026-11-01T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.57%, turnover=6883186. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
