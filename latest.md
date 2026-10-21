# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T10:30:33Z**
- feed_generated_utc: 2026-10-21T10:30:35+00:00
- source_sha256: `8207a607e71121b5f181284ff43c514db571dbb2ada3e58e1ca45d9420f9543e`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 55/55 successful
- tickers: 1202; contracts: 1194; crypto_prefilter: 10; crypto_deep: 10
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T10:30+00:00, close=83276.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T10:00+00:00, close=83402.2, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T08:00+00:00, close=83117.5, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AGT_USDT|0.049338|-23.65|204.98|-24.49|6714910|7.72|
|BAT_USDT|0.182560|-15.39|2.92|-16.23|11072552|2.19|
|BR_USDT|0.579850|-10.88|33.91|-11.72|25141845|0.52|
|BTW_USDT|1.714400|-7.30|-12.19|-8.14|26058885|2.33|
|Q_USDT|0.118516|-3.45|188.17|-4.29|5686521|0.42|
|SILVER_USDT|57.460000|-0.84|-3.24|-1.68|222607451|1.74|
|DOT_USDT|1.147800|-0.84|-0.78|-1.68|14454103|0.87|
|TIA_USDT|0.620900|-0.28|7.55|-1.12|46130963|3.22|
|XAU_USDT|4128.310000|-0.26|-0.89|-1.10|387277450|0.02|
|XAUT_USDT|4120.710000|-0.17|-0.86|-1.01|148916417|0.07|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AGT_USDT|0.049338|0.042549|0.049356|0.55|N|Y/Y|Y/Y|N|N|
|BAT_USDT|0.182560|0.181440|0.182560|1.37|N|Y/Y|Y/Y|N|N|
|BR_USDT|0.579850|0.566870|0.579850|0.75|N|Y/Y|N/N|N|N|
|BTW_USDT|1.714400|1.683300|1.715100|4.66|N|N/N|N/N|N|N|
|DOT_USDT|1.147800|1.146800|1.147800|1.98|N|Y/N|N/N|N|N|
|Q_USDT|0.118516|0.117892|0.118500|1.09|N|Y/Y|N/N|N|N|
|SILVER_USDT|57.460000|57.300000|57.460000|6.14|N|Y/Y|N/N|N|N|
|TIA_USDT|0.620900|0.615500|0.620900|1.69|N|Y/N|N/Y|N|N|
|XAUT_USDT|4120.710000|4115.890000|4120.710000|1.12|N|Y/Y|Y/Y|N|N|
|XAU_USDT|4128.310000|4122.850000|4128.480000|1.24|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AGT_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=0.051865, depth_time=2026-10-21T10:30:08+00:00, book20_bid_proxy_usdt=9909, book20_ask_proxy_usdt=5724, funding_indicative=0.000047, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-23.65%, turnover=6714910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BAT_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=0.188530, depth_time=2026-10-21T10:30:10+00:00, book20_bid_proxy_usdt=29474, book20_ask_proxy_usdt=41396, funding_indicative=-0.000110, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.39%, turnover=11072552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=0.627970, depth_time=2026-10-21T10:30:13+00:00, book20_bid_proxy_usdt=2989, book20_ask_proxy_usdt=3073, funding_indicative=-0.000036, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.88%, turnover=25141845. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=2.153000, depth_time=2026-10-21T10:30:15+00:00, book20_bid_proxy_usdt=8699, book20_ask_proxy_usdt=5978, funding_indicative=-0.001298, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.30%, turnover=26058885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=1.162400, depth_time=2026-10-21T10:30:24+00:00, book20_bid_proxy_usdt=357723, book20_ask_proxy_usdt=344848, funding_indicative=-0.000297, next_funding_utc=2026-10-21T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.84%, turnover=14454103. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=0.125729, depth_time=2026-10-21T10:30:18+00:00, book20_bid_proxy_usdt=13827, book20_ask_proxy_usdt=15364, funding_indicative=0.000008, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.45%, turnover=5686521. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=57.610000, depth_time=2026-10-21T10:30:19+00:00, book20_bid_proxy_usdt=32395099, book20_ask_proxy_usdt=31664068, funding_indicative=0.000018, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.84%, turnover=222607451. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=0.642000, depth_time=2026-10-21T10:30:27+00:00, book20_bid_proxy_usdt=297657, book20_ask_proxy_usdt=305566, funding_indicative=-0.000092, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.28%, turnover=46130963. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAUT_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=4126.350000, depth_time=2026-10-21T10:30:29+00:00, book20_bid_proxy_usdt=264305, book20_ask_proxy_usdt=79999, funding_indicative=0.000050, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.17%, turnover=148916417. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XAU_USDT: quote_utc=2026-10-21T10:30:02+00:00, last15m_closed_end=2026-10-21T10:30+00:00, prior8high=4133.460000, depth_time=2026-10-21T10:30:28+00:00, book20_bid_proxy_usdt=817177, book20_ask_proxy_usdt=527190, funding_indicative=0.000065, next_funding_utc=2026-10-21T12:00:00+00:00, funding_cycle_h=4, 24h_change=-0.26%, turnover=387277450. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
