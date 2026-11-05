# SBF50 PUBLIC READ-ONLY MARKET FEED

- market_observed_utc: **2026-11-05T05:30:44Z**
- feed_generated_utc: 2026-11-05T05:30:46+00:00
- source_sha256: `d3247c6e37372bbbcf0f414309c69c725324b8519cb97484fb9ed8c046dfb559`
- api_status: **PUBLIC_SNAPSHOT_OK**; public MEXC new host api.mexc.com
- API: 80/80 successful
- tickers: 1187; contracts: 1179; crypto_prefilter: 19; crypto_deep: 15
- snapshot_age_at_feed_build: 0.04 minutes (MUST RECHECK NOW against market_observed_utc)

**CAUTION: Research snapshot, NOT a confirmed actionable trade setup. Verify freshness <=20min and new stop/target/RR and public depth. No account permission or fills verified.**

## BTC completed-bar context
- BTC Min15: closed_end=2026-11-05T05:30+00:00, close=80436, belowEMA20=True, EMA20down3=True
- BTC Min60: closed_end=2026-11-05T05:00+00:00, close=80490.1, belowEMA20=False, EMA20down3=False
- BTC Hour4: closed_end=2026-11-05T04:00+00:00, close=80514.9, belowEMA20=False, EMA20down3=False

## Crypto-only cross-sectional prefilter (not final signals)
|Symbol|Last USDT|24h %|7d %|vs BTC 24h pp|24h turnover USDT|spread bp|
|---|---:|---:|---:|---:|---:|---:|
|IDOL_USDT|0.020434|-12.92|136.04|-13.11|5511307|3.43|
|TRUMPOFFICIAL_USDT|1.249000|-12.28|-26.91|-12.47|26824435|8.00|
|CLANKER_USDT|16.760000|-9.94|25.44|-10.13|20107923|5.96|
|AKE_USDT|0.002596|-7.61|-87.08|-7.80|16320166|7.72|
|VVV_USDT|21.504000|-7.12|-9.71|-7.31|5259910|0.47|
|BTW_USDT|1.023600|-6.86|-41.10|-7.05|5737219|2.93|
|WLD_USDT|0.374200|-4.56|-13.53|-4.75|67702912|2.67|
|FARTCOIN_USDT|0.124340|-4.43|-5.07|-4.62|17404800|4.83|
|PEPE_USDT|0.000005|-4.41|1.93|-4.60|135338351|1.22|
|SEI_USDT|0.048100|-4.20|-8.98|-4.39|6799444|2.08|
|OP_USDT|0.109620|-4.01|-1.31|-4.20|10075415|0.91|
|ENA_USDT|0.179250|-3.50|-8.62|-3.69|100869956|0.56|
|PENGU_USDT|0.007203|-3.21|-7.12|-3.40|7643080|1.39|
|ARB_USDT|0.163040|-3.11|-2.78|-3.30|22215743|0.61|
|HYPE_USDT|83.440000|-2.86|4.48|-3.05|83239979|1.08|
|ZRO_USDT|1.818600|-2.47|6.22|-2.66|9252943|1.10|
|DOT_USDT|0.945200|-2.45|-5.81|-2.64|12029053|1.06|
|AVAX_USDT|8.743000|-2.28|-1.62|-2.47|25588481|1.15|
|LIT_USDT|3.356300|-1.93|14.24|-2.12|9324723|0.30|

## Detailed crypto-only completed candle diagnostics
|Symbol|Last USDT|15m 8-low|15m last close|15m volume x20 median|15m break+vol|1h below/down|4h below/down|BTC weak|ALT subgate|
|---|---:|---:|---:|---:|---|---|---|---|---|
|AKE_USDT|0.002596|0.002428|0.002597|2.41|N|Y/Y|Y/Y|N|N|
|ARB_USDT|0.163040|0.162680|0.163040|0.42|N|N/N|N/N|N|N|
|BTW_USDT|1.023600|1.015400|1.023600|0.66|N|Y/Y|Y/Y|N|N|
|CLANKER_USDT|16.760000|16.230000|16.760000|0.30|N|Y/Y|N/N|N|N|
|ENA_USDT|0.179250|0.179340|0.179250|0.88|N|N/N|N/N|N|N|
|FARTCOIN_USDT|0.124340|0.124180|0.124340|1.22|N|N/N|N/N|N|N|
|HYPE_USDT|83.440000|83.085000|83.450000|1.35|N|Y/Y|Y/Y|N|N|
|IDOL_USDT|0.020434|0.020300|0.020434|2.24|N|Y/Y|N/N|N|N|
|OP_USDT|0.109620|0.109200|0.109570|3.43|N|Y/Y|Y/Y|N|N|
|PENGU_USDT|0.007203|0.007196|0.007207|4.67|N|Y/N|N/N|N|N|
|PEPE_USDT|0.000005|0.000005|0.000005|2.65|Y|Y/N|N/N|N|N|
|SEI_USDT|0.048100|0.048230|0.048110|0.92|N|Y/Y|N/N|N|N|
|TRUMPOFFICIAL_USDT|1.249000|1.243000|1.249000|0.88|N|Y/Y|Y/Y|N|N|
|VVV_USDT|21.504000|21.524000|21.511000|0.50|N|Y/Y|Y/Y|N|N|
|WLD_USDT|0.374200|0.371600|0.374300|0.75|N|Y/Y|Y/Y|N|N|

