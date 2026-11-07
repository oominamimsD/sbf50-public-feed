# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-07T14:45:45Z**
- feed_generated_utc: 2026-11-07T14:45:47+00:00
- source_sha256: `e87d8e9749ba06c228cc43d0e8e5c0debfdc196c6c34dcb1ec05594c1b1f15c9`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1198; contracts: 1190; crypto_prefilter: 20; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-07T14:45+00:00, close=75921, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-07T14:00+00:00, close=75903, belowEMA20=True, EMA20down3=True
- BTC Hour4: closed_end=2026-11-07T12:00+00:00, close=75945.1, belowEMA20=True, EMA20down3=True

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|UAI_USDT|0.125400|-34.00|-52.78|-34.11|24138190|7.98|
|PUMPFUN_USDT|0.003776|-6.65|-8.05|-6.76|13476999|2.65|
|ZEC_USDT|1277.140000|-5.42|4.09|-5.53|2110160732|0.08|
|LIT_USDT|3.246100|-4.31|14.93|-4.42|11898572|0.31|
|TRUMPOFFICIAL_USDT|1.191000|-4.10|-24.23|-4.21|8782775|8.40|
|ENA_USDT|0.161180|-3.77|-15.11|-3.88|30436277|0.62|
|DOT_USDT|0.903000|-3.63|-6.83|-3.74|5979175|1.11|
|PEPE_USDT|0.000005|-3.11|-2.72|-3.22|72016992|0.20|
|FARTCOIN_USDT|0.116390|-3.03|-3.25|-3.14|7952181|0.86|
|ONDO_USDT|0.365100|-3.02|-8.58|-3.13|10439441|2.74|
|ADA_USDT|0.182900|-2.76|-5.03|-2.87|21916805|5.47|
|DASH_USDT|46.620000|-2.75|-4.93|-2.86|9375086|2.15|
|XLM_USDT|0.151840|-2.08|-11.84|-2.19|20840918|0.66|
|WLD_USDT|0.338000|-1.97|-17.94|-2.08|28394692|2.96|
|XRP_USDT|1.167600|-1.66|-6.92|-1.77|279855817|0.86|
|AVAX_USDT|8.272000|-1.61|-0.91|-1.72|11291595|1.21|
|INJ_USDT|8.180000|-1.58|14.83|-1.69|29358208|1.22|
|DOGE_USDT|0.071960|-1.54|-5.09|-1.65|61981877|1.39|
|SUI_USDT|0.862100|-1.25|-3.03|-1.36|30370275|1.16|
|NEAR_USDT|3.718000|-1.06|-13.97|-1.17|31003043|2.69|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|ADA_USDT|0.182900|0.182100|0.182900|0.31|N|Y/Y|Y/Y|Y|N|
|DASH_USDT|46.620000|46.370000|46.620000|1.47|N|Y/Y|N/N|Y|N|
|DOT_USDT|0.903000|0.899300|0.902900|1.38|N|Y/Y|Y/Y|Y|N|
|ENA_USDT|0.161180|0.159800|0.161170|7.71|N|Y/Y|Y/Y|Y|N|
|FARTCOIN_USDT|0.116390|0.115570|0.116380|0.44|N|Y/Y|Y/Y|Y|N|
|LIT_USDT|3.246100|3.199900|3.244900|0.47|N|Y/Y|Y/N|Y|N|
|ONDO_USDT|0.365100|0.363400|0.365100|0.16|N|Y/Y|Y/Y|Y|N|
|PEPE_USDT|0.000005|0.000005|0.000005|0.98|N|Y/Y|Y/Y|Y|N|
|PUMPFUN_USDT|0.003776|0.003737|0.003776|0.75|N|Y/Y|Y/Y|Y|N|
|TRUMPOFFICIAL_USDT|1.191000|1.182000|1.191000|2.87|N|N/Y|Y/Y|Y|N|
|UAI_USDT|0.125400|0.121600|0.125400|0.77|N|Y/Y|Y/Y|Y|N|
|WLD_USDT|0.338000|0.336300|0.338000|0.51|N|Y/Y|Y/Y|Y|N|
|XLM_USDT|0.151840|0.151450|0.151840|0.91|N|Y/Y|Y/Y|Y|N|
|XRP_USDT|1.167600|1.158500|1.167500|0.82|N|Y/Y|Y/Y|Y|N|
|ZEC_USDT|1277.140000|1269.810000|1277.230000|0.53|N|Y/Y|Y/N|Y|N|

