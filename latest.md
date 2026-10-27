# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-27T02:30:44Z**
- feed_generated_utc: 2026-10-27T02:30:48+00:00
- source_sha256: `486aafdc46449d400751ab370766550135cb9433673a407645e606fc1c4e2c36`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.07 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-27T02:30+00:00, close=79928.6, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-27T02:00+00:00, close=80041.9, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-27T00:00+00:00, close=80115.5, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|ZRO_USDT|1.613400|-5.48|-15.17|-4.91|5203491|0.62|
|PUMPFUN_USDT|0.004196|-3.04|-5.83|-2.47|21086097|2.38|
|NEAR_USDT|4.443000|-2.84|-9.40|-2.27|105626449|2.25|
|AAVE_USDT|133.100000|-2.65|-9.59|-2.08|25681042|0.75|
|ONDO_USDT|0.407900|-2.60|-5.70|-2.03|22537832|2.45|
|DOT_USDT|0.997100|-2.49|-13.05|-1.92|10853571|1.00|
|ENA_USDT|0.205600|-2.26|9.40|-1.69|99019642|0.49|
|FILECOIN_USDT|0.900400|-2.20|-11.02|-1.63|6460885|2.22|
|FET_USDT|0.172700|-2.20|-8.62|-1.63|6104037|5.79|
|TAO_USDT|248.540000|-1.96|-7.36|-1.39|46531280|1.21|
|LINK_USDT|11.317000|-1.83|-5.24|-1.26|105541798|1.77|
|ICP_USDT|2.582000|-1.82|-9.49|-1.25|5239010|3.87|
|PEPE_USDT|0.000004|-1.78|4.26|-1.21|77194202|0.23|
|WLD_USDT|0.437100|-1.77|-13.66|-1.20|69992315|2.29|
|AVAX_USDT|8.848000|-1.65|-7.46|-1.08|71141552|1.13|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|133.100000|134.200000|133.100000|8.21|Y|Y/Y|Y/Y|Y|Y|
|AVAX_USDT|8.848000|8.873000|8.848000|1.92|Y|Y/N|Y/Y|Y|N|
|DOT_USDT|0.997100|0.995200|0.997100|0.34|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.205600|0.206180|0.205500|0.16|N|N/N|N/N|Y|N|
|FET_USDT|0.172700|0.173200|0.172700|0.64|N|Y/Y|Y/Y|Y|N|
|FILECOIN_USDT|0.900400|0.902400|0.900400|0.21|N|Y/Y|Y/Y|Y|N|
|ICP_USDT|2.582000|2.589000|2.582000|0.89|N|Y/N|Y/Y|Y|N|
|LINK_USDT|11.317000|11.303000|11.316000|1.11|N|Y/Y|Y/Y|Y|N|
|NEAR_USDT|4.443000|4.446000|4.443000|1.58|Y|Y/Y|Y/Y|Y|Y|
|ONDO_USDT|0.407900|0.408600|0.407900|1.19|N|Y/N|N/N|Y|N|
|PEPE_USDT|0.000004|0.000004|0.000004|0.54|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004196|0.004214|0.004196|1.26|N|Y/N|Y/Y|Y|N|
|TAO_USDT|248.540000|249.130000|248.540000|0.72|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.437100|0.438100|0.437100|0.89|N|Y/N|Y/Y|Y|N|
|ZRO_USDT|1.613400|1.607900|1.613400|0.16|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=136.180000, depth_time=2026-10-27T02:30:16+00:00, book20_bid_proxy_usdt=437593, book20_ask_proxy_usdt=326401, funding_indicative=0.000070, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.65%, turnover=25681042. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=8.983000, depth_time=2026-10-27T02:30:42+00:00, book20_bid_proxy_usdt=1769351, book20_ask_proxy_usdt=1269027, funding_indicative=0.000066, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=71141552. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=1.012700, depth_time=2026-10-27T02:30:21+00:00, book20_bid_proxy_usdt=377140, book20_ask_proxy_usdt=456390, funding_indicative=-0.000086, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.49%, turnover=10853571. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-27T02:30:02+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=0.211500, depth_time=2026-10-27T02:30:24+00:00, book20_bid_proxy_usdt=112066, book20_ask_proxy_usdt=146364, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.26%, turnover=99019642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=0.176400, depth_time=2026-10-27T02:30:28+00:00, book20_bid_proxy_usdt=1695185, book20_ask_proxy_usdt=1105766, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=6104037. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FILECOIN_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=0.916600, depth_time=2026-10-27T02:30:26+00:00, book20_bid_proxy_usdt=859496, book20_ask_proxy_usdt=1404693, funding_indicative=0.000051, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.20%, turnover=6460885. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=2.635000, depth_time=2026-10-27T02:30:33+00:00, book20_bid_proxy_usdt=1110386, book20_ask_proxy_usdt=1067970, funding_indicative=0.000100, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.82%, turnover=5239010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=11.421000, depth_time=2026-10-27T02:30:33+00:00, book20_bid_proxy_usdt=469821, book20_ask_proxy_usdt=492430, funding_indicative=0.000072, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.83%, turnover=105541798. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-10-27T02:30:02+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=4.533000, depth_time=2026-10-27T02:30:13+00:00, book20_bid_proxy_usdt=5547351, book20_ask_proxy_usdt=3653859, funding_indicative=0.000058, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.84%, turnover=105626449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=0.415400, depth_time=2026-10-27T02:30:18+00:00, book20_bid_proxy_usdt=2407553, book20_ask_proxy_usdt=3182280, funding_indicative=0.000037, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.60%, turnover=22537832. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=0.000004, depth_time=2026-10-27T02:30:38+00:00, book20_bid_proxy_usdt=70069, book20_ask_proxy_usdt=33250, funding_indicative=0.000028, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=77194202. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=0.004314, depth_time=2026-10-27T02:30:11+00:00, book20_bid_proxy_usdt=2614220, book20_ask_proxy_usdt=2180619, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.04%, turnover=21086097. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=252.300000, depth_time=2026-10-27T02:30:31+00:00, book20_bid_proxy_usdt=92868, book20_ask_proxy_usdt=90393, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.96%, turnover=46531280. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=0.446900, depth_time=2026-10-27T02:30:40+00:00, book20_bid_proxy_usdt=3709258, book20_ask_proxy_usdt=2451628, funding_indicative=-0.000169, next_funding_utc=2026-10-27T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.77%, turnover=69992315. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-27T02:30:03+00:00, last15m_closed_end=2026-10-27T02:30+00:00, prior8high=1.647700, depth_time=2026-10-27T02:30:09+00:00, book20_bid_proxy_usdt=64779, book20_ask_proxy_usdt=19241, funding_indicative=0.000050, next_funding_utc=2026-10-27T04:00:00+00:00, funding_cycle_h=4, 24h_change=-5.48%, turnover=5203491. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
