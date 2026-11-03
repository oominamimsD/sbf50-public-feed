# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T21:15:17Z**
- feed_generated_utc: 2026-11-03T21:15:18+00:00
- source_sha256: `a7afb132f6e8d3e5825438a2be611b950b5f6b7e30280451daf496dd50c0c4f9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 25/25 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 4; crypto_deep: 4
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T21:15+00:00, close=77859.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T21:00+00:00, close=77833.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.003949|-4.98|-81.30|-5.18|13630723|2.53|
|QNT_USDT|192.370000|-1.56|-2.78|-1.76|57124044|0.52|
|OP_USDT|0.109040|-1.25|-2.04|-1.45|8655981|1.84|
|TIA_USDT|0.432300|-0.80|-19.36|-1.00|11691414|2.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.003949|0.003851|0.003949|0.78|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.109040|0.108610|0.109070|1.93|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.370000|190.330000|192.500000|0.50|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.432300|0.427600|0.432200|1.53|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T21:15:01+00:00, last15m_closed_end=2026-11-03T21:15+00:00, prior8high=0.004125, depth_time=2026-11-03T21:15:09+00:00, book20_bid_proxy_usdt=49118, book20_ask_proxy_usdt=23603, funding_indicative=-0.000512, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.98%, turnover=13630723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T21:15:01+00:00, last15m_closed_end=2026-11-03T21:15+00:00, prior8high=0.110600, depth_time=2026-11-03T21:15:13+00:00, book20_bid_proxy_usdt=135039, book20_ask_proxy_usdt=150049, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.25%, turnover=8655981. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T21:15:01+00:00, last15m_closed_end=2026-11-03T21:15+00:00, prior8high=192.620000, depth_time=2026-11-03T21:15:11+00:00, book20_bid_proxy_usdt=57742, book20_ask_proxy_usdt=60664, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.56%, turnover=57124044. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T21:15:01+00:00, last15m_closed_end=2026-11-03T21:15+00:00, prior8high=0.432900, depth_time=2026-11-03T21:15:16+00:00, book20_bid_proxy_usdt=302405, book20_ask_proxy_usdt=298352, funding_indicative=-0.000001, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-0.80%, turnover=11691414. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