## Detailed time markers and risk references (NOT executable limits)
- ADA_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.183100, depth_time=2026-11-07T14:45:34+00:00, book20_bid_proxy_usdt=8519151, book20_ask_proxy_usdt=8429990, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.76%, turnover=21916805. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DASH_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=46.890000, depth_time=2026-11-07T14:45:36+00:00, book20_bid_proxy_usdt=573201, book20_ask_proxy_usdt=698993, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.75%, turnover=9375086. target_RR/account_short_permission/settled_funding=UNKNOWN.
- DOT_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.906000, depth_time=2026-11-07T14:45:21+00:00, book20_bid_proxy_usdt=505561, book20_ask_proxy_usdt=427004, funding_indicative=-0.000046, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.63%, turnover=5979175. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.162700, depth_time=2026-11-07T14:45:17+00:00, book20_bid_proxy_usdt=192296, book20_ask_proxy_usdt=375998, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.77%, turnover=30436277. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.116830, depth_time=2026-11-07T14:45:24+00:00, book20_bid_proxy_usdt=50625, book20_ask_proxy_usdt=46058, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.03%, turnover=7952181. target_RR/account_short_permission/settled_funding=UNKNOWN.
- LIT_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=3.266300, depth_time=2026-11-07T14:45:15+00:00, book20_bid_proxy_usdt=29631, book20_ask_proxy_usdt=27306, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.31%, turnover=11898572. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ONDO_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.366800, depth_time=2026-11-07T14:45:29+00:00, book20_bid_proxy_usdt=2134570, book20_ask_proxy_usdt=1457680, funding_indicative=0.000050, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-3.02%, turnover=10439441. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.000005, depth_time=2026-11-07T14:45:26+00:00, book20_bid_proxy_usdt=46880, book20_ask_proxy_usdt=36742, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=72016992. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PUMPFUN_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.003813, depth_time=2026-11-07T14:45:10+00:00, book20_bid_proxy_usdt=2887907, book20_ask_proxy_usdt=2422746, funding_indicative=-0.000024, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-6.65%, turnover=13476999. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=1.208000, depth_time=2026-11-07T14:45:18+00:00, book20_bid_proxy_usdt=1789522, book20_ask_proxy_usdt=1584289, funding_indicative=-0.000017, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-4.10%, turnover=8782775. target_RR/account_short_permission/settled_funding=UNKNOWN.
- UAI_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.126700, depth_time=2026-11-07T14:45:07+00:00, book20_bid_proxy_usdt=182518, book20_ask_proxy_usdt=142288, funding_indicative=-0.000139, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=4, 24h_change=-34.00%, turnover=24138190. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.340500, depth_time=2026-11-07T14:45:41+00:00, book20_bid_proxy_usdt=2738935, book20_ask_proxy_usdt=3630140, funding_indicative=-0.000197, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.97%, turnover=28394692. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XLM_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=0.152460, depth_time=2026-11-07T14:45:39+00:00, book20_bid_proxy_usdt=127053, book20_ask_proxy_usdt=297308, funding_indicative=-0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-2.08%, turnover=20840918. target_RR/account_short_permission/settled_funding=UNKNOWN.
- XRP_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=1.168400, depth_time=2026-11-07T14:45:44+00:00, book20_bid_proxy_usdt=3528704, book20_ask_proxy_usdt=4200874, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-1.66%, turnover=279855817. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ZEC_USDT: quote_utc=2026-11-07T14:45:03+00:00, last15m_closed_end=2026-11-07T14:45+00:00, prior8high=1294.230000, depth_time=2026-11-07T14:45:12+00:00, book20_bid_proxy_usdt=440564, book20_ask_proxy_usdt=104019, funding_indicative=0.000100, next_funding_utc=2026-11-07T16:00:00+00:00, funding_cycle_h=8, 24h_change=-5.42%, turnover=2110160732. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
