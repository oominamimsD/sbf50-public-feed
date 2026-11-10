# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-10T19:45:35Z**
- feed_generated_utc: 2026-11-10T19:45:36+00:00
- source_sha256: `f456d35a05d4debfa71fecc5e0f0750e770dfbb8f412bb9dcf5d116fc8c781df`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1208; contracts: 1200; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-10T19:45+00:00, close=73346, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-10T19:00+00:00, close=73455.7, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-10T16:00+00:00, close=73180.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PIEVERSE_USDT|1.847900|-8.79|57.21|-9.01|8020753|1.08|
|ZEC_USDT|1025.400000|-6.21|-14.82|-6.43|2340929305|0.88|
|DASH_USDT|42.860000|-5.05|-7.10|-5.27|13649251|2.33|
|AKE_USDT|0.002832|-2.81|-31.85|-3.03|15983333|3.53|
|UNI_USDT|6.660000|-2.48|-9.42|-2.70|28912607|1.50|
|ANTHROPIC_USDT|1296.610000|-1.58|-22.54|-1.80|8034408|0.15|
|ONDO_USDT|0.360200|-1.53|-7.45|-1.75|15204911|2.78|
|TIA_USDT|0.420000|-1.12|-3.62|-1.34|9629827|2.38|
|WLD_USDT|0.304700|-1.10|-18.11|-1.32|29816248|3.28|
|VVV_USDT|19.038000|-1.04|-14.86|-1.26|5092900|0.53|
|DOT_USDT|0.833000|-1.03|-11.62|-1.25|9046239|1.20|
|ENA_USDT|0.147880|-0.87|-14.11|-1.09|30250814|0.68|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002832|0.002739|0.002832|0.83|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1296.610000|1285.250000|1296.610000|0.07|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|42.860000|42.910000|42.860000|0.33|N|Y/Y|Y/Y|Y|N|
|DOT_USDT|0.833000|0.834200|0.833000|1.84|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.147880|0.146700|0.147880|0.65|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.360200|0.358700|0.360200|0.25|N|Y/Y|Y/N|Y|N|
|PIEVERSE_USDT|1.847900|1.808000|1.847900|0.34|N|Y/Y|N/N|Y|N|
|TIA_USDT|0.420000|0.417500|0.420000|0.48|N|Y/Y|Y/Y|Y|N|
|UNI_USDT|6.660000|6.608000|6.660000|0.44|N|Y/Y|Y/Y|Y|N|
|VVV_USDT|19.038000|18.330000|19.038000|0.51|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.304700|0.304600|0.304700|1.58|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1025.400000|1023.760000|1025.400000|0.60|N|Y/Y|Y/Y|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=0.002954, depth_time=2026-11-10T19:45:14+00:00, book20_bid_proxy_usdt=33146, book20_ask_proxy_usdt=32165, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-2.81%, turnover=15983333. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=1325.200000, depth_time=2026-11-10T19:45:19+00:00, book20_bid_proxy_usdt=8150, book20_ask_proxy_usdt=19717, funding_indicative=0.000050, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.58%, turnover=8034408. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=43.750000, depth_time=2026-11-10T19:45:10+00:00, book20_bid_proxy_usdt=761914, book20_ask_proxy_usdt=617648, funding_indicative=-0.000165, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-5.05%, turnover=13649251. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=0.845000, depth_time=2026-11-10T19:45:31+00:00, book20_bid_proxy_usdt=418799, book20_ask_proxy_usdt=972388, funding_indicative=-0.000086, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.03%, turnover=9046239. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=0.150710, depth_time=2026-11-10T19:45:33+00:00, book20_bid_proxy_usdt=223408, book20_ask_proxy_usdt=221272, funding_indicative=0.000050, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-0.87%, turnover=30250814. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=0.364800, depth_time=2026-11-10T19:45:20+00:00, book20_bid_proxy_usdt=3519266, book20_ask_proxy_usdt=2614210, funding_indicative=-0.000006, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.53%, turnover=15204911. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PIEVERSE_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=1.873800, depth_time=2026-11-10T19:45:06+00:00, book20_bid_proxy_usdt=13553, book20_ask_proxy_usdt=27301, funding_indicative=0.000139, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-8.79%, turnover=8020753. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TIA_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=0.426100, depth_time=2026-11-10T19:45:24+00:00, book20_bid_proxy_usdt=431888, book20_ask_proxy_usdt=464169, funding_indicative=0.000022, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.12%, turnover=9629827. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UNI_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=6.745000, depth_time=2026-11-10T19:45:16+00:00, book20_bid_proxy_usdt=2247653, book20_ask_proxy_usdt=3074205, funding_indicative=-0.000025, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-2.48%, turnover=28912607. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=19.408000, depth_time=2026-11-10T19:45:29+00:00, book20_bid_proxy_usdt=28961, book20_ask_proxy_usdt=23740, funding_indicative=0.000001, next_funding_utc=2026-11-10T20:00:00+00:00, funding_cycle_h=4, 24h_change=-1.04%, turnover=5092900. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=0.310500, depth_time=2026-11-10T19:45:26+00:00, book20_bid_proxy_usdt=5103284, book20_ask_proxy_usdt=6039506, funding_indicative=0.000005, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-1.10%, turnover=29816248. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-10T19:45:00+00:00, last15m_closed_end=2026-11-10T19:45+00:00, prior8high=1045.180000, depth_time=2026-11-10T19:45:09+00:00, book20_bid_proxy_usdt=156277, book20_ask_proxy_usdt=172928, funding_indicative=-0.000010, next_funding_utc=2026-11-11T00:00:00+00:00, funding_cycle_h=8, 24h_change=-6.21%, turnover=2340929305. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
