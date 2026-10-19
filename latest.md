# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-19T07:45:19Z**
- feed_generated_utc: 2026-10-19T07:45:20+00:00
- source_sha256: `e915808b32f5a3c1f37a080fd8bc0ee91789fff7219cc036dfacd002cfa5aba1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 30/30 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 5; crypto_deep: 5
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-19T07:45+00:00, close=82852.2, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-19T07:00+00:00, close=82812.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-19T04:00+00:00, close=82496.1, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ICNT_USDT|0.168200|-6.24|58.67|-8.35|7068285|5.95|
|BTW_USDT|2.221500|-3.63|32.05|-5.74|21952003|1.80|
|STRK_USDT|0.059670|-3.07|-49.97|-5.18|17868017|1.68|
|TIA_USDT|0.616300|-0.25|4.68|-2.36|57188763|3.25|
|Q_USDT|0.122224|0.20|331.55|-1.91|15424880|0.66|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BTW_USDT|2.221500|2.166400|2.222400|0.68|N|Y/Y|N/N|N|N|
|ICNT_USDT|0.168200|0.167000|0.168200|0.38|N|Y/Y|N/N|N|N|
|Q_USDT|0.122224|0.115540|0.121979|0.61|N|N/N|N/N|N|N|
|STRK_USDT|0.059670|0.059350|0.059670|2.23|N|Y/Y|Y/Y|N|N|
|TIA_USDT|0.616300|0.606800|0.616200|1.14|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- BTW_USDT: quote_utc=2026-10-19T07:45:01+00:00, last15m_closed_end=2026-10-19T07:45+00:00, prior8high=2.321000, depth_time=2026-10-19T07:45:10+00:00, book20_bid_proxy_usdt=12646, book20_ask_proxy_usdt=13993, funding_indicative=-0.000271, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.63%, turnover=21952003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICNT_USDT: quote_utc=2026-10-19T07:45:01+00:00, last15m_closed_end=2026-10-19T07:45+00:00, prior8high=0.189100, depth_time=2026-10-19T07:45:07+00:00, book20_bid_proxy_usdt=144652, book20_ask_proxy_usdt=107183, funding_indicative=-0.000045, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.24%, turnover=7068285. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-19T07:45:01+00:00, last15m_closed_end=2026-10-19T07:45+00:00, prior8high=0.216121, depth_time=2026-10-19T07:45:18+00:00, book20_bid_proxy_usdt=13923, book20_ask_proxy_usdt=15615, funding_indicative=-0.001203, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=0.20%, turnover=15424880. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-19T07:45:01+00:00, last15m_closed_end=2026-10-19T07:45+00:00, prior8high=0.060510, depth_time=2026-10-19T07:45:10+00:00, book20_bid_proxy_usdt=1271311, book20_ask_proxy_usdt=770649, funding_indicative=0.000050, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.07%, turnover=17868017. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-19T07:45:01+00:00, last15m_closed_end=2026-10-19T07:45+00:00, prior8high=0.616500, depth_time=2026-10-19T07:45:14+00:00, book20_bid_proxy_usdt=259044, book20_ask_proxy_usdt=259058, funding_indicative=-0.000042, next_funding_utc=2026-10-19T08:00:00+00:00, funding_cycle_h=4, 24h_change=-0.25%, turnover=57188763. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
