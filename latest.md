# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T12:00:42Z**
- feed_generated_utc: 2026-10-30T12:00:45+00:00
- source_sha256: `7376450e41a71ae2bb28f740275c024e25d021cc230e7dbe843d87073e786e3a`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.05 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.333400|-21.32|-25.50|-15.96|9417072|0.75|
|PYTH_USDT|0.060660|-15.35|-18.22|-9.99|5287990|1.65|
|TIA_USDT|0.463900|-14.56|-18.38|-9.20|20077557|2.16|
|CRV_USDT|0.286400|-13.44|-22.02|-8.08|9288164|3.49|
|ENA_USDT|0.185300|-11.23|-6.67|-5.87|114037474|1.62|
|FET_USDT|0.164500|-10.25|-11.22|-4.89|14116482|6.08|
|LDO_USDT|0.334800|-10.14|-12.47|-4.78|6315617|5.98|
|INJ_USDT|7.198000|-10.09|-9.25|-4.73|31107812|2.78|
|FARTCOIN_USDT|0.117790|-9.98|-17.53|-4.62|15550696|1.70|
|ETHFI_USDT|0.606400|-9.73|-8.44|-4.37|5821998|1.65|
|TAO_USDT|232.690000|-8.88|-9.68|-3.52|86730449|1.29|
|APT_USDT|0.626100|-8.82|-18.91|-3.46|11378041|1.60|
|TRUMPOFFICIAL_USDT|1.556000|-8.73|-10.77|-3.37|10752782|6.43|
|PENGU_USDT|0.007188|-8.63|-6.98|-3.27|10053203|2.78|
|LIT_USDT|2.824600|-8.42|-21.84|-3.06|17475228|0.35|
|PUMPFUN_USDT|0.004070|-8.12|-13.01|-2.76|30659784|2.46|
|SEI_USDT|0.048540|-7.40|-16.41|-2.04|6912529|2.06|
|JUP_USDT|0.254900|-7.30|-17.77|-1.94|6882223|3.92|
|ONDO_USDT|0.390600|-7.13|-9.37|-1.77|33457484|2.56|
|BNB_USDT|700.800000|-6.53|-4.17|-1.17|55640715|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.626100|0.612700|0.626100|0.91|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.333400|1.290100|1.333400|6.15|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.286400|0.280800|0.286400|0.69|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.185300|0.185060|0.185300|2.90|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.606400|0.603900|0.606400|1.25|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117790|0.116210|0.117790|0.90|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.164500|0.163000|0.164500|3.26|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.198000|7.100000|7.198000|0.45|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.334800|0.328200|0.334800|3.24|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.824600|2.777900|2.824600|0.26|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007188|0.007058|0.007188|0.71|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.060660|0.060420|0.060660|0.70|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|232.690000|231.840000|232.690000|0.63|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.463900|0.457700|0.463900|1.61|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.556000|1.544000|1.556000|0.28|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.629900, depth_time=2026-10-30T12:00:33+00:00, book20_bid_proxy_usdt=85335, book20_ask_proxy_usdt=118410, funding_indicative=0.000094, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-8.82%, turnover=11378041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=1.549900, depth_time=2026-10-30T12:00:07+00:00, book20_bid_proxy_usdt=12434, book20_ask_proxy_usdt=7902, funding_indicative=0.000040, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.32%, turnover=9417072. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.288000, depth_time=2026-10-30T12:00:14+00:00, book20_bid_proxy_usdt=559678, book20_ask_proxy_usdt=451330, funding_indicative=-0.000231, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-13.44%, turnover=9288164. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.191700, depth_time=2026-10-30T12:00:17+00:00, book20_bid_proxy_usdt=133428, book20_ask_proxy_usdt=76051, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.23%, turnover=114037474. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.613800, depth_time=2026-10-30T12:00:28+00:00, book20_bid_proxy_usdt=237297, book20_ask_proxy_usdt=138426, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.73%, turnover=5821998. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.119010, depth_time=2026-10-30T12:00:27+00:00, book20_bid_proxy_usdt=62862, book20_ask_proxy_usdt=29020, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.98%, turnover=15550696. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.166000, depth_time=2026-10-30T12:00:19+00:00, book20_bid_proxy_usdt=1106326, book20_ask_proxy_usdt=554450, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.25%, turnover=14116482. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=7.256000, depth_time=2026-10-30T12:00:25+00:00, book20_bid_proxy_usdt=228869, book20_ask_proxy_usdt=201990, funding_indicative=0.000034, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.09%, turnover=31107812. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.334700, depth_time=2026-10-30T12:00:21+00:00, book20_bid_proxy_usdt=378359, book20_ask_proxy_usdt=373389, funding_indicative=0.000087, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.14%, turnover=6315617. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=2.848700, depth_time=2026-10-30T12:00:41+00:00, book20_bid_proxy_usdt=21094, book20_ask_proxy_usdt=29472, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.42%, turnover=17475228. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.007281, depth_time=2026-10-30T12:00:39+00:00, book20_bid_proxy_usdt=140458, book20_ask_proxy_usdt=216142, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.63%, turnover=10053203. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.061880, depth_time=2026-10-30T12:00:09+00:00, book20_bid_proxy_usdt=138876, book20_ask_proxy_usdt=208303, funding_indicative=-0.000117, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-15.35%, turnover=5287990. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=235.330000, depth_time=2026-10-30T12:00:31+00:00, book20_bid_proxy_usdt=47432, book20_ask_proxy_usdt=94011, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.88%, turnover=86730449. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=0.470200, depth_time=2026-10-30T12:00:12+00:00, book20_bid_proxy_usdt=136658, book20_ask_proxy_usdt=192386, funding_indicative=0.000019, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.56%, turnover=20077557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T12:00:00+00:00, last15m_closed_end=2026-10-30T12:00+00:00, prior8high=1.573000, depth_time=2026-10-30T12:00:36+00:00, book20_bid_proxy_usdt=1582635, book20_ask_proxy_usdt=1446434, funding_indicative=-0.000045, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-8.73%, turnover=10752782. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
