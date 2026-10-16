# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T11:30:17Z**
- feed_generated_utc: 2026-10-16T11:30:19+00:00
- source_sha256: `9961ac5547dfda5ec98241453f45665ea6421742a56ae43d9ab60044d5c9abc3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T11:30+00:00, close=82784, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T11:00+00:00, close=82175.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T08:00+00:00, close=82258.6, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.039111|-23.75|42.44|-24.28|5356240|6.16|
|STRK_USDT|0.079440|-17.55|32.04|-18.08|40582459|2.52|
|BTW_USDT|1.691600|-11.31|21.84|-11.84|21931667|3.54|
|AKE_USDT|0.029769|-5.80|2.57|-6.33|19328486|0.67|
|NIL_USDT|0.083310|-4.10|-3.78|-4.63|5707651|4.80|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.029769|0.029790|0.029769|1.01|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.691600|1.632500|1.691600|2.47|N|Y/Y|Y/Y|Y|N|
|NIL_USDT|0.083310|0.081680|0.083350|0.52|N|Y/Y|Y/N|Y|N|
|STRK_USDT|0.079440|0.075950|0.079450|2.03|N|Y/Y|Y/Y|Y|N|
|ZEREBRO_USDT|0.039111|0.041255|0.039050|4.89|Y|N/N|N/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-10-16T11:29:59+00:00, last15m_closed_end=2026-10-16T11:30+00:00, prior8high=0.030894, depth_time=2026-10-16T11:30:14+00:00, book20_bid_proxy_usdt=11947, book20_ask_proxy_usdt=14103, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-5.80%, turnover=19328486. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-16T11:29:59+00:00, last15m_closed_end=2026-10-16T11:30+00:00, prior8high=2.038000, depth_time=2026-10-16T11:30:12+00:00, book20_bid_proxy_usdt=7382, book20_ask_proxy_usdt=7393, funding_indicative=-0.000800, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.31%, turnover=21931667. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T11:29:59+00:00, last15m_closed_end=2026-10-16T11:30+00:00, prior8high=0.084570, depth_time=2026-10-16T11:30:16+00:00, book20_bid_proxy_usdt=22469, book20_ask_proxy_usdt=19445, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=5707651. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T11:29:59+00:00, last15m_closed_end=2026-10-16T11:30+00:00, prior8high=0.079390, depth_time=2026-10-16T11:30:09+00:00, book20_bid_proxy_usdt=207703, book20_ask_proxy_usdt=230374, funding_indicative=0.000004, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-17.55%, turnover=40582459. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T11:30:02+00:00, last15m_closed_end=2026-10-16T11:30+00:00, prior8high=0.055777, depth_time=2026-10-16T11:30:07+00:00, book20_bid_proxy_usdt=16207, book20_ask_proxy_usdt=104911, funding_indicative=0.000050, next_funding_utc=2026-10-16T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.75%, turnover=5356240. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
