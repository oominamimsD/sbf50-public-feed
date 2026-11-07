# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T14:15:44Z**
- feed_generated_utc: 2026-11-07T14:15:46+00:00
- source_sha256: `57d86084018e340db24fd32a89e7a11baf49b34c766b8212596696c9a799c2be`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T14:15+00:00, close=75910.2, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T14:00+00:00, close=75903, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T12:00+00:00, close=75945.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|PUMPFUN_USDT|0.003761|-7.02|-8.42|-7.11|13289011|2.66|
|ZEC_USDT|1277.100000|-5.42|4.09|-5.51|2082509089|0.08|
|LIT_USDT|3.230000|-4.78|14.36|-4.87|11785737|0.31|
|ENA_USDT|0.161070|-3.84|-15.17|-3.93|27417922|0.62|
|TRUMPOFFICIAL_USDT|1.196000|-3.70|-23.91|-3.79|8666946|8.37|
|DOT_USDT|0.904000|-3.53|-6.72|-3.62|5910022|1.11|
|PEPE_USDT|0.000005|-3.28|-2.89|-3.37|71260616|0.41|
|ADA_USDT|0.182300|-3.08|-5.34|-3.17|21846061|5.48|
|ONDO_USDT|0.365000|-3.05|-8.61|-3.14|10308041|2.74|
|DASH_USDT|46.490000|-3.02|-5.19|-3.11|9351950|2.15|
|FARTCOIN_USDT|0.116430|-2.99|-3.21|-3.08|7928219|0.86|
|WLD_USDT|0.337300|-2.17|-18.11|-2.26|28062928|2.96|
|XLM_USDT|0.151730|-2.15|-11.90|-2.24|20614344|0.66|
|AVAX_USDT|8.263000|-1.72|-1.01|-1.81|11143047|1.21|
|XRP_USDT|1.167900|-1.64|-6.90|-1.73|276287879|0.86|
|DOGE_USDT|0.071940|-1.57|-5.11|-1.66|61199352|1.39|
|SUI_USDT|0.861500|-1.32|-3.10|-1.41|29762784|1.16|
|NEAR_USDT|3.710000|-1.27|-14.16|-1.36|30484083|2.70|
|BTW_USDT|1.114700|-1.10|-7.06|-1.19|6588913|1.79|
|INJ_USDT|8.221000|-1.09|15.41|-1.18|28393206|1.22|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.182300|0.182100|0.182300|0.14|N|Y/Y|Y/Y|Y|N|
|AVAX_USDT|8.263000|8.218000|8.262000|1.46|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.490000|46.370000|46.490000|4.31|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.904000|0.899300|0.904000|0.67|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.161070|0.160270|0.161070|5.29|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116430|0.115570|0.116430|0.24|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.230000|3.199900|3.230000|0.45|N|Y/Y|Y/N|Y|N|
|ONDO_USDT|0.365000|0.363400|0.365000|0.74|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.73|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003761|0.003737|0.003761|0.36|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.196000|1.188000|1.196000|1.72|N|N/Y|Y/Y|Y|N|
|WLD_USDT|0.337300|0.336900|0.337400|0.38|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.151730|0.151450|0.151730|2.97|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.167900|1.158500|1.168200|0.54|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1277.100000|1269.810000|1277.020000|0.72|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.183400, depth_time=2026-11-07T14:15:25+00:00, book20_bid_proxy_usdt=9475657, book20_ask_proxy_usdt=7961087, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.08%, turnover=21846061. target_RR/account_short_permission/settled_funding=UNKNOWN.
- AVAX_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=8.278000, depth_time=2026-11-07T14:15:38+00:00, book20_bid_proxy_usdt=1344348, book20_ask_proxy_usdt=1171350, funding_indicative=0.000027, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.72%, turnover=11143047. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=46.980000, depth_time=2026-11-07T14:15:31+00:00, book20_bid_proxy_usdt=664760, book20_ask_proxy_usdt=605964, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.02%, turnover=9351950. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.906000, depth_time=2026-11-07T14:15:21+00:00, book20_bid_proxy_usdt=543002, book20_ask_proxy_usdt=498807, funding_indicative=-0.000056, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.53%, turnover=5910022. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.162700, depth_time=2026-11-07T14:15:14+00:00, book20_bid_proxy_usdt=489132, book20_ask_proxy_usdt=179618, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.84%, turnover=27417922. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.116900, depth_time=2026-11-07T14:15:33+00:00, book20_bid_proxy_usdt=47395, book20_ask_proxy_usdt=44327, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-2.99%, turnover=7928219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=3.264000, depth_time=2026-11-07T14:15:13+00:00, book20_bid_proxy_usdt=28505, book20_ask_proxy_usdt=35033, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.78%, turnover=11785737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.366800, depth_time=2026-11-07T14:15:28+00:00, book20_bid_proxy_usdt=1990713, book20_ask_proxy_usdt=1805774, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.05%, turnover=10308041. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.000005, depth_time=2026-11-07T14:15:22+00:00, book20_bid_proxy_usdt=43708, book20_ask_proxy_usdt=60918, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.28%, turnover=71260616. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.003824, depth_time=2026-11-07T14:15:07+00:00, book20_bid_proxy_usdt=2818279, book20_ask_proxy_usdt=2303540, funding_indicative=-0.000019, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-7.02%, turnover=13289011. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=1.208000, depth_time=2026-11-07T14:15:18+00:00, book20_bid_proxy_usdt=1853108, book20_ask_proxy_usdt=1392638, funding_indicative=-0.000028, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=8666946. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.340500, depth_time=2026-11-07T14:15:35+00:00, book20_bid_proxy_usdt=3609911, book20_ask_proxy_usdt=3317079, funding_indicative=-0.000170, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.17%, turnover=28062928. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=0.152760, depth_time=2026-11-07T14:15:34+00:00, book20_bid_proxy_usdt=157453, book20_ask_proxy_usdt=222034, funding_indicative=-0.000106, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.15%, turnover=20614344. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=1.172400, depth_time=2026-11-07T14:15:42+00:00, book20_bid_proxy_usdt=3309905, book20_ask_proxy_usdt=3680052, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.64%, turnover=276287879. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T14:14:59+00:00, last15m_closed_end=2026-11-07T14:15+00:00, prior8high=1297.000000, depth_time=2026-11-07T14:15:10+00:00, book20_bid_proxy_usdt=322961, book20_ask_proxy_usdt=171758, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.42%, turnover=2082509089. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
