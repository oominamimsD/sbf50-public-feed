# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T03:45:39Z**
- feed_generated_utc: 2026-11-10T03:45:40+00:00
- source_sha256: `3fbd5c7e4f19f6ddfb70e26be0658f0ffd3c6dd1bb581f2cfa78a5dec09faea5`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 70/70 successful
- tickers: 1203; contracts: 1195; crypto_prefilter: 13; crypto_deep: 13
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T03:45+00:00, close=74390, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T03:00+00:00, close=74843.6, belowEMA20=True, EMA20down3=False
- BTC Hour4: closed_end=2026-11-10T00:00+00:00, close=75327.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002585|-47.21|-53.01|-45.74|15242646|7.72|
|JCT_USDT|0.007966|-21.37|84.52|-19.90|27929003|2.51|
|ARB_USDT|0.171180|-6.98|7.43|-5.51|31657646|0.58|
|ZEC_USDT|1147.080000|-6.41|-8.53|-4.94|2434678274|0.09|
|DOT_USDT|0.848700|-4.73|-9.14|-3.26|10874160|1.18|
|QNT_USDT|192.300000|-3.86|-5.01|-2.39|37199058|0.52|
|AAVE_USDT|128.400000|-3.71|-1.65|-2.24|13692987|0.78|
|WLD_USDT|0.315100|-3.31|-17.33|-1.84|26626226|3.17|
|DASH_USDT|46.040000|-3.31|-2.45|-1.84|15282041|2.17|
|HYPE_USDT|73.806000|-3.28|-13.89|-1.81|47601121|0.14|
|PUMPFUN_USDT|0.003563|-3.23|-13.18|-1.76|8011339|2.81|
|SOL_USDT|85.580000|-2.62|-8.48|-1.15|637209918|1.17|
|HBAR_USDT|0.066750|-2.51|-5.27|-1.04|9406098|1.50|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|128.400000|129.140000|128.400000|2.33|Y|Y/Y|N/N|Y|N|
|AKE_USDT|0.002585|0.002302|0.002584|1.02|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.171180|0.171590|0.171180|1.11|N|Y/Y|N/N|Y|N|
|DASH_USDT|46.040000|45.860000|46.040000|0.40|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.848700|0.849300|0.848700|2.70|Y|Y/Y|Y/Y|Y|Y|
|HBAR_USDT|0.066750|0.066500|0.066750|0.81|N|Y/Y|Y/N|Y|N|
|HYPE_USDT|73.806000|73.740000|73.809000|9.20|N|Y/Y|Y/Y|Y|N|
|JCT_USDT|0.007966|0.008030|0.007973|1.50|Y|Y/Y|N/N|Y|N|
|PUMPFUN_USDT|0.003563|0.003550|0.003563|1.47|N|Y/Y|Y/Y|Y|N|
|QNT_USDT|192.300000|192.510000|192.300000|0.45|N|Y/Y|Y/Y|Y|N|
|SOL_USDT|85.580000|85.640000|85.580000|0.85|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.315100|0.314400|0.315100|2.32|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1147.080000|1141.980000|1147.080000|1.05|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-10T03:45:00+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=132.100000, depth_time=2026-11-10T03:45:21+00:00, book20_bid_proxy_usdt=457574, book20_ask_proxy_usdt=542881, funding_indicative=0.000003, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.71%, turnover=13692987. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AKE_USDT: quote_utc=2026-11-10T03:44:59+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=0.002982, depth_time=2026-11-10T03:45:07+00:00, book20_bid_proxy_usdt=25805, book20_ask_proxy_usdt=68855, funding_indicative=0.000050, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-47.21%, turnover=15242646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-10T03:44:59+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=0.174390, depth_time=2026-11-10T03:45:08+00:00, book20_bid_proxy_usdt=39152, book20_ask_proxy_usdt=55548, funding_indicative=-0.000010, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.98%, turnover=31657646. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T03:45:00+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=46.900000, depth_time=2026-11-10T03:45:27+00:00, book20_bid_proxy_usdt=781838, book20_ask_proxy_usdt=559176, funding_indicative=-0.000016, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=15282041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T03:45:00+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=0.858400, depth_time=2026-11-10T03:45:17+00:00, book20_bid_proxy_usdt=775472, book20_ask_proxy_usdt=688242, funding_indicative=0.000002, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.73%, turnover=10874160. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HBAR_USDT: quote_utc=2026-11-10T03:45:00+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=0.067110, depth_time=2026-11-10T03:45:38+00:00, book20_bid_proxy_usdt=650517, book20_ask_proxy_usdt=792650, funding_indicative=0.000044, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.51%, turnover=9406098. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-10T03:44:59+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=74.972000, depth_time=2026-11-10T03:45:30+00:00, book20_bid_proxy_usdt=164844, book20_ask_proxy_usdt=47638, funding_indicative=0.000043, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.28%, turnover=47601121. target_RR/account_short_permission/settled_funding=UNKNOWN.
- JCT_USDT: quote_utc=2026-11-10T03:44:59+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=0.009990, depth_time=2026-11-10T03:45:10+00:00, book20_bid_proxy_usdt=35028, book20_ask_proxy_usdt=20150, funding_indicative=0.000497, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-21.37%, turnover=27929003. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-10T03:45:00+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=0.003599, depth_time=2026-11-10T03:45:31+00:00, book20_bid_proxy_usdt=2476380, book20_ask_proxy_usdt=2874195, funding_indicative=0.000026, next_funding_utc=2026-11-10T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.23%, turnover=8011339. target_RR/account_short_permission/settled_funding=UNKNOWN.
- QNT_USDT: quote_utc=2026-11-10T03:45:00+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=195.060000, depth_time=2026-11-10T03:45:18+00:00, book20_bid_proxy_usdt=34046, book20_ask_proxy_usdt=73041, funding_indicative=0.000010, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.86%, turnover=37199058. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SOL_USDT: quote_utc=2026-11-10T03:44:59+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=86.600000, depth_time=2026-11-10T03:45:35+00:00, book20_bid_proxy_usdt=15299187, book20_ask_proxy_usdt=19463819, funding_indicative=-0.000001, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.62%, turnover=637209918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T03:45:00+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=0.317800, depth_time=2026-11-10T03:45:26+00:00, book20_bid_proxy_usdt=5786714, book20_ask_proxy_usdt=4743569, funding_indicative=0.000047, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.31%, turnover=26626226. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T03:44:59+00:00, last15m_closed_end=2026-11-10T03:45+00:00, prior8high=1174.570000, depth_time=2026-11-10T03:45:14+00:00, book20_bid_proxy_usdt=242085, book20_ask_proxy_usdt=369193, funding_indicative=0.000068, next_funding_utc=2026-11-10T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.41%, turnover=2434678274. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
