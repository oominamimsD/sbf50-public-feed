# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-29T14:45:24Z**
- feed_generated_utc: 2026-10-29T14:45:25+00:00
- source_sha256: `acc7c9ef6b034e59a7ea5a4d374c228a91e08cd1d970e93c9f7002713b23f2c0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 40/40 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 7; crypto_deep: 7
- snapshot_age_at_feed_build: 0.02 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-29T14:45+00:00, close=81210, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-29T14:00+00:00, close=80275.1, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-29T12:00+00:00, close=80133.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|Q_USDT|0.040940|-34.25|-64.75|-35.09|34169871|2.44|
|EVAA_USDT|1.170600|-21.17|107.70|-22.01|18941268|4.28|
|BLESS_USDT|0.009639|-12.02|19.76|-12.86|9392999|9.34|
|DASH_USDT|50.930000|-3.97|-4.39|-4.81|15224755|1.97|
|BTW_USDT|1.698200|-2.28|15.53|-3.12|9810562|1.18|
|SILVER_USDT|52.840000|-1.54|-8.35|-2.38|554371425|1.89|
|XRP_USDT|1.304400|-0.51|-5.49|-1.35|303018735|0.77|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|BLESS_USDT|0.009639|0.009476|0.009637|1.27|N|Y/Y|Y/N|Y|N|
|BTW_USDT|1.698200|1.606100|1.699900|1.01|N|N/N|N/N|Y|N|
|DASH_USDT|50.930000|49.890000|50.930000|1.70|N|Y/Y|Y/Y|Y|N|
|EVAA_USDT|1.170600|1.161100|1.170500|0.70|N|Y/Y|N/N|Y|N|
|Q_USDT|0.040940|0.040040|0.040940|0.81|N|Y/Y|Y/Y|Y|N|
|SILVER_USDT|52.840000|52.110000|52.830000|0.96|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.304400|1.285100|1.305100|5.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- BLESS_USDT: quote_utc=2026-10-29T14:45:02+00:00, last15m_closed_end=2026-10-29T14:45+00:00, prior8high=0.009702, depth_time=2026-10-29T14:45:12+00:00, book20_bid_proxy_usdt=8537, book20_ask_proxy_usdt=6460, funding_indicative=0.000263, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-12.02%, turnover=9392999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-29T14:45:02+00:00, last15m_closed_end=2026-10-29T14:45+00:00, prior8high=1.794200, depth_time=2026-10-29T14:45:18+00:00, book20_bid_proxy_usdt=19316, book20_ask_proxy_usdt=26122, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.28%, turnover=9810562. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-10-29T14:45:02+00:00, last15m_closed_end=2026-10-29T14:45+00:00, prior8high=50.660000, depth_time=2026-10-29T14:45:15+00:00, book20_bid_proxy_usdt=380735, book20_ask_proxy_usdt=481429, funding_indicative=0.000016, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.97%, turnover=15224755. target_RR/account_short_permission/settled_funding=UNKNOWN.
- EVAA_USDT: quote_utc=2026-10-29T14:45:02+00:00, last15m_closed_end=2026-10-29T14:45+00:00, prior8high=1.276800, depth_time=2026-10-29T14:45:10+00:00, book20_bid_proxy_usdt=15395, book20_ask_proxy_usdt=6311, funding_indicative=0.000174, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.17%, turnover=18941268. target_RR/account_short_permission/settled_funding=UNKNOWN.
- Q_USDT: quote_utc=2026-10-29T14:45:02+00:00, last15m_closed_end=2026-10-29T14:45+00:00, prior8high=0.042860, depth_time=2026-10-29T14:45:07+00:00, book20_bid_proxy_usdt=61692, book20_ask_proxy_usdt=65961, funding_indicative=0.000050, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.25%, turnover=34169871. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SILVER_USDT: quote_utc=2026-10-29T14:45:02+00:00, last15m_closed_end=2026-10-29T14:45+00:00, prior8high=52.820000, depth_time=2026-10-29T14:45:20+00:00, book20_bid_proxy_usdt=41226799, book20_ask_proxy_usdt=41010420, funding_indicative=0.000082, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.54%, turnover=554371425. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-10-29T14:45:02+00:00, last15m_closed_end=2026-10-29T14:45+00:00, prior8high=1.294800, depth_time=2026-10-29T14:45:23+00:00, book20_bid_proxy_usdt=3845257, book20_ask_proxy_usdt=3808195, funding_indicative=0.000100, next_funding_utc=2026-10-29T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.51%, turnover=303018735. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
