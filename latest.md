# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-13T22:30:13Z**
- feed_generated_utc: 2026-10-13T22:30:15+00:00
- source_sha256: `2455a1b594d841141f559a91d086f86c0342605985be97d26d8b89d9447d7705`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 20/20 successful
- tickers: 1212; contracts: 1204; crypto_prefilter: 3; crypto_deep: 3
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-13T22:30+00:00, close=83403.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-13T22:00+00:00, close=83487.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-13T20:00+00:00, close=83253, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|STRK_USDT|0.083570|-3.86|60.12|-3.87|40602415|1.20|
|CT_USDT|0.359870|-3.19|-3.15|-3.20|5538445|2.50|
|RLC_USDT|0.894200|-3.14|9.07|-3.15|5383940|1.12|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.359870|0.353500|0.359870|0.14|N|Y/Y|N/N|N|N|
|RLC_USDT|0.894200|0.878300|0.894200|0.86|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.083570|0.082920|0.083570|1.40|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-13T22:30:02+00:00, last15m_closed_end=2026-10-13T22:30+00:00, prior8high=0.367810, depth_time=2026-10-13T22:30:09+00:00, book20_bid_proxy_usdt=11757, book20_ask_proxy_usdt=12721, funding_indicative=0.000050, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.19%, turnover=5538445. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RLC_USDT: quote_utc=2026-10-13T22:30:02+00:00, last15m_closed_end=2026-10-13T22:30+00:00, prior8high=0.903000, depth_time=2026-10-13T22:30:11+00:00, book20_bid_proxy_usdt=93867, book20_ask_proxy_usdt=79213, funding_indicative=-0.000483, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.14%, turnover=5383940. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-13T22:30:01+00:00, last15m_closed_end=2026-10-13T22:30+00:00, prior8high=0.085880, depth_time=2026-10-13T22:30:06+00:00, book20_bid_proxy_usdt=173870, book20_ask_proxy_usdt=168136, funding_indicative=0.000007, next_funding_utc=2026-10-14T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.86%, turnover=40602415. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
