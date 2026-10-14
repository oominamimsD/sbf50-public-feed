# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T07:30:21Z**
- feed_generated_utc: 2026-10-14T07:30:23+00:00
- source_sha256: `ac7a29d8891f229c8b0b0f1f46acd04fb7cc7e7fa1f8c45743b8b065114b000f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T07:30+00:00, close=83439.4, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T07:00+00:00, close=83400, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-14T04:00+00:00, close=83663.4, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|MAGIC_USDT|0.112600|-5.09|65.29|-5.14|5438444|0.89|
|STRK_USDT|0.083650|-3.77|60.27|-3.82|30925877|1.20|
|TIA_USDT|0.560000|-2.99|17.57|-3.04|42432403|1.78|
|UNI_USDT|7.374000|-2.61|-14.89|-2.66|19379676|1.36|
|W_USDT|0.016369|-2.58|12.79|-2.63|6873792|3.06|
|SILVER_USDT|58.650000|-1.24|-4.43|-1.29|252241435|1.71|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|MAGIC_USDT|0.112600|0.110660|0.112600|3.23|N|Y/Y|Y/N|N|N|
|SILVER_USDT|58.650000|58.510000|58.670000|3.40|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.083650|0.080270|0.083640|0.99|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.560000|0.547400|0.560000|0.71|N|Y/Y|N/N|N|N|
|UNI_USDT|7.374000|7.259000|7.374000|0.05|N|Y/Y|Y/N|N|N|
|W_USDT|0.016369|0.015869|0.016369|0.60|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- MAGIC_USDT: quote_utc=2026-10-14T07:30:02+00:00, last15m_closed_end=2026-10-14T07:30+00:00, prior8high=0.115390, depth_time=2026-10-14T07:30:08+00:00, book20_bid_proxy_usdt=186045, book20_ask_proxy_usdt=170780, funding_indicative=0.000005, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.09%, turnover=5438444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T07:30:02+00:00, last15m_closed_end=2026-10-14T07:30+00:00, prior8high=59.330000, depth_time=2026-10-14T07:30:20+00:00, book20_bid_proxy_usdt=48339113, book20_ask_proxy_usdt=46444838, funding_indicative=0.000076, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.24%, turnover=252241435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T07:30:02+00:00, last15m_closed_end=2026-10-14T07:30+00:00, prior8high=0.083620, depth_time=2026-10-14T07:30:11+00:00, book20_bid_proxy_usdt=204306, book20_ask_proxy_usdt=186955, funding_indicative=0.000050, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=30925877. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T07:30:02+00:00, last15m_closed_end=2026-10-14T07:30+00:00, prior8high=0.575200, depth_time=2026-10-14T07:30:11+00:00, book20_bid_proxy_usdt=116098, book20_ask_proxy_usdt=194948, funding_indicative=0.000024, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.99%, turnover=42432403. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T07:30:02+00:00, last15m_closed_end=2026-10-14T07:30+00:00, prior8high=7.436000, depth_time=2026-10-14T07:30:14+00:00, book20_bid_proxy_usdt=1649055, book20_ask_proxy_usdt=1429353, funding_indicative=0.000100, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.61%, turnover=19379676. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T07:30:02+00:00, last15m_closed_end=2026-10-14T07:30+00:00, prior8high=0.016455, depth_time=2026-10-14T07:30:17+00:00, book20_bid_proxy_usdt=36823, book20_ask_proxy_usdt=31205, funding_indicative=-0.000203, next_funding_utc=2026-10-14T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=6873792. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
