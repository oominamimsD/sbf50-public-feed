# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-16T12:30:15Z**
- feed_generated_utc: 2026-10-16T12:30:17+00:00
- source_sha256: `89499f7cd13d8422d19d9b95b8f81c60c388a775c4e08587d6c5dff451f336d8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-16T12:30+00:00, close=82295.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-16T12:00+00:00, close=82599.5, belowEMA20=False, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZEREBRO_USDT|0.040634|-20.78|47.99|-20.69|5034465|1.48|
|STRK_USDT|0.076950|-20.14|27.90|-20.05|40331246|1.30|
|BTW_USDT|1.728500|-9.37|24.50|-9.28|22110743|4.62|
|NIL_USDT|0.082380|-5.17|-4.86|-5.08|5413768|3.64|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|1.728500|1.611400|1.728400|0.94|N|Y/Y|Y/Y|N|N|
|NIL_USDT|0.082380|0.081930|0.082350|1.19|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.076950|0.075950|0.076900|1.50|N|Y/Y|Y/Y|N|N|
|ZEREBRO_USDT|0.040634|0.037647|0.040704|1.15|N|Y/N|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-16T12:30:01+00:00, last15m_closed_end=2026-10-16T12:30+00:00, prior8high=1.936600, depth_time=2026-10-16T12:30:12+00:00, book20_bid_proxy_usdt=10678, book20_ask_proxy_usdt=9312, funding_indicative=-0.000690, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.37%, turnover=22110743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NIL_USDT: quote_utc=2026-10-16T12:30:01+00:00, last15m_closed_end=2026-10-16T12:30+00:00, prior8high=0.084570, depth_time=2026-10-16T12:30:13+00:00, book20_bid_proxy_usdt=32419, book20_ask_proxy_usdt=41764, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.17%, turnover=5413768. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-16T12:30:01+00:00, last15m_closed_end=2026-10-16T12:30+00:00, prior8high=0.080420, depth_time=2026-10-16T12:30:09+00:00, book20_bid_proxy_usdt=179984, book20_ask_proxy_usdt=207530, funding_indicative=-0.000013, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.14%, turnover=40331246. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEREBRO_USDT: quote_utc=2026-10-16T12:30:01+00:00, last15m_closed_end=2026-10-16T12:30+00:00, prior8high=0.053759, depth_time=2026-10-16T12:30:07+00:00, book20_bid_proxy_usdt=7274, book20_ask_proxy_usdt=8539, funding_indicative=0.000050, next_funding_utc=2026-10-16T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.78%, turnover=5034465. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
