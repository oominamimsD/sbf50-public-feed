# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T05:15:43Z**
- feed_generated_utc: 2026-10-30T05:15:47+00:00
- source_sha256: `f6441499d4b1c73703ccf80cfc690cd1f191b094cbbeecf1ebaf9894a3be424c`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1195; contracts: 1187; crypto_prefilter: 15; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T05:15+00:00, close=78535.6, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-30T05:00+00:00, close=78237, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T04:00+00:00, close=78198.4, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|CRV_USDT|0.273300|-18.66|-25.59|-14.76|7985490|3.66|
|TIA_USDT|0.456700|-16.84|-19.65|-12.94|18887724|2.19|
|PYTH_USDT|0.062380|-14.76|-15.90|-10.86|5229004|4.81|
|LDO_USDT|0.326200|-13.79|-14.71|-9.89|6377353|3.07|
|FET_USDT|0.163300|-11.63|-11.87|-7.73|14014581|6.13|
|APT_USDT|0.623100|-11.40|-19.30|-7.50|12846362|4.82|
|BTW_USDT|1.456700|-11.07|-18.62|-7.17|11371836|2.06|
|FARTCOIN_USDT|0.119680|-10.95|-16.21|-7.05|15102520|1.67|
|PENGU_USDT|0.007253|-10.79|-6.14|-6.89|10104126|2.76|
|ETHFI_USDT|0.611600|-9.99|-7.65|-6.09|5932381|1.64|
|TRUMPOFFICIAL_USDT|1.566000|-9.37|-10.20|-5.47|11035832|6.38|
|INJ_USDT|7.377000|-9.28|-6.99|-5.38|30769335|2.71|
|JUP_USDT|0.255900|-9.19|-17.45|-5.29|6714096|3.91|
|SHIB_USDT|0.000005|-6.45|-5.63|-2.55|7932291|2.12|
|ETH_USDT|2247.180000|-5.10|-6.27|-1.20|2483956038|0.04|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.623100|0.602700|0.623100|1.22|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.456700|1.458400|1.456700|1.25|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.273300|0.267600|0.273300|0.67|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.611600|0.579200|0.611800|0.92|N|Y/Y|Y/Y|Y|N|
|ETH_USDT|2247.180000|2208.490000|2247.170000|1.00|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.119680|0.114070|0.119680|1.05|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163300|0.155300|0.163300|0.92|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.377000|7.071000|7.377000|0.53|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.255900|0.247500|0.256000|2.38|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.326200|0.314900|0.326200|0.87|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007253|0.006841|0.007253|1.77|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.062380|0.059550|0.062380|0.71|N|Y/Y|Y/Y|Y|N|
|SHIB_USDT|0.000005|0.000005|0.000005|1.07|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.456700|0.456500|0.456800|1.44|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.566000|1.518000|1.566000|1.66|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.622000, depth_time=2026-10-30T05:15:20+00:00, book20_bid_proxy_usdt=119184, book20_ask_proxy_usdt=85902, funding_indicative=-0.000170, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.40%, turnover=12846362. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=1.528200, depth_time=2026-10-30T05:15:19+00:00, book20_bid_proxy_usdt=11369, book20_ask_proxy_usdt=18979, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-11.07%, turnover=11371836. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.277500, depth_time=2026-10-30T05:15:08+00:00, book20_bid_proxy_usdt=481382, book20_ask_proxy_usdt=457059, funding_indicative=0.000019, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-18.66%, turnover=7985490. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.612900, depth_time=2026-10-30T05:15:31+00:00, book20_bid_proxy_usdt=237221, book20_ask_proxy_usdt=164522, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.99%, turnover=5932381. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETH_USDT: quote_utc=2026-10-30T05:15:01+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=2246.940000, depth_time=2026-10-30T05:15:43+00:00, book20_bid_proxy_usdt=1944825, book20_ask_proxy_usdt=4486701, funding_indicative=0.000020, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-5.10%, turnover=2483956038. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.119310, depth_time=2026-10-30T05:15:25+00:00, book20_bid_proxy_usdt=56541, book20_ask_proxy_usdt=37532, funding_indicative=0.000050, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.95%, turnover=15102520. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.161900, depth_time=2026-10-30T05:15:18+00:00, book20_bid_proxy_usdt=847053, book20_ask_proxy_usdt=743640, funding_indicative=-0.000568, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-11.63%, turnover=14014581. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=7.402000, depth_time=2026-10-30T05:15:35+00:00, book20_bid_proxy_usdt=250852, book20_ask_proxy_usdt=172388, funding_indicative=-0.000068, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-9.28%, turnover=30769335. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.255000, depth_time=2026-10-30T05:15:37+00:00, book20_bid_proxy_usdt=525904, book20_ask_proxy_usdt=467109, funding_indicative=-0.000080, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.19%, turnover=6714096. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.324500, depth_time=2026-10-30T05:15:13+00:00, book20_bid_proxy_usdt=359973, book20_ask_proxy_usdt=315750, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-13.79%, turnover=6377353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.007253, depth_time=2026-10-30T05:15:28+00:00, book20_bid_proxy_usdt=129296, book20_ask_proxy_usdt=140287, funding_indicative=0.000005, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.79%, turnover=10104126. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.061300, depth_time=2026-10-30T05:15:12+00:00, book20_bid_proxy_usdt=178084, book20_ask_proxy_usdt=200748, funding_indicative=-0.000128, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-14.76%, turnover=5229004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SHIB_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.000005, depth_time=2026-10-30T05:15:39+00:00, book20_bid_proxy_usdt=154263, book20_ask_proxy_usdt=132136, funding_indicative=0.000100, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.45%, turnover=7932291. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=0.466000, depth_time=2026-10-30T05:15:10+00:00, book20_bid_proxy_usdt=397813, book20_ask_proxy_usdt=172347, funding_indicative=0.000005, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-16.84%, turnover=18887724. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T05:15:02+00:00, last15m_closed_end=2026-10-30T05:15+00:00, prior8high=1.565000, depth_time=2026-10-30T05:15:26+00:00, book20_bid_proxy_usdt=1663344, book20_ask_proxy_usdt=1430487, funding_indicative=0.000045, next_funding_utc=2026-10-30T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.37%, turnover=11035832. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
