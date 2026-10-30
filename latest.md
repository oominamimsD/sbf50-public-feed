# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T12:30:45Z**
- feed_generated_utc: 2026-10-30T12:30:48+00:00
- source_sha256: `f913fa23a8223eac89bc23fcba8ad5e9fbe7e1cdd74f8c395b94e8492f0bdcfe`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 18; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T12:30+00:00, close=77430.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T12:00+00:00, close=77345.8, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|BTW_USDT|1.288400|-21.34|-28.02|-16.07|9723195|1.55|
|PYTH_USDT|0.060830|-16.88|-17.99|-11.61|5306754|3.29|
|TIA_USDT|0.460100|-16.22|-19.05|-10.95|20471852|2.17|
|CRV_USDT|0.286100|-14.85|-22.10|-9.58|9440054|3.50|
|LIT_USDT|2.786900|-14.43|-22.89|-9.16|17677411|0.36|
|FARTCOIN_USDT|0.118330|-11.95|-17.15|-6.68|15636784|2.54|
|LDO_USDT|0.335900|-11.23|-12.18|-5.96|6410175|2.98|
|INJ_USDT|7.252000|-10.82|-8.57|-5.55|31476354|1.38|
|FET_USDT|0.164800|-10.82|-11.06|-5.55|14170000|6.07|
|APT_USDT|0.627800|-10.73|-18.69|-5.46|11592876|1.59|
|TRUMPOFFICIAL_USDT|1.551000|-10.24|-11.06|-4.97|10857204|6.45|
|ETHFI_USDT|0.610000|-10.22|-7.89|-4.95|5860148|1.64|
|TAO_USDT|232.650000|-10.09|-9.70|-4.82|87409480|1.29|
|PUMPFUN_USDT|0.004085|-9.72|-12.69|-4.45|30784723|2.45|
|JUP_USDT|0.255000|-9.51|-17.74|-4.24|6912353|3.92|
|AVAX_USDT|8.169000|-9.27|-10.87|-4.00|36428242|1.22|
|ZEC_USDT|1246.250000|-8.18|0.97|-2.91|2201960656|0.08|
|BNB_USDT|701.200000|-6.76|-4.11|-1.49|56242231|1.43|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.627800|0.617800|0.627900|2.13|N|Y/Y|Y/Y|Y|N|
|BTW_USDT|1.288400|1.248100|1.288600|2.33|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.286100|0.281300|0.286100|1.47|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.610000|0.604300|0.610000|1.34|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.118330|0.116870|0.118330|0.70|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.164800|0.163000|0.164800|0.39|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.252000|7.100000|7.251000|1.26|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.255000|0.252800|0.255000|1.09|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.335900|0.328800|0.335800|2.44|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.786900|2.774100|2.786900|2.69|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004085|0.004034|0.004085|0.92|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.060830|0.060360|0.060830|0.82|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|232.650000|231.840000|232.690000|1.52|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.460100|0.461700|0.460100|2.27|Y|Y/Y|Y/Y|Y|Y|
|TRUMPOFFICIAL_USDT|1.551000|1.545000|1.551000|2.09|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.632500, depth_time=2026-10-30T12:30:32+00:00, book20_bid_proxy_usdt=80984, book20_ask_proxy_usdt=72085, funding_indicative=0.000098, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.73%, turnover=11592876. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=1.549900, depth_time=2026-10-30T12:30:09+00:00, book20_bid_proxy_usdt=9143, book20_ask_proxy_usdt=26314, funding_indicative=0.000024, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-21.34%, turnover=9723195. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.288300, depth_time=2026-10-30T12:30:12+00:00, book20_bid_proxy_usdt=518627, book20_ask_proxy_usdt=500413, funding_indicative=-0.000219, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-14.85%, turnover=9440054. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.613800, depth_time=2026-10-30T12:30:35+00:00, book20_bid_proxy_usdt=132839, book20_ask_proxy_usdt=146768, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.22%, turnover=5860148. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.119010, depth_time=2026-10-30T12:30:21+00:00, book20_bid_proxy_usdt=33490, book20_ask_proxy_usdt=39957, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-11.95%, turnover=15636784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.166000, depth_time=2026-10-30T12:30:27+00:00, book20_bid_proxy_usdt=763332, book20_ask_proxy_usdt=546088, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.82%, turnover=14170000. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=7.256000, depth_time=2026-10-30T12:30:27+00:00, book20_bid_proxy_usdt=122293, book20_ask_proxy_usdt=173460, funding_indicative=0.000082, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-10.82%, turnover=31476354. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.257100, depth_time=2026-10-30T12:30:44+00:00, book20_bid_proxy_usdt=368640, book20_ask_proxy_usdt=473819, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.51%, turnover=6912353. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.336300, depth_time=2026-10-30T12:30:24+00:00, book20_bid_proxy_usdt=294653, book20_ask_proxy_usdt=264015, funding_indicative=0.000079, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.23%, turnover=6410175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=2.848700, depth_time=2026-10-30T12:30:18+00:00, book20_bid_proxy_usdt=24832, book20_ask_proxy_usdt=22025, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-14.43%, turnover=17677411. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.004139, depth_time=2026-10-30T12:30:41+00:00, book20_bid_proxy_usdt=1109467, book20_ask_proxy_usdt=1055082, funding_indicative=0.000012, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-9.72%, turnover=30784723. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.061880, depth_time=2026-10-30T12:30:10+00:00, book20_bid_proxy_usdt=102799, book20_ask_proxy_usdt=170732, funding_indicative=-0.000110, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.88%, turnover=5306754. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=235.330000, depth_time=2026-10-30T12:30:39+00:00, book20_bid_proxy_usdt=53327, book20_ask_proxy_usdt=40268, funding_indicative=0.000050, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.09%, turnover=87409480. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=0.470200, depth_time=2026-10-30T12:30:14+00:00, book20_bid_proxy_usdt=232319, book20_ask_proxy_usdt=214288, funding_indicative=0.000035, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-16.22%, turnover=20471852. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T12:30:03+00:00, last15m_closed_end=2026-10-30T12:30+00:00, prior8high=1.573000, depth_time=2026-10-30T12:30:33+00:00, book20_bid_proxy_usdt=1261820, book20_ask_proxy_usdt=1399127, funding_indicative=0.000000, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=4, 24h_change=-10.24%, turnover=10857204. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
