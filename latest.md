# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-03T20:45:22Z**
- feed_generated_utc: 2026-11-03T20:45:24+00:00
- source_sha256: `c4c2f433a0dbe25b91ddc1ccee514363ac8ac1198f7593008419db327bdd15a0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 35/35 successful
- tickers: 1193; contracts: 1185; crypto_prefilter: 6; crypto_deep: 6
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-03T20:45+00:00, close=77787.5, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-03T20:00+00:00, close=77586.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.004007|-3.58|-81.03|-3.73|13632269|4.99|
|TRUMPOFFICIAL_USDT|1.575000|-2.05|-6.69|-2.20|6000092|6.35|
|QNT_USDT|191.890000|-1.80|-3.03|-1.95|58002915|0.52|
|OP_USDT|0.108740|-1.53|-2.31|-1.68|8827575|0.92|
|XLM_USDT|0.162460|-1.41|-3.98|-1.56|33800574|1.85|
|TIA_USDT|0.430400|-1.23|-19.71|-1.38|11826129|2.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.004007|0.003757|0.004007|1.63|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.108740|0.108610|0.108740|0.37|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|191.890000|190.330000|191.890000|0.77|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.430400|0.427600|0.430400|0.40|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.575000|1.571000|1.575000|1.05|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.162460|0.162310|0.162460|1.17|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-03T20:45:00+00:00, last15m_closed_end=2026-11-03T20:45+00:00, prior8high=0.004019, depth_time=2026-11-03T20:45:08+00:00, book20_bid_proxy_usdt=40769, book20_ask_proxy_usdt=25982, funding_indicative=-0.000512, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.58%, turnover=13632269. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-03T20:45:00+00:00, last15m_closed_end=2026-11-03T20:45+00:00, prior8high=0.110950, depth_time=2026-11-03T20:45:16+00:00, book20_bid_proxy_usdt=141996, book20_ask_proxy_usdt=141974, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.53%, turnover=8827575. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-03T20:45:00+00:00, last15m_closed_end=2026-11-03T20:45+00:00, prior8high=193.660000, depth_time=2026-11-03T20:45:14+00:00, book20_bid_proxy_usdt=70420, book20_ask_proxy_usdt=102258, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=58002915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-03T20:45:00+00:00, last15m_closed_end=2026-11-03T20:45+00:00, prior8high=0.433900, depth_time=2026-11-03T20:45:21+00:00, book20_bid_proxy_usdt=402504, book20_ask_proxy_usdt=447634, funding_indicative=-0.000025, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-1.23%, turnover=11826129. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-03T20:45:00+00:00, last15m_closed_end=2026-11-03T20:45+00:00, prior8high=1.588000, depth_time=2026-11-03T20:45:10+00:00, book20_bid_proxy_usdt=2317857, book20_ask_proxy_usdt=2212910, funding_indicative=0.000028, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=6000092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-03T20:45:00+00:00, last15m_closed_end=2026-11-03T20:45+00:00, prior8high=0.164650, depth_time=2026-11-03T20:45:19+00:00, book20_bid_proxy_usdt=202437, book20_ask_proxy_usdt=215176, funding_indicative=0.000100, next_funding_utc=2026-11-04T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=33800574. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
