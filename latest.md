# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T13:00:33Z**
- feed_generated_utc: 2026-10-27T13:00:37+00:00
- source_sha256: `3d49ce2663ff4b0bb89997879c646c30273402b729e7db66331f3c6217fa3015`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T13:00+00:00, close=80337, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T13:00+00:00, close=80337, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BULLA_USDT|0.070460|-51.28|-2.16|-51.21|10493677|1.42|
|IRYS_USDT|0.024900|-10.68|102.76|-10.61|6924452|4.01|
|QNT_USDT|201.900000|-5.32|3.16|-5.25|103057779|1.49|
|AAVE_USDT|132.400000|-3.97|-10.06|-3.90|28079024|0.76|
|DOT_USDT|0.993800|-3.62|-13.34|-3.55|10935963|1.01|
|FILECOIN_USDT|0.896400|-3.24|-11.42|-3.17|6482199|1.11|
|WLD_USDT|0.435400|-2.85|-14.00|-2.78|66535216|2.30|
|ICP_USDT|2.596000|-2.11|-9.00|-2.04|5149805|3.85|
|TIA_USDT|0.525900|-1.82|-13.57|-1.75|16997912|1.90|
|HBAR_USDT|0.076440|-1.59|-6.63|-1.52|10257929|1.31|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.400000|130.450000|132.400000|0.88|N|Y/Y|Y/Y|Y|N|
|BULLA_USDT|0.070460|0.060490|0.070460|2.18|N|Y/Y|Y/N|Y|N|
|DOT_USDT|0.993800|0.982200|0.993800|1.48|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.896400|0.887200|0.896400|1.03|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076440|0.075590|0.076440|0.71|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.596000|2.565000|2.596000|2.52|N|N/Y|Y/Y|Y|N|
|IRYS_USDT|0.024900|0.024650|0.024900|0.40|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|201.900000|200.570000|201.900000|1.13|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.525900|0.522500|0.526100|1.30|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.435400|0.428900|0.435400|0.97|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T13:00:00+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=132.910000, depth_time=2026-10-27T13:00:15+00:00, book20_bid_proxy_usdt=415305, book20_ask_proxy_usdt=377074, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.97%, turnover=28079024. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BULLA_USDT: quote_utc=2026-10-27T13:00:00+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=0.082380, depth_time=2026-10-27T13:00:08+00:00, book20_bid_proxy_usdt=45006, book20_ask_proxy_usdt=14718, funding_indicative=-0.008652, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-51.28%, turnover=10493677. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T13:00:00+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=0.994000, depth_time=2026-10-27T13:00:18+00:00, book20_bid_proxy_usdt=298621, book20_ask_proxy_usdt=555160, funding_indicative=-0.000111, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.62%, turnover=10935963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T13:00:01+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=0.900900, depth_time=2026-10-27T13:00:21+00:00, book20_bid_proxy_usdt=897378, book20_ask_proxy_usdt=1286582, funding_indicative=0.000074, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.24%, turnover=6482199. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T13:00:01+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=0.076470, depth_time=2026-10-27T13:00:32+00:00, book20_bid_proxy_usdt=631309, book20_ask_proxy_usdt=1363872, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.59%, turnover=10257929. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T13:00:01+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=2.599000, depth_time=2026-10-27T13:00:27+00:00, book20_bid_proxy_usdt=1116464, book20_ask_proxy_usdt=1127018, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.11%, turnover=5149805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T13:00:00+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=0.025210, depth_time=2026-10-27T13:00:11+00:00, book20_bid_proxy_usdt=135455, book20_ask_proxy_usdt=128590, funding_indicative=-0.000314, next_funding_utc=2026-10-27T14:00:00+00:00, funding_cycle_h=1, 24h_change=-10.68%, turnover=6924452. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T13:00:00+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=206.180000, depth_time=2026-10-27T13:00:13+00:00, book20_bid_proxy_usdt=45967, book20_ask_proxy_usdt=59163, funding_indicative=-0.000210, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.32%, turnover=103057779. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T13:00:00+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=0.529700, depth_time=2026-10-27T13:00:29+00:00, book20_bid_proxy_usdt=169743, book20_ask_proxy_usdt=366241, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.82%, turnover=16997912. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T13:00:00+00:00, last15m_closed_end=2026-10-27T13:00+00:00, prior8high=0.437100, depth_time=2026-10-27T13:00:23+00:00, book20_bid_proxy_usdt=3359161, book20_ask_proxy_usdt=3080769, funding_indicative=-0.000042, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=66535216. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
