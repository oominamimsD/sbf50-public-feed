# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-14T11:00:34Z**
- feed_generated_utc: 2026-10-14T11:00:36+00:00
- source_sha256: `a9285478f6ac484e77fbc848c2aec3f05d43b95aaf3e81ad8199c32f83d7e8e8`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-14T11:00+00:00, close=83430.4, belowEMA20=False, EMA20down3=True
- BTC Min60: closed_end=2026-10-14T11:00+00:00, close=83430.4, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-10-14T08:00+00:00, close=83540.2, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|S_USDT|0.056520|-19.94|29.33|-19.98|24768784|3.54|
|STRK_USDT|0.079040|-7.46|51.44|-7.50|27611116|1.27|
|TIA_USDT|0.543800|-7.04|14.17|-7.08|35162604|1.84|
|W_USDT|0.016120|-4.06|11.08|-4.10|6289003|1.24|
|DOT_USDT|1.139200|-3.82|-5.17|-3.86|18943217|0.88|
|UNI_USDT|7.359000|-2.21|-15.07|-2.25|18158136|1.36|
|ICP_USDT|3.080000|-1.94|-9.46|-1.98|9240785|3.25|
|RENDER_USDT|1.985000|-1.68|-6.80|-1.72|8782742|5.04|
|FILECOIN_USDT|1.133600|-1.35|-1.46|-1.39|25053725|1.76|
|XLM_USDT|0.189400|-1.35|-11.36|-1.39|9408881|0.53|
|SILVER_USDT|58.590000|-1.34|-4.52|-1.38|257373277|1.71|
|HBAR_USDT|0.086330|-1.12|-13.73|-1.16|13350225|1.16|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|DOT_USDT|1.139200|1.129300|1.139200|0.44|N|Y/Y|Y/Y|N|N|
|FILECOIN_USDT|1.133600|1.117200|1.133600|0.82|N|Y/Y|N/N|N|N|
|HBAR_USDT|0.086330|0.085820|0.086330|0.10|N|Y/Y|Y/Y|N|N|
|ICP_USDT|3.080000|3.053000|3.080000|0.42|N|Y/Y|Y/Y|N|N|
|RENDER_USDT|1.985000|1.946000|1.985000|0.25|N|Y/Y|Y/Y|N|N|
|SILVER_USDT|58.590000|58.570000|58.580000|0.83|N|Y/Y|Y/Y|N|N|
|STRK_USDT|0.079040|0.077870|0.079050|0.32|N|Y/Y|Y/Y|N|N|
|S_USDT|0.056520|0.055860|0.056520|1.00|N|Y/Y|N/N|N|N|
|TIA_USDT|0.543800|0.540100|0.543800|0.91|N|Y/Y|Y/N|N|N|
|UNI_USDT|7.359000|7.328000|7.359000|0.15|N|Y/Y|Y/Y|N|N|
|W_USDT|0.016120|0.015659|0.016122|0.94|N|Y/Y|Y/Y|N|N|
|XLM_USDT|0.189400|0.188210|0.189400|0.23|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- DOT_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=1.148800, depth_time=2026-10-14T11:00:16+00:00, book20_bid_proxy_usdt=322074, book20_ask_proxy_usdt=343032, funding_indicative=0.000036, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.82%, turnover=18943217. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=1.163700, depth_time=2026-10-14T11:00:24+00:00, book20_bid_proxy_usdt=613852, book20_ask_proxy_usdt=363479, funding_indicative=-0.000033, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=25053725. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=0.086760, depth_time=2026-10-14T11:00:33+00:00, book20_bid_proxy_usdt=490708, book20_ask_proxy_usdt=491647, funding_indicative=0.000021, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.12%, turnover=13350225. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=3.101000, depth_time=2026-10-14T11:00:21+00:00, book20_bid_proxy_usdt=916984, book20_ask_proxy_usdt=699504, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=9240785. target_RR/account_short_permission/settled_funding=UNKNOWN.
- RENDER_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=2.004000, depth_time=2026-10-14T11:00:23+00:00, book20_bid_proxy_usdt=1924144, book20_ask_proxy_usdt=1472016, funding_indicative=0.000012, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.68%, turnover=8782742. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=58.750000, depth_time=2026-10-14T11:00:31+00:00, book20_bid_proxy_usdt=48351906, book20_ask_proxy_usdt=54891689, funding_indicative=0.000100, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-1.34%, turnover=257373277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=0.081940, depth_time=2026-10-14T11:00:08+00:00, book20_bid_proxy_usdt=280209, book20_ask_proxy_usdt=192249, funding_indicative=0.000050, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.46%, turnover=27611116. target_RR/account_short_permission/settled_funding=UNKNOWN.
- S_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=0.057200, depth_time=2026-10-14T11:00:07+00:00, book20_bid_proxy_usdt=161980, book20_ask_proxy_usdt=106690, funding_indicative=-0.000047, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-19.94%, turnover=24768784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=0.554100, depth_time=2026-10-14T11:00:11+00:00, book20_bid_proxy_usdt=164862, book20_ask_proxy_usdt=237942, funding_indicative=-0.000035, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.04%, turnover=35162604. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=7.382000, depth_time=2026-10-14T11:00:18+00:00, book20_bid_proxy_usdt=1495476, book20_ask_proxy_usdt=1158726, funding_indicative=0.000100, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.21%, turnover=18158136. target_RR/account_short_permission/settled_funding=UNKNOWN.
- W_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=0.016390, depth_time=2026-10-14T11:00:13+00:00, book20_bid_proxy_usdt=35074, book20_ask_proxy_usdt=28540, funding_indicative=-0.000266, next_funding_utc=2026-10-14T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.06%, turnover=6289003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-10-14T11:00:01+00:00, last15m_closed_end=2026-10-14T11:00+00:00, prior8high=0.190060, depth_time=2026-10-14T11:00:27+00:00, book20_bid_proxy_usdt=241571, book20_ask_proxy_usdt=121286, funding_indicative=-0.000113, next_funding_utc=2026-10-14T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.35%, turnover=9408881. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
