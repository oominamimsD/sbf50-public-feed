# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T15:00:32Z**
- feed_generated_utc: 2026-10-27T15:00:36+00:00
- source_sha256: `59483464165c3b5497f414a88cd6d2e71676f4d224d310d3771b2fe2d6089d0f`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1192; contracts: 1184; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T15:00+00:00, close=80328.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T15:00+00:00, close=80328.7, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.025240|-8.48|105.53|-8.42|6290718|7.91|
|QNT_USDT|198.680000|-5.51|1.52|-5.45|88995674|1.51|
|AAVE_USDT|131.390000|-4.70|-10.75|-4.64|26227884|0.76|
|FILECOIN_USDT|0.892200|-3.70|-11.83|-3.64|5121819|3.36|
|APT_USDT|0.683000|-3.39|-10.47|-3.33|5098149|1.46|
|DOT_USDT|0.988800|-3.30|-13.77|-3.24|11026443|2.02|
|WLD_USDT|0.431600|-3.01|-14.75|-2.95|69371283|2.32|
|HBAR_USDT|0.075910|-1.87|-7.27|-1.81|9531715|1.32|
|ICP_USDT|2.582000|-1.82|-9.49|-1.76|5040777|3.87|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|131.390000|130.180000|131.390000|0.70|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.683000|0.672700|0.683000|0.93|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.988800|0.977000|0.988700|1.37|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.892200|0.880500|0.892200|0.05|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.075910|0.075590|0.075900|0.73|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.582000|2.552000|2.581000|1.12|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.025240|0.024590|0.025310|1.00|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|198.680000|196.560000|198.500000|0.89|N|Y/Y|N/N|Y|N|
|WLD_USDT|0.431600|0.424600|0.431200|0.84|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=133.100000, depth_time=2026-10-27T15:00:16+00:00, book20_bid_proxy_usdt=309754, book20_ask_proxy_usdt=462958, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.70%, turnover=26227884. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=0.690800, depth_time=2026-10-27T15:00:22+00:00, book20_bid_proxy_usdt=148392, book20_ask_proxy_usdt=158702, funding_indicative=-0.000023, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.39%, turnover=5098149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=0.996900, depth_time=2026-10-27T15:00:24+00:00, book20_bid_proxy_usdt=343765, book20_ask_proxy_usdt=655793, funding_indicative=-0.000142, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.30%, turnover=11026443. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=0.902000, depth_time=2026-10-27T15:00:19+00:00, book20_bid_proxy_usdt=1182807, book20_ask_proxy_usdt=1391229, funding_indicative=0.000024, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.70%, turnover=5121819. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=0.076600, depth_time=2026-10-27T15:00:27+00:00, book20_bid_proxy_usdt=795096, book20_ask_proxy_usdt=1292574, funding_indicative=0.000078, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.87%, turnover=9531715. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=2.608000, depth_time=2026-10-27T15:00:31+00:00, book20_bid_proxy_usdt=1009652, book20_ask_proxy_usdt=1142521, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=5040777. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=0.025580, depth_time=2026-10-27T15:00:11+00:00, book20_bid_proxy_usdt=71235, book20_ask_proxy_usdt=103997, funding_indicative=-0.000554, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=1, 24h_change=-8.48%, turnover=6290718. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=202.980000, depth_time=2026-10-27T15:00:14+00:00, book20_bid_proxy_usdt=49098, book20_ask_proxy_usdt=59752, funding_indicative=-0.000203, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.51%, turnover=88995674. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T15:00:03+00:00, last15m_closed_end=2026-10-27T15:00+00:00, prior8high=0.438400, depth_time=2026-10-27T15:00:26+00:00, book20_bid_proxy_usdt=3059979, book20_ask_proxy_usdt=4144824, funding_indicative=-0.000043, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=69371283. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
