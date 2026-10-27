# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T20:30:14Z**
- feed_generated_utc: 2026-10-27T20:30:16+00:00
- source_sha256: `4a8e81ea253c21825a4ad7eab19df95fc48736393acf30bd8d5560c043146620`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T20:30+00:00, close=80663.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T20:00+00:00, close=80778.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.053628|-15.65|-56.31|-15.81|54673504|3.92|
|IRYS_USDT|0.024520|-1.56|88.32|-1.72|5731560|4.08|
|SYN_USDT|0.179500|-1.04|-2.23|-1.20|5937372|5.57|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|IRYS_USDT|0.024520|0.024560|0.024520|0.78|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.053628|0.051125|0.053582|1.00|N|Y/Y|Y/Y|N|N|
|SYN_USDT|0.179500|0.177900|0.179500|0.49|N|N/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- IRYS_USDT: quote_utc=2026-10-27T20:30:01+00:00, last15m_closed_end=2026-10-27T20:30+00:00, prior8high=0.024890, depth_time=2026-10-27T20:30:11+00:00, book20_bid_proxy_usdt=138177, book20_ask_proxy_usdt=107609, funding_indicative=-0.000401, next_funding_utc=2026-10-27T21:00:00+00:00, funding_cycle_h=1, 24h_change=-1.56%, turnover=5731560. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-27T20:30:01+00:00, last15m_closed_end=2026-10-27T20:30+00:00, prior8high=0.055947, depth_time=2026-10-27T20:30:08+00:00, book20_bid_proxy_usdt=4009, book20_ask_proxy_usdt=1658, funding_indicative=0.000048, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-15.65%, turnover=54673504. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SYN_USDT: quote_utc=2026-10-27T20:30:02+00:00, last15m_closed_end=2026-10-27T20:30+00:00, prior8high=0.181900, depth_time=2026-10-27T20:30:12+00:00, book20_bid_proxy_usdt=100411, book20_ask_proxy_usdt=104702, funding_indicative=0.000050, next_funding_utc=2026-10-28T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=5937372. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
