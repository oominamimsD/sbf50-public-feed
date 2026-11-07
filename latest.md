# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T02:30:43Z**
- feed_generated_utc: 2026-11-07T02:30:45+00:00
- source_sha256: `b674e5ca67e22ab000fab0a698699fd4475e14bb32de014d488663e0ad5a81a1`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 17; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T02:30+00:00, close=76024.7, belowEMA20=False, EMA20down3=False
- BTC Min60: closed_end=2026-11-07T02:00+00:00, close=76000, belowEMA20=False, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T00:00+00:00, close=75811.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.143900|-24.26|-45.82|-24.51|35244191|6.96|
|CYBER_USDT|0.311500|-12.00|14.01|-12.25|6450514|3.21|
|ANTHROPIC_USDT|1342.780000|-6.17|-19.90|-6.42|7231014|0.15|
|TRUMPOFFICIAL_USDT|1.196000|-3.70|-23.91|-3.95|11231547|8.37|
|DOT_USDT|0.903700|-3.56|-6.75|-3.81|6844201|5.53|
|PUMPFUN_USDT|0.003941|-2.57|-4.04|-2.82|12402395|2.54|
|APT_USDT|0.602100|-2.47|-4.07|-2.72|5225875|1.66|
|OP_USDT|0.104820|-2.32|-3.13|-2.57|5891913|1.91|
|ARB_USDT|0.164570|-2.16|1.51|-2.41|26296206|0.61|
|ENA_USDT|0.164170|-1.99|-13.54|-2.24|30774909|0.61|
|BEAT_USDT|0.107320|-1.81|2.06|-2.06|9057275|1.86|
|ADA_USDT|0.184700|-1.80|-4.10|-2.05|27037737|5.41|
|ONDO_USDT|0.371100|-1.43|-7.08|-1.68|10581784|2.69|
|AAVE_USDT|130.180000|-1.37|3.61|-1.62|17570714|0.77|
|XRP_USDT|1.173300|-1.18|-6.47|-1.43|332304552|0.85|
|FARTCOIN_USDT|0.118660|-1.14|-1.36|-1.39|12230130|0.84|
|XLM_USDT|0.153770|-0.83|-10.72|-1.08|22818566|0.65|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AAVE_USDT|130.180000|130.350000|130.180000|0.47|N|Y/Y|N/N|Y|N|
|ADA_USDT|0.184700|0.183800|0.184700|0.37|N|Y/Y|Y/Y|Y|N|
|ANTHROPIC_USDT|1342.780000|1331.280000|1342.780000|0.06|N|Y/Y|Y/Y|Y|N|
|APT_USDT|0.602100|0.601600|0.602100|1.98|N|Y/Y|Y/Y|Y|N|
|ARB_USDT|0.164570|0.164120|0.164570|0.75|N|Y/Y|N/N|Y|N|
|BEAT_USDT|0.107320|0.106510|0.107320|1.55|N|Y/N|N/N|Y|N|
|CYBER_USDT|0.311500|0.313200|0.311500|0.65|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.903700|0.904500|0.903700|2.75|Y|Y/Y|Y/Y|Y|Y|
|ENA_USDT|0.164170|0.163260|0.164170|1.54|N|Y/Y|Y/Y|Y|N|
|ONDO_USDT|0.371100|0.370300|0.371000|1.93|N|Y/Y|Y/Y|Y|N|
|OP_USDT|0.104820|0.104920|0.104820|7.72|Y|Y/Y|Y/Y|Y|Y|
|PUMPFUN_USDT|0.003941|0.003901|0.003941|0.12|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.196000|1.196000|1.196000|4.70|N|Y/Y|Y/Y|Y|N|
|UAI_USDT|0.143900|0.135100|0.143900|0.30|N|Y/Y|N/N|Y|N|
|XRP_USDT|1.173300|1.177000|1.173300|1.91|Y|Y/Y|Y/Y|Y|Y|

## Detailed time markers and risk references (NOT executable limits)
- AAVE_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=131.090000, depth_time=2026-11-07T02:30:40+00:00, book20_bid_proxy_usdt=461237, book20_ask_proxy_usdt=419574, funding_indicative=0.000056, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.37%, turnover=17570714. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ADA_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.185600, depth_time=2026-11-07T02:30:33+00:00, book20_bid_proxy_usdt=10211763, book20_ask_proxy_usdt=9721722, funding_indicative=0.000100, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.80%, turnover=27037737. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ANTHROPIC_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=1354.930000, depth_time=2026-11-07T02:30:12+00:00, book20_bid_proxy_usdt=29571, book20_ask_proxy_usdt=43917, funding_indicative=0.000050, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-6.17%, turnover=7231014. target_RR/account_short_permission/settled_funding=UNKNOWN.
- APT_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.605200, depth_time=2026-11-07T02:30:22+00:00, book20_bid_proxy_usdt=154473, book20_ask_proxy_usdt=182600, funding_indicative=0.000000, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.47%, turnover=5225875. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.165540, depth_time=2026-11-07T02:30:26+00:00, book20_bid_proxy_usdt=89781, book20_ask_proxy_usdt=78272, funding_indicative=-0.000027, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.16%, turnover=26296206. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BEAT_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.108860, depth_time=2026-11-07T02:30:31+00:00, book20_bid_proxy_usdt=11462, book20_ask_proxy_usdt=17502, funding_indicative=0.000120, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.81%, turnover=9057275. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CYBER_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.336400, depth_time=2026-11-07T02:30:09+00:00, book20_bid_proxy_usdt=105393, book20_ask_proxy_usdt=159568, funding_indicative=-0.002165, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-12.00%, turnover=6450514. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.912000, depth_time=2026-11-07T02:30:17+00:00, book20_bid_proxy_usdt=272843, book20_ask_proxy_usdt=369070, funding_indicative=0.000096, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.56%, turnover=6844201. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.164780, depth_time=2026-11-07T02:30:29+00:00, book20_bid_proxy_usdt=149350, book20_ask_proxy_usdt=509521, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.99%, turnover=30774909. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.372500, depth_time=2026-11-07T02:30:37+00:00, book20_bid_proxy_usdt=2375998, book20_ask_proxy_usdt=1068163, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-1.43%, turnover=10581784. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.105740, depth_time=2026-11-07T02:30:24+00:00, book20_bid_proxy_usdt=77816, book20_ask_proxy_usdt=82760, funding_indicative=-0.000030, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.32%, turnover=5891913. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.003956, depth_time=2026-11-07T02:30:14+00:00, book20_bid_proxy_usdt=2376400, book20_ask_proxy_usdt=2023494, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-2.57%, turnover=12402395. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=1.206000, depth_time=2026-11-07T02:30:13+00:00, book20_bid_proxy_usdt=1312062, book20_ask_proxy_usdt=1393902, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-3.70%, turnover=11231547. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=0.145900, depth_time=2026-11-07T02:30:07+00:00, book20_bid_proxy_usdt=165606, book20_ask_proxy_usdt=138136, funding_indicative=0.000050, next_funding_utc=2026-11-07T04:00:00+00:00, funding_cycle_h=4, 24h_change=-24.26%, turnover=35244191. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T02:29:59+00:00, last15m_closed_end=2026-11-07T02:30+00:00, prior8high=1.181600, depth_time=2026-11-07T02:30:42+00:00, book20_bid_proxy_usdt=3866749, book20_ask_proxy_usdt=3352847, funding_indicative=0.000054, next_funding_utc=2026-11-07T08:00:00+00:00, funding_cycle_h=8, 24h_change=-1.18%, turnover=332304552. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
