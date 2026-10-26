# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T12:30:24Z**
- feed_generated_utc: 2026-10-26T12:30:27+00:00
- source_sha256: `0d37680916515d1ade2cb7805ba8a7b0868cc5791508d37403b867e9cabfadfc`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T12:30+00:00, close=80482.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T12:00+00:00, close=80382.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.076120|-29.17|14.46|-29.03|7188404|6.57|
|IRYS_USDT|0.028570|-25.67|134.18|-25.53|12203156|3.50|
|APR_USDT|0.033710|-18.39|23.75|-18.25|7203436|5.94|
|BTW_USDT|1.428300|-13.90|-38.04|-13.76|11906167|5.60|
|WLD_USDT|0.443700|-2.82|-6.84|-2.68|60818456|2.25|
|XMR_USDT|592.310000|-2.46|1.68|-2.32|5749629|0.17|
|STRK_USDT|0.044800|-2.05|-27.22|-1.91|9347025|2.23|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.033710|0.033120|0.033710|0.74|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.428300|1.410700|1.428600|2.94|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.076120|0.070960|0.076120|0.82|N|Y/Y|Y/N|Y|N|
|IRYS_USDT|0.028570|0.027970|0.028580|1.02|N|Y/Y|Y/Y|Y|N|
|STRK_USDT|0.044800|0.044360|0.044790|1.20|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.443700|0.435800|0.443700|0.63|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|592.310000|588.790000|592.310000|0.90|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T12:30:01+00:00, last15m_closed_end=2026-10-26T12:30+00:00, prior8high=0.035000, depth_time=2026-10-26T12:30:12+00:00, book20_bid_proxy_usdt=70563, book20_ask_proxy_usdt=45702, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-18.39%, turnover=7203436. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T12:30:01+00:00, last15m_closed_end=2026-10-26T12:30+00:00, prior8high=1.523500, depth_time=2026-10-26T12:30:16+00:00, book20_bid_proxy_usdt=36869, book20_ask_proxy_usdt=15973, funding_indicative=-0.014034, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-13.90%, turnover=11906167. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T12:30:01+00:00, last15m_closed_end=2026-10-26T12:30+00:00, prior8high=0.082200, depth_time=2026-10-26T12:30:08+00:00, book20_bid_proxy_usdt=59302, book20_ask_proxy_usdt=57871, funding_indicative=0.000050, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-29.17%, turnover=7188404. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T12:30:01+00:00, last15m_closed_end=2026-10-26T12:30+00:00, prior8high=0.029090, depth_time=2026-10-26T12:30:09+00:00, book20_bid_proxy_usdt=89670, book20_ask_proxy_usdt=97411, funding_indicative=-0.000509, next_funding_utc=2026-10-26T13:00:00+00:00, funding_cycle_h=1, 24h_change=-25.67%, turnover=12203156. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-26T12:30:01+00:00, last15m_closed_end=2026-10-26T12:30+00:00, prior8high=0.045410, depth_time=2026-10-26T12:30:22+00:00, book20_bid_proxy_usdt=882065, book20_ask_proxy_usdt=740333, funding_indicative=-0.000029, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.05%, turnover=9347025. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T12:30:01+00:00, last15m_closed_end=2026-10-26T12:30+00:00, prior8high=0.441800, depth_time=2026-10-26T12:30:18+00:00, book20_bid_proxy_usdt=2353626, book20_ask_proxy_usdt=2909867, funding_indicative=-0.000155, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.82%, turnover=60818456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T12:30:01+00:00, last15m_closed_end=2026-10-26T12:30+00:00, prior8high=592.670000, depth_time=2026-10-26T12:30:20+00:00, book20_bid_proxy_usdt=7941, book20_ask_proxy_usdt=13781, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.46%, turnover=5749629. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
