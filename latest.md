# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-08T14:00:42Z**
- feed_generated_utc: 2026-11-08T14:00:43+00:00
- source_sha256: `960a03d32630dc651a7e70556e5bff29c5a4719bbb1fa97278007c2edcbc0713`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-08T14:00+00:00, close=75895.8, belowEMA20=True, EMA20down3=False
- BTC Min60: closed_end=2026-11-08T14:00+00:00, close=75895.8, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-08T12:00+00:00, close=75944.2, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.005362|-10.37|-51.85|-10.59|26587933|1.86|
|ONE_USDT|0.001830|-10.16|55.82|-10.38|22972520|1.64|
|IDOL_USDT|0.030200|-9.30|72.36|-9.52|15658821|1.99|
|TIA_USDT|0.420500|-4.64|-14.20|-4.86|6915289|2.38|
|ENA_USDT|0.153470|-4.23|-20.89|-4.45|29137154|0.65|
|WLD_USDT|0.324900|-3.41|-19.65|-3.63|24271256|3.08|
|AAVE_USDT|129.000000|-2.08|-4.80|-2.30|9362131|0.78|
|LINK_USDT|10.710000|-1.78|-7.44|-2.00|60384934|0.93|
|ADA_USDT|0.179500|-1.69|-7.28|-1.91|10339149|5.57|
|SUI_USDT|0.849700|-1.28|-5.79|-1.50|22939694|1.18|
|LIT_USDT|3.199100|-1.27|9.61|-1.49|8087861|0.31|
|AVAX_USDT|8.167000|-1.04|-4.31|-1.26|8504736|1.23|
|ONDO_USDT|0.360700|-0.96|-12.53|-1.18|7167766|2.77|
|UNI_USDT|6.961000|-0.78|-0.82|-1.00|27569945|1.44|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|129.000000|129.540000|129.000000|6.57|Y|Y/Y|Y/N|Y|N|
|ADA_USDT|0.179500|0.179500|0.179500|1.15|N|Y/Y|Y/Y|Y|N|
|AKE_USDT|0.005362|0.005312|0.005359|0.34|N|Y/N|N/N|Y|N|
|AVAX_USDT|8.167000|8.152000|8.167000|3.89|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.153470|0.152800|0.153470|0.85|N|Y/Y|Y/Y|Y|N|
|IDOL_USDT|0.030200|0.028182|0.030122|0.35|N|Y/Y|N/N|Y|N|
|LINK_USDT|10.710000|10.706000|10.710000|1.16|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.199100|3.195800|3.199100|1.23|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360700|0.361100|0.360700|2.22|Y|Y/N|Y/Y|Y|N|
|ONE_USDT|0.001830|0.001830|0.001830|0.82|N|Y/Y|N/N|Y|N|
|SUI_USDT|0.849700|0.849300|0.849700|6.65|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.420500|0.421400|0.420500|2.88|Y|Y/Y|Y/Y|Y|Y|
|UNI_USDT|6.961000|6.968000|6.962000|1.60|Y|Y/Y|Y/Y|Y|Y|
|WLD_USDT|0.324900|0.324400|0.324900|3.49|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=131.400000, depth_time=2026-11-08T14:00:21+00:00, book20_bid_proxy_usdt=381293, book20_ask_proxy_usdt=358031, funding_indicative=0.000065, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=9362131. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.181200, depth_time=2026-11-08T14:00:27+00:00, book20_bid_proxy_usdt=9124081, book20_ask_proxy_usdt=9314975, funding_indicative=-0.000041, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.69%, turnover=10339149. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.005766, depth_time=2026-11-08T14:00:07+00:00, book20_bid_proxy_usdt=42395, book20_ask_proxy_usdt=33497, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.37%, turnover=26587933. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=8.225000, depth_time=2026-11-08T14:00:35+00:00, book20_bid_proxy_usdt=1711529, book20_ask_proxy_usdt=2275793, funding_indicative=0.000035, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.04%, turnover=8504736. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.155690, depth_time=2026-11-08T14:00:17+00:00, book20_bid_proxy_usdt=248642, book20_ask_proxy_usdt=279916, funding_indicative=-0.000096, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.23%, turnover=29137154. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.032257, depth_time=2026-11-08T14:00:12+00:00, book20_bid_proxy_usdt=8307, book20_ask_proxy_usdt=3687, funding_indicative=0.000852, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.30%, turnover=15658821. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LINK_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=10.794000, depth_time=2026-11-08T14:00:25+00:00, book20_bid_proxy_usdt=478080, book20_ask_proxy_usdt=552684, funding_indicative=-0.000001, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.78%, turnover=60384934. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=3.276300, depth_time=2026-11-08T14:00:33+00:00, book20_bid_proxy_usdt=38690, book20_ask_proxy_usdt=55675, funding_indicative=0.000050, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-1.27%, turnover=8087861. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.365700, depth_time=2026-11-08T14:00:38+00:00, book20_bid_proxy_usdt=1501457, book20_ask_proxy_usdt=1852050, funding_indicative=0.000042, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-0.96%, turnover=7167766. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONE_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.001956, depth_time=2026-11-08T14:00:10+00:00, book20_bid_proxy_usdt=9098, book20_ask_proxy_usdt=11323, funding_indicative=-0.000626, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.16%, turnover=22972520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SUI_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.859000, depth_time=2026-11-08T14:00:30+00:00, book20_bid_proxy_usdt=2036705, book20_ask_proxy_usdt=1567460, funding_indicative=0.000039, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.28%, turnover=22939694. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.427000, depth_time=2026-11-08T14:00:15+00:00, book20_bid_proxy_usdt=292262, book20_ask_proxy_usdt=358347, funding_indicative=-0.000040, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.64%, turnover=6915289. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=7.050000, depth_time=2026-11-08T14:00:41+00:00, book20_bid_proxy_usdt=2204907, book20_ask_proxy_usdt=2737774, funding_indicative=-0.000083, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-0.78%, turnover=27569945. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-08T14:00:02+00:00, last15m_closed_end=2026-11-08T14:00+00:00, prior8high=0.329500, depth_time=2026-11-08T14:00:18+00:00, book20_bid_proxy_usdt=3426399, book20_ask_proxy_usdt=4166788, funding_indicative=-0.000074, next_funding_utc=2026-11-08T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.41%, turnover=24271256. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
