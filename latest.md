# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-20T04:15:17Z**
- feed_generated_utc: 2026-10-20T04:15:20+00:00
- source_sha256: `804a9695ccebbdd20d36efd44e797f8f7213317b4c89a425764c788e15886c04`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-20T04:15+00:00, close=82093.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-20T04:00+00:00, close=82099.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.120072|-4.69|289.95|-4.90|13475117|0.58|
|SAND_USDT|0.057680|-2.46|-7.10|-2.67|8870943|1.73|
|CT_USDT|0.324030|-1.84|-5.29|-2.05|5311070|0.93|
|ZRO_USDT|1.868600|-1.75|-17.35|-1.96|7668777|0.54|
|NEAR_USDT|4.840000|-1.30|-12.77|-1.51|166309299|2.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|CT_USDT|0.324030|0.326360|0.324030|0.71|N|Y/N|Y/Y|N|N|
|NEAR_USDT|4.840000|4.788000|4.840000|1.40|N|Y/Y|Y/Y|N|N|
|Q_USDT|0.120072|0.120821|0.120072|1.63|Y|Y/Y|N/N|N|N|
|SAND_USDT|0.057680|0.057590|0.057670|0.72|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.868600|1.847300|1.868600|0.76|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- CT_USDT: quote_utc=2026-10-20T04:15:01+00:00, last15m_closed_end=2026-10-20T04:15+00:00, prior8high=0.342220, depth_time=2026-10-20T04:15:11+00:00, book20_bid_proxy_usdt=7152, book20_ask_proxy_usdt=11367, funding_indicative=-0.002840, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.84%, turnover=5311070. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-20T04:15:01+00:00, last15m_closed_end=2026-10-20T04:15+00:00, prior8high=4.884000, depth_time=2026-10-20T04:15:17+00:00, book20_bid_proxy_usdt=3163948, book20_ask_proxy_usdt=3703065, funding_indicative=0.000039, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.30%, turnover=166309299. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-20T04:15:01+00:00, last15m_closed_end=2026-10-20T04:15+00:00, prior8high=0.128625, depth_time=2026-10-20T04:15:07+00:00, book20_bid_proxy_usdt=14922, book20_ask_proxy_usdt=25829, funding_indicative=-0.000181, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.69%, turnover=13475117. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SAND_USDT: quote_utc=2026-10-20T04:15:01+00:00, last15m_closed_end=2026-10-20T04:15+00:00, prior8high=0.058600, depth_time=2026-10-20T04:15:09+00:00, book20_bid_proxy_usdt=441218, book20_ask_proxy_usdt=768777, funding_indicative=-0.002012, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=8870943. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-20T04:15:01+00:00, last15m_closed_end=2026-10-20T04:15+00:00, prior8high=1.883500, depth_time=2026-10-20T04:15:14+00:00, book20_bid_proxy_usdt=35922, book20_ask_proxy_usdt=35967, funding_indicative=0.000050, next_funding_utc=2026-10-20T08:00:00+00:00, funding_cycle_h=4, 24h_change=-1.75%, turnover=7668777. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
