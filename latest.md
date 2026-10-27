# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T12:45:31Z**
- feed_generated_utc: 2026-10-27T12:45:34+00:00
- source_sha256: `29aa45be68da2a7ef5f00db8b7fdfc43676ac51a25d732a14e9ae6309a7abc79`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 50/50 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 9; crypto_deep: 9
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T12:45+00:00, close=80317.3, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T12:00+00:00, close=79880.3, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IRYS_USDT|0.024820|-10.00|102.11|-9.90|7305204|4.03|
|QNT_USDT|202.100000|-3.89|3.27|-3.79|113764933|0.49|
|DOT_USDT|0.993000|-2.89|-13.41|-2.79|11181760|1.01|
|AAVE_USDT|132.830000|-2.85|-9.77|-2.75|28363064|0.75|
|FILECOIN_USDT|0.899300|-2.32|-11.13|-2.22|6651794|1.11|
|WLD_USDT|0.436700|-1.86|-13.74|-1.76|67996555|2.29|
|HBAR_USDT|0.076360|-1.29|-6.73|-1.19|11553622|1.31|
|ICP_USDT|2.598000|-1.21|-8.93|-1.11|5204947|3.85|
|TIA_USDT|0.529400|-1.17|-12.99|-1.07|17467900|1.89|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|132.830000|129.950000|132.830000|2.06|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.993000|0.981400|0.993000|1.26|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.899300|0.887200|0.899300|3.31|N|Y/Y|Y/Y|Y|N|
|HBAR_USDT|0.076360|0.075550|0.076360|9.56|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.598000|2.565000|2.598000|1.63|N|Y/Y|Y/Y|Y|N|
|IRYS_USDT|0.024820|0.024650|0.024830|0.53|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|202.100000|200.570000|202.100000|0.81|N|Y/N|N/N|Y|N|
|TIA_USDT|0.529400|0.522500|0.529500|0.92|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.436700|0.428600|0.436400|1.15|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=132.270000, depth_time=2026-10-27T12:45:17+00:00, book20_bid_proxy_usdt=453071, book20_ask_proxy_usdt=348436, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.85%, turnover=28363064. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=0.992500, depth_time=2026-10-27T12:45:14+00:00, book20_bid_proxy_usdt=511945, book20_ask_proxy_usdt=576914, funding_indicative=-0.000117, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.89%, turnover=11181760. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=0.900900, depth_time=2026-10-27T12:45:14+00:00, book20_bid_proxy_usdt=1278885, book20_ask_proxy_usdt=1503146, funding_indicative=0.000067, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=6651794. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=0.076310, depth_time=2026-10-27T12:45:25+00:00, book20_bid_proxy_usdt=1183086, book20_ask_proxy_usdt=1125082, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=11553622. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=2.597000, depth_time=2026-10-27T12:45:26+00:00, book20_bid_proxy_usdt=1111123, book20_ask_proxy_usdt=1061526, funding_indicative=0.000100, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.21%, turnover=5204947. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IRYS_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=0.025440, depth_time=2026-10-27T12:45:08+00:00, book20_bid_proxy_usdt=131395, book20_ask_proxy_usdt=135154, funding_indicative=-0.000330, next_funding_utc=2026-10-27T13:00:00+00:00, funding_cycle_h=1, 24h_change=-10.00%, turnover=7305204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=206.180000, depth_time=2026-10-27T12:45:11+00:00, book20_bid_proxy_usdt=39361, book20_ask_proxy_usdt=65452, funding_indicative=-0.000200, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.89%, turnover=113764933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=0.529500, depth_time=2026-10-27T12:45:29+00:00, book20_bid_proxy_usdt=170172, book20_ask_proxy_usdt=570246, funding_indicative=0.000050, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.17%, turnover=17467900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T12:45:03+00:00, last15m_closed_end=2026-10-27T12:45+00:00, prior8high=0.435700, depth_time=2026-10-27T12:45:21+00:00, book20_bid_proxy_usdt=2995593, book20_ask_proxy_usdt=3156514, funding_indicative=-0.000049, next_funding_utc=2026-10-27T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.86%, turnover=67996555. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
