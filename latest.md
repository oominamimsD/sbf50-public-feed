# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T15:00:37Z**
- feed_generated_utc: 2026-10-29T15:00:39+00:00
- source_sha256: `7f89ef508976dd1a2953e83ba47e4236f36bb3d271d85ca7460dcd0f9fa19dc5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T15:00+00:00, close=81149.9, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T15:00+00:00, close=81149.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.040230|-30.38|-65.37|-31.22|33966706|4.96|
|EVAA_USDT|1.183200|-20.32|109.93|-21.16|16931338|8.46|
|BLESS_USDT|0.009666|-11.34|20.10|-12.18|8116603|1.03|
|DASH_USDT|50.750000|-4.31|-4.73|-5.15|14921652|1.97|
|BTW_USDT|1.694800|-2.70|15.30|-3.54|9155854|0.59|
|HBAR_USDT|0.074420|-1.96|-13.40|-2.80|15179329|1.34|
|SILVER_USDT|52.720000|-1.77|-8.56|-2.61|539761456|1.90|
|WLD_USDT|0.426100|-1.54|-25.71|-2.38|78744376|2.35|
|XRP_USDT|1.302600|-0.65|-5.62|-1.49|292944972|0.77|
|LTC_USDT|57.840000|-0.48|-6.78|-1.32|11438358|3.46|
|XAU_USDT|4033.950000|-0.39|-2.54|-1.23|611982296|0.03|
|XAUT_USDT|4023.600000|-0.32|-2.57|-1.16|254891522|0.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009666|0.009476|0.009666|0.56|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.694800|1.606100|1.694800|0.77|N|Y/Y|N/N|Y|N|
|DASH_USDT|50.750000|50.030000|50.740000|1.34|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.183200|1.161100|1.185600|0.52|N|Y/Y|N/N|Y|N|
|HBAR_USDT|0.074420|0.073740|0.074430|1.99|N|N/N|Y/Y|Y|N|
|LTC_USDT|57.840000|57.610000|57.840000|1.62|N|Y/N|N/Y|Y|N|
|Q_USDT|0.040230|0.040040|0.040230|1.38|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.720000|52.110000|52.720000|1.70|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.426100|0.417800|0.425700|1.51|N|N/Y|Y/Y|Y|N|
|XAUT_USDT|4023.600000|4015.260000|4023.500000|0.68|N|Y/Y|Y/Y|Y|N|
|XAU_USDT|4033.950000|4025.250000|4033.950000|1.21|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.302600|1.285100|1.302000|3.25|N|N/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=0.009702, depth_time=2026-10-29T15:00:14+00:00, book20_bid_proxy_usdt=17976, book20_ask_proxy_usdt=5929, funding_indicative=0.000281, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.34%, turnover=8116603. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=1.791500, depth_time=2026-10-29T15:00:16+00:00, book20_bid_proxy_usdt=11668, book20_ask_proxy_usdt=20823, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.70%, turnover=9155854. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=51.010000, depth_time=2026-10-29T15:00:15+00:00, book20_bid_proxy_usdt=500711, book20_ask_proxy_usdt=482044, funding_indicative=0.000012, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.31%, turnover=14921652. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=1.249100, depth_time=2026-10-29T15:00:11+00:00, book20_bid_proxy_usdt=6751, book20_ask_proxy_usdt=11059, funding_indicative=0.000179, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-20.32%, turnover=16931338. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=0.075160, depth_time=2026-10-29T15:00:21+00:00, book20_bid_proxy_usdt=630006, book20_ask_proxy_usdt=934591, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.96%, turnover=15179329. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LTC_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=58.420000, depth_time=2026-10-29T15:00:31+00:00, book20_bid_proxy_usdt=1774508, book20_ask_proxy_usdt=1788467, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.48%, turnover=11438358. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=0.042860, depth_time=2026-10-29T15:00:09+00:00, book20_bid_proxy_usdt=59339, book20_ask_proxy_usdt=45804, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-30.38%, turnover=33966706. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=52.870000, depth_time=2026-10-29T15:00:23+00:00, book20_bid_proxy_usdt=36638938, book20_ask_proxy_usdt=38859127, funding_indicative=0.000085, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.77%, turnover=539761456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=0.432400, depth_time=2026-10-29T15:00:26+00:00, book20_bid_proxy_usdt=3050090, book20_ask_proxy_usdt=2772962, funding_indicative=0.000047, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.54%, turnover=78744376. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=4033.370000, depth_time=2026-10-29T15:00:36+00:00, book20_bid_proxy_usdt=79181, book20_ask_proxy_usdt=230708, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.32%, turnover=254891522. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=4044.990000, depth_time=2026-10-29T15:00:33+00:00, book20_bid_proxy_usdt=1862132, book20_ask_proxy_usdt=2565450, funding_indicative=0.000044, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.39%, turnover=611982296. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T15:00:02+00:00, last15m_closed_end=2026-10-29T15:00+00:00, prior8high=1.307900, depth_time=2026-10-29T15:00:28+00:00, book20_bid_proxy_usdt=3067958, book20_ask_proxy_usdt=2885969, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.65%, turnover=292944972. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
