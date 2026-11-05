# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T11:00:47Z**
- feed_generated_utc: 2026-11-05T11:00:49+00:00
- source_sha256: `e1dbd7933d6a121c35dc9182960c4bcb75a6db1cde9e851a31af35758575c6a0`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T11:00+00:00, close=80277.5, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T11:00+00:00, close=80277.5, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T08:00+00:00, close=80362.3, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|AKE_USDT|0.002592|-18.72|-87.10|-18.72|16893272|3.85|
|TRUMPOFFICIAL_USDT|1.260000|-11.64|-26.27|-11.64|25721152|7.93|
|ZRO_USDT|1.750100|-7.38|2.22|-7.38|7277083|0.57|
|HYPE_USDT|82.362000|-4.55|3.13|-4.55|76769958|0.12|
|WLD_USDT|0.374200|-4.17|-13.53|-4.17|61767707|2.67|
|FET_USDT|0.157000|-3.85|-13.59|-3.85|7453412|6.37|
|PUMPFUN_USDT|0.004285|-3.20|1.85|-3.20|12754698|2.33|
|NEAR_USDT|4.019000|-3.01|-13.17|-3.01|68943805|2.49|
|PENGU_USDT|0.007199|-2.58|-7.18|-2.58|5614903|1.39|
|ENA_USDT|0.179440|-2.53|-8.53|-2.53|85531147|0.56|
|DOT_USDT|0.952800|-2.44|-5.06|-2.44|11606171|1.05|
|SEI_USDT|0.048820|-2.26|-7.62|-2.26|5721204|2.05|
|OP_USDT|0.111220|-1.95|0.12|-1.95|7988716|0.90|
|ARB_USDT|0.163500|-1.85|-2.51|-1.85|20596125|1.83|
|PEPE_USDT|0.000005|-1.79|2.47|-1.79|120417539|0.20|
|ONDO_USDT|0.401900|-1.75|-4.12|-1.75|21231987|2.49|
|XPL_USDT|0.064580|-1.49|-16.87|-1.49|6988427|1.55|
|AVAX_USDT|8.753000|-1.22|-1.50|-1.22|21267974|1.14|
|UNI_USDT|7.458000|-1.21|5.23|-1.21|166017475|1.34|
|AAVE_USDT|132.420000|-1.20|-0.21|-1.20|14472733|0.76|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002592|0.002070|0.002594|1.45|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.163500|0.163560|0.163520|1.03|N|N/N|N/N|N|N|
|DOT_USDT|0.952800|0.952500|0.952800|0.08|N|N/N|Y/N|N|N|
|ENA_USDT|0.179440|0.180010|0.179440|1.00|N|Y/N|N/N|N|N|
|FET_USDT|0.157000|0.157500|0.157000|2.98|Y|Y/Y|N/N|N|N|
|HYPE_USDT|82.362000|82.538000|82.362000|2.48|Y|Y/Y|Y/Y|N|Y|
|NEAR_USDT|4.019000|4.006000|4.019000|1.90|N|Y/N|Y/Y|N|N|
|OP_USDT|0.111220|0.111030|0.111220|0.59|N|N/N|N/Y|N|N|
|PENGU_USDT|0.007199|0.007193|0.007199|0.56|N|Y/Y|Y/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.62|N|Y/N|N/N|N|N|
|PUMPFUN_USDT|0.004285|0.004293|0.004285|1.36|Y|Y/N|N/N|N|N|
|SEI_USDT|0.048820|0.048890|0.048820|0.21|N|N/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.260000|1.252000|1.260000|1.28|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374200|0.374400|0.374200|3.74|Y|Y/Y|Y/Y|N|Y|
|ZRO_USDT|1.750100|1.763300|1.750100|9.22|Y|Y/Y|Y/N|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.002753, depth_time=2026-11-05T11:00:08+00:00, book20_bid_proxy_usdt=34252, book20_ask_proxy_usdt=31672, funding_indicative=-0.008982, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-18.72%, turnover=16893272. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.165760, depth_time=2026-11-05T11:00:43+00:00, book20_bid_proxy_usdt=82705, book20_ask_proxy_usdt=132914, funding_indicative=-0.000019, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.85%, turnover=20596125. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.960200, depth_time=2026-11-05T11:00:34+00:00, book20_bid_proxy_usdt=345869, book20_ask_proxy_usdt=601271, funding_indicative=-0.000071, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.44%, turnover=11606171. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.182070, depth_time=2026-11-05T11:00:32+00:00, book20_bid_proxy_usdt=129765, book20_ask_proxy_usdt=251443, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.53%, turnover=85531147. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FET_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.160700, depth_time=2026-11-05T11:00:16+00:00, book20_bid_proxy_usdt=1811001, book20_ask_proxy_usdt=1078834, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.85%, turnover=7453412. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=84.025000, depth_time=2026-11-05T11:00:16+00:00, book20_bid_proxy_usdt=146785, book20_ask_proxy_usdt=213414, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-4.55%, turnover=76769958. target_RR/account_short_permission/settled_funding=UNKNOWN.
- NEAR_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=4.054000, depth_time=2026-11-05T11:00:27+00:00, book20_bid_proxy_usdt=6077786, book20_ask_proxy_usdt=4262774, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.01%, turnover=68943805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.112890, depth_time=2026-11-05T11:00:39+00:00, book20_bid_proxy_usdt=137929, book20_ask_proxy_usdt=134926, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.95%, turnover=7988716. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.007286, depth_time=2026-11-05T11:00:27+00:00, book20_bid_proxy_usdt=285891, book20_ask_proxy_usdt=271000, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-2.58%, turnover=5614903. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.000005, depth_time=2026-11-05T11:00:46+00:00, book20_bid_proxy_usdt=52958, book20_ask_proxy_usdt=34132, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.79%, turnover=120417539. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.004346, depth_time=2026-11-05T11:00:23+00:00, book20_bid_proxy_usdt=2196184, book20_ask_proxy_usdt=1867540, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-3.20%, turnover=12754698. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.049230, depth_time=2026-11-05T11:00:38+00:00, book20_bid_proxy_usdt=326884, book20_ask_proxy_usdt=276598, funding_indicative=0.000100, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.26%, turnover=5721204. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=1.278000, depth_time=2026-11-05T11:00:06+00:00, book20_bid_proxy_usdt=1970701, book20_ask_proxy_usdt=1464706, funding_indicative=-0.000342, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-11.64%, turnover=25721152. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=0.381000, depth_time=2026-11-05T11:00:18+00:00, book20_bid_proxy_usdt=2925225, book20_ask_proxy_usdt=2412540, funding_indicative=-0.000170, next_funding_utc=2026-11-05T16:00:00+00:00, funding_cycle_h=8, 24h_change=-4.17%, turnover=61767707. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T11:00:00+00:00, last15m_closed_end=2026-11-05T11:00+00:00, prior8high=1.811300, depth_time=2026-11-05T11:00:11+00:00, book20_bid_proxy_usdt=28431, book20_ask_proxy_usdt=50213, funding_indicative=0.000050, next_funding_utc=2026-11-05T12:00:00+00:00, funding_cycle_h=4, 24h_change=-7.38%, turnover=7277083. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
