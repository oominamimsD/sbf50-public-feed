# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-30T10:30:43Z**
- feed_generated_utc: 2026-10-30T10:30:47+00:00
- source_sha256: `028aaa9fddf314387a3fd5de6c5db03efdf63f1d7140cfa416c342a998564ad1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1194; contracts: 1186; crypto_prefilter: 22; crypto_deep: 15
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-30T10:30+00:00, close=77365.3, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-10-30T10:00+00:00, close=77654.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-10-30T08:00+00:00, close=78147.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PYTH_USDT|0.061330|-16.20|-17.32|-10.86|5263135|1.63|
|CRV_USDT|0.283900|-15.50|-22.70|-10.16|9293589|3.53|
|TIA_USDT|0.468100|-14.76|-17.64|-9.42|19891092|2.14|
|LIT_USDT|2.829300|-13.12|-21.71|-7.78|18187177|0.35|
|FARTCOIN_USDT|0.117200|-12.79|-17.95|-7.45|15531926|0.85|
|LDO_USDT|0.330100|-12.76|-13.69|-7.42|6357218|3.03|
|INJ_USDT|7.134000|-12.27|-10.06|-6.93|32345685|1.40|
|PENGU_USDT|0.007144|-12.13|-7.55|-6.79|9964036|2.80|
|APT_USDT|0.620700|-11.74|-19.61|-6.40|11958456|3.22|
|FET_USDT|0.163400|-11.58|-11.81|-6.24|14126953|6.12|
|ETHFI_USDT|0.606400|-10.75|-8.44|-5.41|5858737|1.65|
|TAO_USDT|232.600000|-10.11|-9.72|-4.77|87742669|1.29|
|PUMPFUN_USDT|0.004071|-10.03|-12.99|-4.69|30514193|2.46|
|TRUMPOFFICIAL_USDT|1.556000|-9.95|-10.77|-4.61|11083430|6.42|
|JUP_USDT|0.254700|-9.61|-17.83|-4.27|7054783|3.93|
|ONDO_USDT|0.389100|-9.46|-9.72|-4.12|34314497|2.57|
|BTW_USDT|1.503600|-8.21|-16.00|-2.87|10247260|2.00|
|ZEC_USDT|1263.000000|-6.95|2.32|-1.61|2195277088|0.08|
|BNB_USDT|702.100000|-6.64|-3.99|-1.30|56592216|1.42|
|ADA_USDT|0.192700|-6.63|-9.91|-1.29|66330120|5.19|
|SHIB_USDT|0.000005|-6.57|-5.75|-1.23|7750607|2.13|
|DOGE_USDT|0.075460|-6.41|-4.68|-1.07|129840251|1.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|APT_USDT|0.620700|0.612600|0.620600|1.83|N|Y/Y|Y/Y|Y|N|
|CRV_USDT|0.283900|0.278500|0.283900|0.06|N|Y/Y|Y/Y|Y|N|
|ETHFI_USDT|0.606400|0.603100|0.606400|1.70|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.117200|0.116180|0.117230|0.44|N|Y/Y|Y/Y|Y|N|
|FET_USDT|0.163400|0.163000|0.163400|0.59|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|7.134000|7.109000|7.134000|1.97|N|Y/Y|Y/Y|Y|N|
|JUP_USDT|0.254700|0.252800|0.254600|0.23|N|Y/Y|Y/Y|Y|N|
|LDO_USDT|0.330100|0.324500|0.330100|1.02|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|2.829300|2.789700|2.829300|1.18|N|Y/Y|Y/Y|Y|N|
|PENGU_USDT|0.007144|0.007058|0.007144|5.42|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.004071|0.004016|0.004073|0.60|N|Y/Y|Y/Y|Y|N|
|PYTH_USDT|0.061330|0.060550|0.061330|1.09|N|Y/Y|Y/Y|Y|N|
|TAO_USDT|232.600000|231.900000|232.500000|1.85|N|Y/Y|Y/Y|Y|N|
|TIA_USDT|0.468100|0.457700|0.468200|7.87|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.556000|1.531000|1.556000|0.81|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- APT_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.622500, depth_time=2026-10-30T10:30:27+00:00, book20_bid_proxy_usdt=107168, book20_ask_proxy_usdt=117973, funding_indicative=0.000060, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.74%, turnover=11958456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CRV_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.286500, depth_time=2026-10-30T10:30:09+00:00, book20_bid_proxy_usdt=500744, book20_ask_proxy_usdt=463109, funding_indicative=-0.000242, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-15.50%, turnover=9293589. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ETHFI_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.612200, depth_time=2026-10-30T10:30:31+00:00, book20_bid_proxy_usdt=189336, book20_ask_proxy_usdt=157518, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.75%, turnover=5858737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.117800, depth_time=2026-10-30T10:30:18+00:00, book20_bid_proxy_usdt=44374, book20_ask_proxy_usdt=51907, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.79%, turnover=15531926. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.165300, depth_time=2026-10-30T10:30:27+00:00, book20_bid_proxy_usdt=1079015, book20_ask_proxy_usdt=562856, funding_indicative=0.000100, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-11.58%, turnover=14126953. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=7.310000, depth_time=2026-10-30T10:30:22+00:00, book20_bid_proxy_usdt=246344, book20_ask_proxy_usdt=297238, funding_indicative=0.000078, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.27%, turnover=32345685. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JUP_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.256000, depth_time=2026-10-30T10:30:42+00:00, book20_bid_proxy_usdt=379251, book20_ask_proxy_usdt=455887, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.61%, turnover=7054783. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.331600, depth_time=2026-10-30T10:30:15+00:00, book20_bid_proxy_usdt=297153, book20_ask_proxy_usdt=221214, funding_indicative=0.000093, next_funding_utc=2026-10-30T16:00:00+00:00, funding_cycle_h=8, 24h_change=-12.76%, turnover=6357218. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=2.864000, depth_time=2026-10-30T10:30:16+00:00, book20_bid_proxy_usdt=40150, book20_ask_proxy_usdt=22538, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-13.12%, turnover=18187177. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.007173, depth_time=2026-10-30T10:30:25+00:00, book20_bid_proxy_usdt=283376, book20_ask_proxy_usdt=79399, funding_indicative=0.000037, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-12.13%, turnover=9964036. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.004084, depth_time=2026-10-30T10:30:36+00:00, book20_bid_proxy_usdt=1666246, book20_ask_proxy_usdt=1248133, funding_indicative=0.000002, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.03%, turnover=30514193. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PYTH_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.061390, depth_time=2026-10-30T10:30:09+00:00, book20_bid_proxy_usdt=226554, book20_ask_proxy_usdt=157549, funding_indicative=-0.000158, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-16.20%, turnover=5263135. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TAO_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=235.450000, depth_time=2026-10-30T10:30:34+00:00, book20_bid_proxy_usdt=39850, book20_ask_proxy_usdt=94974, funding_indicative=0.000050, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-10.11%, turnover=87742669. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=0.469400, depth_time=2026-10-30T10:30:13+00:00, book20_bid_proxy_usdt=159004, book20_ask_proxy_usdt=553754, funding_indicative=-0.000035, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-14.76%, turnover=19891092. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-10-30T10:30:02+00:00, last15m_closed_end=2026-10-30T10:30+00:00, prior8high=1.555000, depth_time=2026-10-30T10:30:40+00:00, book20_bid_proxy_usdt=1383948, book20_ask_proxy_usdt=1189955, funding_indicative=-0.000110, next_funding_utc=2026-10-30T12:00:00+00:00, funding_cycle_h=4, 24h_change=-9.95%, turnover=11083430. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
