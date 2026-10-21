# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-10-21T22:15:39Z**
- feed_generated_utc: 2026-10-21T22:15:42+00:00
- source_sha256: `d4a06a77f68d8d36e57ca5cf885600074ed997a7dec9c4a132bb87d03589599b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 75/75 successful
- tickers: 1207; contracts: 1199; crypto_prefilter: 14; crypto_deep: 14
- snapshot_age_at_feed_build: 0.06 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-10-21T22:15+00:00, close=84707.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-10-21T22:00+00:00, close=84800, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-10-21T20:00+00:00, close=84445.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|DOOD_USDT|0.002388|-16.03|68.40|-16.27|9124698|4.17|
|BR_USDT|0.494730|-8.64|21.33|-8.88|14866839|0.61|
|AKE_USDT|0.024734|-7.32|-4.43|-7.56|10516524|1.62|
|ZRO_USDT|1.966400|-6.23|3.82|-6.47|7249890|0.51|
|STRK_USDT|0.059300|-4.30|-23.16|-4.54|22872556|1.69|
|TIA_USDT|0.613100|-3.06|14.92|-3.30|39407649|1.63|
|FET_USDT|0.196700|-1.94|-3.53|-2.18|7474109|5.08|
|DOT_USDT|1.158700|-1.79|3.04|-2.03|16372782|0.86|
|LDO_USDT|0.408100|-1.71|0.56|-1.95|5104270|2.45|
|INJ_USDT|8.613000|-1.65|12.75|-1.89|53436829|1.16|
|APT_USDT|0.822200|-1.60|3.98|-1.84|8101939|1.22|
|ICP_USDT|2.923000|-1.44|-2.46|-1.68|5112456|3.42|
|AAVE_USDT|156.260000|-1.41|0.23|-1.65|131780501|0.64|
|OP_USDT|0.130190|-1.29|-5.89|-1.53|6469219|2.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|156.260000|156.380000|156.260000|1.21|N|N/N|N/N|N|N|
|AKE_USDT|0.024734|0.024769|0.024734|1.71|Y|Y/Y|Y/Y|N|Y|
|APT_USDT|0.822200|0.823200|0.822200|0.93|N|N/N|N/N|N|N|
|BR_USDT|0.494730|0.476600|0.494580|1.35|N|Y/Y|Y/Y|N|N|
|DOOD_USDT|0.002388|0.002430|0.002387|0.90|N|Y/Y|N/N|N|N|
|DOT_USDT|1.158700|1.160500|1.158700|1.52|Y|Y/N|N/N|N|N|
|FET_USDT|0.196700|0.197000|0.196700|1.08|N|N/N|N/N|N|N|
|ICP_USDT|2.923000|2.927000|2.924000|3.82|Y|N/N|N/N|N|N|
|INJ_USDT|8.613000|8.489000|8.613000|0.76|N|Y/Y|Y/N|N|N|
|LDO_USDT|0.408100|0.408700|0.408100|1.57|Y|Y/Y|N/N|N|N|
|OP_USDT|0.130190|0.130710|0.130200|2.53|Y|N/N|N/N|N|N|
|STRK_USDT|0.059300|0.059100|0.059300|1.74|N|N/N|N/N|N|N|
|TIA_USDT|0.613100|0.616100|0.613100|1.98|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.966400|1.985500|1.966400|4.96|Y|Y/Y|N/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=158.100000, depth_time=2026-10-21T22:15:36+00:00, book20_bid_proxy_usdt=328408, book20_ask_proxy_usdt=285480, funding_indicative=-0.000024, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.41%, turnover=131780501. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.026307, depth_time=2026-10-21T22:15:12+00:00, book20_bid_proxy_usdt=15411, book20_ask_proxy_usdt=14435, funding_indicative=0.000050, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-7.32%, turnover=10516524. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.833600, depth_time=2026-10-21T22:15:31+00:00, book20_bid_proxy_usdt=98265, book20_ask_proxy_usdt=183472, funding_indicative=0.000075, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.60%, turnover=8101939. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BR_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.504950, depth_time=2026-10-21T22:15:10+00:00, book20_bid_proxy_usdt=3184, book20_ask_proxy_usdt=3450, funding_indicative=-0.000138, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-8.64%, turnover=14866839. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOOD_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.002549, depth_time=2026-10-21T22:15:08+00:00, book20_bid_proxy_usdt=90309, book20_ask_proxy_usdt=108382, funding_indicative=0.000012, next_funding_utc=2026-10-21T23:00:00+00:00, funding_cycle_h=1, 24h_change=-16.03%, turnover=9124698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=1.176100, depth_time=2026-10-21T22:15:23+00:00, book20_bid_proxy_usdt=301530, book20_ask_proxy_usdt=275524, funding_indicative=-0.000105, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=16372782. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.200300, depth_time=2026-10-21T22:15:21+00:00, book20_bid_proxy_usdt=1699380, book20_ask_proxy_usdt=1380844, funding_indicative=0.000100, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.94%, turnover=7474109. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ICP_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=2.959000, depth_time=2026-10-21T22:15:31+00:00, book20_bid_proxy_usdt=800767, book20_ask_proxy_usdt=949014, funding_indicative=-0.000030, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.44%, turnover=5112456. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=8.739000, depth_time=2026-10-21T22:15:28+00:00, book20_bid_proxy_usdt=221483, book20_ask_proxy_usdt=227138, funding_indicative=0.000130, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.65%, turnover=53436829. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LDO_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.412800, depth_time=2026-10-21T22:15:27+00:00, book20_bid_proxy_usdt=607584, book20_ask_proxy_usdt=353876, funding_indicative=0.000003, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.71%, turnover=5104270. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.132920, depth_time=2026-10-21T22:15:38+00:00, book20_bid_proxy_usdt=79228, book20_ask_proxy_usdt=118389, funding_indicative=0.000030, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.29%, turnover=6469219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- STRK_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.061790, depth_time=2026-10-21T22:15:17+00:00, book20_bid_proxy_usdt=332578, book20_ask_proxy_usdt=453132, funding_indicative=0.000025, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-4.30%, turnover=22872556. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=0.626800, depth_time=2026-10-21T22:15:18+00:00, book20_bid_proxy_usdt=269364, book20_ask_proxy_usdt=313950, funding_indicative=-0.000112, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-3.06%, turnover=39407649. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-10-21T22:15:00+00:00, last15m_closed_end=2026-10-21T22:15+00:00, prior8high=2.023500, depth_time=2026-10-21T22:15:15+00:00, book20_bid_proxy_usdt=45499, book20_ask_proxy_usdt=53222, funding_indicative=-0.000004, next_funding_utc=2026-10-22T00:00:00+00:00, funding_cycle_h=4, 24h_change=-6.23%, turnover=7249890. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
