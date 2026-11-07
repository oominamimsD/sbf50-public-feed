# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T14:30:48Z**
- feed_generated_utc: 2026-11-07T14:30:50+00:00
- source_sha256: `1afc402adb26e8d526c812c8d49f555f5b72cbf82b3eacdde46ffd5f753a5724`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T14:30+00:00, close=75900.1, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T14:00+00:00, close=75903, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T12:00+00:00, close=75945.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.124800|-34.31|-53.01|-34.39|24082820|8.01|
|PUMPFUN_USDT|0.003753|-7.21|-8.61|-7.29|13383210|2.67|
|ZEC_USDT|1275.660000|-5.53|3.97|-5.61|2098566065|0.08|
|LIT_USDT|3.222000|-5.02|14.08|-5.10|11842208|0.31|
|TRUMPOFFICIAL_USDT|1.184000|-4.66|-24.68|-4.74|8697208|8.44|
|ENA_USDT|0.160300|-4.30|-15.57|-4.38|28260707|0.62|
|DOT_USDT|0.902600|-3.68|-6.87|-3.76|5917642|1.11|
|PEPE_USDT|0.000005|-3.48|-3.10|-3.56|71638855|0.20|
|FARTCOIN_USDT|0.116210|-3.18|-3.39|-3.26|7935260|0.86|
|ONDO_USDT|0.364700|-3.13|-8.68|-3.21|10420815|2.74|
|DASH_USDT|46.440000|-3.12|-5.30|-3.20|9359557|2.15|
|ADA_USDT|0.182500|-2.97|-5.24|-3.05|21872995|5.48|
|WLD_USDT|0.337000|-2.26|-18.18|-2.34|28259915|2.97|
|XLM_USDT|0.151720|-2.16|-11.91|-2.24|20708004|0.66|
|INJ_USDT|8.152000|-1.92|14.44|-2.00|29138065|1.23|
|XRP_USDT|1.165800|-1.81|-7.07|-1.89|278172967|1.72|
|AVAX_USDT|8.259000|-1.77|-1.06|-1.85|11170336|1.21|
|DOGE_USDT|0.071870|-1.66|-5.20|-1.74|61543253|1.39|
|NEAR_USDT|3.698000|-1.59|-14.43|-1.67|30830686|2.71|
|SUI_USDT|0.860500|-1.44|-3.21|-1.52|30105750|2.32|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.182500|0.182100|0.182500|0.19|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.440000|46.370000|46.440000|0.57|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.902600|0.899300|0.902600|0.17|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.160300|0.160950|0.160300|3.08|Y|Y/Y|Y/Y|Y|Y|
|FARTCOIN_USDT|0.116210|0.115570|0.116210|0.18|N|Y/Y|Y/Y|Y|N|
|INJ_USDT|8.152000|8.195000|8.152000|4.14|Y|Y/Y|N/N|Y|N|
|LIT_USDT|3.222000|3.199900|3.222000|0.42|N|Y/Y|Y/N|Y|N|
|ONDO_USDT|0.364700|0.363400|0.364700|1.02|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.98|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003753|0.003737|0.003753|0.75|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.184000|1.188000|1.185000|1.18|N|N/Y|Y/Y|Y|N|
|UAI_USDT|0.124800|0.121600|0.124800|0.50|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.337000|0.337100|0.337000|0.75|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.151720|0.151450|0.151720|0.63|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1275.660000|1269.810000|1275.660000|0.73|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.183100, depth_time=2026-11-07T14:30:38+00:00, book20_bid_proxy_usdt=10877642, book20_ask_proxy_usdt=9050851, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.97%, turnover=21872995. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=46.980000, depth_time=2026-11-07T14:30:34+00:00, book20_bid_proxy_usdt=878330, book20_ask_proxy_usdt=649071, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.12%, turnover=9359557. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.906000, depth_time=2026-11-07T14:30:24+00:00, book20_bid_proxy_usdt=522750, book20_ask_proxy_usdt=530792, funding_indicative=-0.000055, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.68%, turnover=5917642. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.162700, depth_time=2026-11-07T14:30:21+00:00, book20_bid_proxy_usdt=141824, book20_ask_proxy_usdt=365341, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.30%, turnover=28260707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.116890, depth_time=2026-11-07T14:30:30+00:00, book20_bid_proxy_usdt=47974, book20_ask_proxy_usdt=51948, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.18%, turnover=7935260. target_RR/account_short_permission/settled_funding=UNKNOWN.
- INJ_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=8.258000, depth_time=2026-11-07T14:30:47+00:00, book20_bid_proxy_usdt=192949, book20_ask_proxy_usdt=337257, funding_indicative=0.000279, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.92%, turnover=29138065. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=3.266300, depth_time=2026-11-07T14:30:13+00:00, book20_bid_proxy_usdt=38887, book20_ask_proxy_usdt=25204, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-5.02%, turnover=11842208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.366800, depth_time=2026-11-07T14:30:32+00:00, book20_bid_proxy_usdt=2619157, book20_ask_proxy_usdt=2478648, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.13%, turnover=10420815. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.000005, depth_time=2026-11-07T14:30:27+00:00, book20_bid_proxy_usdt=41121, book20_ask_proxy_usdt=48024, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.48%, turnover=71638855. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.003814, depth_time=2026-11-07T14:30:10+00:00, book20_bid_proxy_usdt=2407007, book20_ask_proxy_usdt=2885871, funding_indicative=-0.000023, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.21%, turnover=13383210. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=1.208000, depth_time=2026-11-07T14:30:18+00:00, book20_bid_proxy_usdt=1480095, book20_ask_proxy_usdt=1502570, funding_indicative=-0.000020, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.66%, turnover=8697208. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.126700, depth_time=2026-11-07T14:30:08+00:00, book20_bid_proxy_usdt=145545, book20_ask_proxy_usdt=99067, funding_indicative=-0.000145, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.31%, turnover=24082820. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.340500, depth_time=2026-11-07T14:30:41+00:00, book20_bid_proxy_usdt=3757031, book20_ask_proxy_usdt=3596881, funding_indicative=-0.000186, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=28259915. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=0.152680, depth_time=2026-11-07T14:30:43+00:00, book20_bid_proxy_usdt=168422, book20_ask_proxy_usdt=228960, funding_indicative=-0.000102, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=20708004. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T14:29:59+00:00, last15m_closed_end=2026-11-07T14:30+00:00, prior8high=1297.000000, depth_time=2026-11-07T14:30:14+00:00, book20_bid_proxy_usdt=104446, book20_ask_proxy_usdt=452294, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.53%, turnover=2098566065. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