## Detailed time markers and risk references (NOT executable limits)
- AKE_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.002618, depth_time=2026-11-05T05:30:15+00:00, book20_bid_proxy_usdt=43581, book20_ask_proxy_usdt=40783, funding_indicative=-0.000544, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.61%, turnover=16320166. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ARB_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.165340, depth_time=2026-11-05T05:30:41+00:00, book20_bid_proxy_usdt=107447, book20_ask_proxy_usdt=176823, funding_indicative=-0.000137, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-3.11%, turnover=22215743. target_RR/account_short_permission/settled_funding=UNKNOWN.
- BTW_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=1.061500, depth_time=2026-11-05T05:30:16+00:00, book20_bid_proxy_usdt=13103, book20_ask_proxy_usdt=21542, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-6.86%, turnover=5737219. target_RR/account_short_permission/settled_funding=UNKNOWN.
- CLANKER_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=17.070000, depth_time=2026-11-05T05:30:12+00:00, book20_bid_proxy_usdt=150261, book20_ask_proxy_usdt=158882, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-9.94%, turnover=20107923. target_RR/account_short_permission/settled_funding=UNKNOWN.
- ENA_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.183980, depth_time=2026-11-05T05:30:35+00:00, book20_bid_proxy_usdt=76599, book20_ask_proxy_usdt=228800, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.50%, turnover=100869956. target_RR/account_short_permission/settled_funding=UNKNOWN.
- FARTCOIN_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.126740, depth_time=2026-11-05T05:30:25+00:00, book20_bid_proxy_usdt=55649, book20_ask_proxy_usdt=63621, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-4.43%, turnover=17404800. target_RR/account_short_permission/settled_funding=UNKNOWN.
- HYPE_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=84.509000, depth_time=2026-11-05T05:30:43+00:00, book20_bid_proxy_usdt=100166, book20_ask_proxy_usdt=141438, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-2.86%, turnover=83239979. target_RR/account_short_permission/settled_funding=UNKNOWN.
- IDOL_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.021553, depth_time=2026-11-05T05:30:07+00:00, book20_bid_proxy_usdt=4350, book20_ask_proxy_usdt=8059, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.92%, turnover=5511307. target_RR/account_short_permission/settled_funding=UNKNOWN.
- OP_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.111820, depth_time=2026-11-05T05:30:33+00:00, book20_bid_proxy_usdt=92250, book20_ask_proxy_usdt=114343, funding_indicative=0.000041, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.01%, turnover=10075415. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PENGU_USDT: quote_utc=2026-11-05T05:30:02+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.007385, depth_time=2026-11-05T05:30:38+00:00, book20_bid_proxy_usdt=303002, book20_ask_proxy_usdt=267009, funding_indicative=0.000050, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-3.21%, turnover=7643080. target_RR/account_short_permission/settled_funding=UNKNOWN.
- PEPE_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.000005, depth_time=2026-11-05T05:30:28+00:00, book20_bid_proxy_usdt=83929, book20_ask_proxy_usdt=52752, funding_indicative=0.000045, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.41%, turnover=135338351. target_RR/account_short_permission/settled_funding=UNKNOWN.
- SEI_USDT: quote_utc=2026-11-05T05:30:02+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.049420, depth_time=2026-11-05T05:30:30+00:00, book20_bid_proxy_usdt=294261, book20_ask_proxy_usdt=296835, funding_indicative=0.000100, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.20%, turnover=6799444. target_RR/account_short_permission/settled_funding=UNKNOWN.
- TRUMPOFFICIAL_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=1.290000, depth_time=2026-11-05T05:30:10+00:00, book20_bid_proxy_usdt=1529900, book20_ask_proxy_usdt=1359270, funding_indicative=-0.000347, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-12.28%, turnover=26824435. target_RR/account_short_permission/settled_funding=UNKNOWN.
- VVV_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=22.117000, depth_time=2026-11-05T05:30:16+00:00, book20_bid_proxy_usdt=19360, book20_ask_proxy_usdt=20453, funding_indicative=-0.000221, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=4, 24h_change=-7.12%, turnover=5259910. target_RR/account_short_permission/settled_funding=UNKNOWN.
- WLD_USDT: quote_utc=2026-11-05T05:30:01+00:00, last15m_closed_end=2026-11-05T05:30+00:00, prior8high=0.380500, depth_time=2026-11-05T05:30:23+00:00, book20_bid_proxy_usdt=1984938, book20_ask_proxy_usdt=2880447, funding_indicative=-0.000365, next_funding_utc=2026-11-05T08:00:00+00:00, funding_cycle_h=8, 24h_change=-4.56%, turnover=67702912. target_RR/account_short_permission/settled_funding=UNKNOWN.

## Research guards
- Independently confirm any current candidate using real-time structure, fresh orderbook/depth, account eligibility, lower target, invalidation and adequate RR.
- 15m break alone is NOT the complete SBF50 strategy. Current coin list may be selected from today (selection bias), historical backtests not proven OOS.
- If feed is stale, report DATA_BLOCKED for live entries. The researcher must re-read this page rather than reuse old prices.
- For full ZIP receipt evidence, the source remains on the Windows device; this page is only a compact public summary.
- Public markets only. No logins, positions, API keys, orders or other secrets.
