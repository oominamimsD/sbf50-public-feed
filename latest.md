# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-26T10:15:24Z**
- feed_generated_utc: 2026-10-26T10:15:28+00:00
- source_sha256: `be88af590f960c1bf0b0402a791e9f94932da7ba2b43e58aa5d2ac64c10850c3`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 45/45 successful
- tickers: 1182; contracts: 1174; crypto_prefilter: 8; crypto_deep: 8
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-26T10:15+00:00, close=80416.1, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-26T10:00+00:00, close=80507.3, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-26T08:00+00:00, close=80002, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CAP_USDT|0.080700|-24.91|21.35|-24.68|7271415|2.47|
|IRYS_USDT|0.029020|-24.50|137.86|-24.27|12613889|6.90|
|APR_USDT|0.034880|-15.56|28.04|-15.33|8961257|2.86|
|BTW_USDT|1.509800|-8.98|-34.51|-8.75|10997842|1.99|
|WLD_USDT|0.438600|-3.94|-7.91|-3.71|62825834|2.28|
|LIT_USDT|3.070200|-3.40|4.77|-3.17|5545088|0.33|
|XMR_USDT|590.350000|-2.78|1.34|-2.55|5888054|0.17|
|DOT_USDT|1.019100|-1.93|-4.70|-1.70|9921519|0.98|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APR_USDT|0.034880|0.033760|0.034820|1.64|N|Y/Y|N/N|Y|N|
|BTW_USDT|1.509800|1.440500|1.509800|1.17|N|Y/Y|Y/Y|Y|N|
|CAP_USDT|0.080700|0.074320|0.080700|0.64|N|Y/Y|N/N|Y|N|
|DOT_USDT|1.019100|1.002700|1.019100|1.29|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.029020|0.028610|0.028990|0.70|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.070200|3.052200|3.072000|0.49|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.438600|0.434300|0.438500|1.56|N|Y/Y|Y/Y|Y|N|
|XMR_USDT|590.350000|583.530000|590.550000|1.65|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APR_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=0.038620, depth_time=2026-10-26T10:15:12+00:00, book20_bid_proxy_usdt=68977, book20_ask_proxy_usdt=58654, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-15.56%, turnover=8961257. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=1.596200, depth_time=2026-10-26T10:15:14+00:00, book20_bid_proxy_usdt=12687, book20_ask_proxy_usdt=13764, funding_indicative=-0.010879, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-8.98%, turnover=10997842. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CAP_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=0.090900, depth_time=2026-10-26T10:15:07+00:00, book20_bid_proxy_usdt=54330, book20_ask_proxy_usdt=52073, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-24.91%, turnover=7271415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=1.025400, depth_time=2026-10-26T10:15:24+00:00, book20_bid_proxy_usdt=446233, book20_ask_proxy_usdt=405673, funding_indicative=-0.000059, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.93%, turnover=9921519. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=0.030450, depth_time=2026-10-26T10:15:10+00:00, book20_bid_proxy_usdt=53746, book20_ask_proxy_usdt=59016, funding_indicative=-0.000401, next_funding_utc=2026-10-26T11:00:00+00:00, funding_cycle_h=1, 24h_change=-24.50%, turnover=12613889. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=3.121700, depth_time=2026-10-26T10:15:19+00:00, book20_bid_proxy_usdt=31536, book20_ask_proxy_usdt=19802, funding_indicative=0.000050, next_funding_utc=2026-10-26T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.40%, turnover=5545088. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=0.444800, depth_time=2026-10-26T10:15:17+00:00, book20_bid_proxy_usdt=2828128, book20_ask_proxy_usdt=3022378, funding_indicative=-0.000132, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.94%, turnover=62825834. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XMR_USDT: quote_utc=2026-10-26T10:15:02+00:00, last15m_closed_end=2026-10-26T10:15+00:00, prior8high=592.000000, depth_time=2026-10-26T10:15:21+00:00, book20_bid_proxy_usdt=20592, book20_ask_proxy_usdt=10017, funding_indicative=0.000100, next_funding_utc=2026-10-26T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.78%, turnover=5888054. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
