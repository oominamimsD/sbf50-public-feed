# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T04:30:36Z**
- feed_generated_utc: 2026-11-05T04:30:37+00:00
- source_sha256: `efba8aa13a204a04fbb12a4f807fac52ab88db27b0a5c9008ef477e1dcfdf55b`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 65/65 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 12; crypto_deep: 12
- snapshot_age_at_feed_build: 0.03 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T04:30+00:00, close=80419.7, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|TRUMPOFFICIAL_USDT|1.251000|-12.14|-26.79|-12.32|26773010|8.00|
|CLANKER_USDT|16.640000|-10.58|24.55|-10.76|20263648|6.01|
|AKE_USDT|0.002513|-10.56|-87.49|-10.74|16556310|3.98|
|IDOL_USDT|0.020990|-10.55|142.46|-10.73|5586932|3.33|
|BTW_USDT|1.030000|-6.27|-40.73|-6.45|5759881|0.97|
|VVV_USDT|21.829000|-5.71|-8.34|-5.89|5196793|0.46|
|WLD_USDT|0.373300|-4.79|-13.74|-4.97|70490413|2.68|
|OP_USDT|0.109890|-3.77|-1.07|-3.95|10366721|0.91|
|PEPE_USDT|0.000005|-3.09|3.35|-3.27|139397544|0.20|
|HYPE_USDT|83.564000|-2.72|4.64|-2.90|84792465|0.12|
|ZRO_USDT|1.813900|-2.72|5.95|-2.90|9996389|0.55|
|DOT_USDT|0.948300|-2.13|-5.51|-2.31|12590882|1.05|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002513|0.002354|0.002513|0.36|N|Y/Y|Y/Y|N|N|
|BTW_USDT|1.030000|1.020800|1.030000|0.54|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.640000|16.230000|16.640000|0.95|N|Y/Y|N/N|N|N|
|DOT_USDT|0.948300|0.949300|0.948300|2.44|Y|Y/Y|N/N|N|N|
|HYPE_USDT|83.564000|83.085000|83.564000|0.63|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.020990|0.021046|0.020990|1.36|Y|Y/Y|N/N|N|N|
|OP_USDT|0.109890|0.109980|0.109890|0.81|N|Y/Y|Y/Y|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.70|N|Y/N|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.251000|1.228000|1.251000|0.27|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.829000|21.353000|21.829000|1.00|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.373300|0.372200|0.373200|0.80|N|Y/Y|Y/Y|N|N|
|ZRO_USDT|1.813900|1.813800|1.814100|0.52|N|Y/Y|N/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=0.002617, depth_time=2026-11-05T04:30:12+00:00, book20_bid_proxy_usdt=46283, book20_ask_proxy_usdt=162739, funding_indicative=-0.000571, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.56%, turnover=16556310. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=1.061500, depth_time=2026-11-05T04:30:17+00:00, book20_bid_proxy_usdt=22142, book20_ask_proxy_usdt=16646, funding_indicative=0.000048, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.27%, turnover=5759881. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=17.050000, depth_time=2026-11-05T04:30:09+00:00, book20_bid_proxy_usdt=148232, book20_ask_proxy_usdt=127498, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.58%, turnover=20263648. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=0.960300, depth_time=2026-11-05T04:30:35+00:00, book20_bid_proxy_usdt=453990, book20_ask_proxy_usdt=1178564, funding_indicative=-0.000165, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-2.13%, turnover=12590882. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=84.572000, depth_time=2026-11-05T04:30:29+00:00, book20_bid_proxy_usdt=201354, book20_ask_proxy_usdt=152387, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=84792465. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=0.021620, depth_time=2026-11-05T04:30:14+00:00, book20_bid_proxy_usdt=7652, book20_ask_proxy_usdt=8540, funding_indicative=0.000052, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-10.55%, turnover=5586932. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=0.111820, depth_time=2026-11-05T04:30:25+00:00, book20_bid_proxy_usdt=93383, book20_ask_proxy_usdt=68184, funding_indicative=0.000026, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.77%, turnover=10366721. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=0.000005, depth_time=2026-11-05T04:30:28+00:00, book20_bid_proxy_usdt=93340, book20_ask_proxy_usdt=50771, funding_indicative=0.000100, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.09%, turnover=139397544. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=1.290000, depth_time=2026-11-05T04:30:07+00:00, book20_bid_proxy_usdt=1194586, book20_ask_proxy_usdt=1371988, funding_indicative=-0.000345, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.14%, turnover=26773010. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=22.117000, depth_time=2026-11-05T04:30:18+00:00, book20_bid_proxy_usdt=53675, book20_ask_proxy_usdt=14482, funding_indicative=-0.000173, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-5.71%, turnover=5196793. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=0.380500, depth_time=2026-11-05T04:30:23+00:00, book20_bid_proxy_usdt=2624194, book20_ask_proxy_usdt=2678607, funding_indicative=-0.000323, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.79%, turnover=70490413. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZRO_USDT: quote_utc=2026-11-05T04:30:01+00:00, last15m_closed_end=2026-11-05T04:30+00:00, prior8high=1.861000, depth_time=2026-11-05T04:30:33+00:00, book20_bid_proxy_usdt=68207, book20_ask_proxy_usdt=19832, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.72%, turnover=9996389. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
